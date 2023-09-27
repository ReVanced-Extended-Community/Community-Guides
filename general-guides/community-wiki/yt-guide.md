# **YT ReVanced Extended Guide**



## **Things To Know Before You Begin** 

**a)** Check out the [Frequently Asked Questions](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/faq.md#frequently-asked-questions).

**b)** This guide will use the non-root RVX Manager method. Check [inotia00's documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation) for info on root installs and the other patching methods.

**c)** There is a [YT troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-troubleshooting.md#issues-with-patching--installation) which you should check if you get stuck at any point during this tutorial.




## **Requirements**

**a)** Your device must be running Android 8 or newer.

**b)** Your device must use the arm64-v8a architecture. (If you aren't sure what yours is, you will find out soon enough in the tutorial. If it is not arm64-v8a (ie: armeabi-v7a), refer to the [YT troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-troubleshooting.md#issues-with-patching--installation) for instructions.)




## **1. Downloading RVX Manager, YT APK, & Vanced MicroG**

**a)** Download and install the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

(If you get an error saying "App not installed as app isn't compatible with your device." it means that your device isn't supported by the RVX Manager. Refer to the [YT troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-troubleshooting.md#issues-with-patching--installation) for further instructions.) 

**b)** Download (but do **not** bother installing) a [`18.31.40` (nodpi) YouTube APK](https://www.apkmirror.com/apk/google-inc/youtube/youtube-18-31-40-release/youtube-18-31-40-android-apk-download/).

**c)** Download and install [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest). This will connect the patched YT Music app to the Google servers. You can use an updated forked version from [inotia00's GitHub](https://github.com/inotia00/VancedMicroG/releases/latest) if desired.




## **2. Patching The APK**

Open the RVX Manager and press Patcher > Select an application > **STORAGE**, and then select the YouTube APK that you downloaded from APKMirror. (It will probably be in your downloads folder.)

Now press "Select patches". You may get a warning saying that you shouldn't change from the default patches selection. If you want to customize the patches selection you can enable the "Enable changing selection" toggle in the RVX Manager settings. To reset to the default selection, tap the "Default" button at the top of the patches selection menu.

You can see examples of what all the patches do [here](https://github.com/ReVanced-Extended-Community/Patches-Documentation#youtube).

If you decide not to use the default selection, keep the following things in mind:

**a)** You **must** include the `MicroG Support` patch.

**b)** You can select which custom branding icon you want to use, but make sure to only select one custom branding icon patch. You can view a preview of the 3 icons [here on Imgur](https://imgur.com/a/qlelvZk). You can exclude all custom branding icon patches to get the YouTube icon.


When you are done selecting the patches you want, press "Done" and then "Patch". Patching generally takes 2-5 minutes. If you leave the app it may cancel without warning. Take screenshots of any errors / failures that occur to make troubleshooting easier.




## **3. Installation**

When patching is finished I do not recommend using the "Install" button in the Manager. Instead, export the APK by tapping the save icon as shown in [this image](https://imgur.com/a/FKD0okE). Save it, and then install the exported APK from your file manager.

You may get a pop-up saying that the installation was blocked because it is an unknown app. Tap **"More details"** and then **"Install anyway"** as shown [here](https://imgur.com/a/iLP2m7l).

(If you get an installation error see the [YT troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-troubleshooting.md#issues-with-patching--installation).)




# **4. Additional Setup**

Aside from the detailed setup instructions below that are for the more complex configurations, many settings / patches can be enabled/disabled in the YT ReVanced Extended app.

To find these settings, open YT Music Extended > Profile picture > Settings. From there you can configure the ReVanced Extended, Return YouTube Dislike, and SponsorBlock settings (if you include the necessary patches).

You can see what all of the settings do [here](https://kazimmt.github.io/RVX-Features/rvx-features/yt-rvx-features/).



### **Open Links By Default**

Follow these steps so that when you open a YouTube link it will open in the YT ReVanced Extended app instead of the official YouTube app.

(If you are using MIUI, you'll need to use [Hidden Settings for MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets). After you install it, open it and tap on Manage applications. Then continue with the steps below.)

**a)** Uninstall or disable the official YouTube app. Or go to the App info of official YouTube, tap on Set as default / Open by default > Open supported links, **Off**.

**b)** Now open the App info of YT ReVanced Extended > Set as default / Open by default > Open supported links, **On**.

**c)** Then go back to the previous page. Tap "Supported web addresses" > turn them all **On**. (If you are on MIUI, tap on "Add link" and check off all URLs. Then press "Add".)




### **Downloader Setup**

There are three important things to know about downloading in YT ReVanced Extended.

**a)** You need to have included the `Overlay Buttons` patch.

**b)** The ReVanced Extended download function is separate from the built-in download button which is reserved for YT Premium members. The ReVanced Extended download button can be enabled by going into Settings > ReVanced Extended > Overlay buttons > Show download button, **On**. The download button will appear beside the full-screen button in the video player.

**c)** When you press the download button it will attempt to open [YTDLnis](https://github.com/deniscerri/ytdlnis/releases/latest) to download the media. You can check out [this post](https://www.reddit.com/r/revancedapp/comments/xft8vq) for the download links and info of several other downloaders you can use. 

If you want to use a downloader other than YTDLnis, install the downloader and open YT ReVanced Extended and navigate to Settings > ReVanced Extended > Overlay buttons > External downloader settings. Then enter the package name of the downloader and then restart the app. 





# **Updating ReVanced Extended**

To update YT ReVanced Extended you must patch a new APK and then install the newly patched APK on top of the old YT ReVanced Extended app as an update. Installing it as an update will preserve your settings configuration.

Normally, you do not need to uninstall your old YT ReVanced Extended app before installing the new one. However, there are two things to note.

**1)** Some bugs can persist if you do not do a fresh install.

**2)** If the new and old YT ReVanced Extended APKs were not signed using the same keystore file, the new YT ReVanced Extended APK cannot be installed without uninstalling the old YT ReVanced Extended app first.




### **Keystore Info**

The keystore is a file that the RVX Manager (and any other ReVanced patcher) uses to sign the patched APK. If the new YT ReVanced Extended APK was signed with the same keystore as the old YT ReVanced Extended APK then you will be able to install it as an update to the old YT ReVanced Extended.

If you uninstall the RVX Manager or clear the app data, the keystore file will be deleted. So be sure export/backup the keystore before uninstalling or clearing the data of the Manager. You can export and import the keystore file from the RVX Manager settings.




### **Exporting / Importing The Settings**

If you need or want to uninstall the old YT ReVanced Extended APK and install the new APK as a fresh install, you can still export the settings from the old YT ReVanced Extended app and then import that file into the new app so that you won't need to reconfigure all of your settings.

To do this, open the old YT ReVanced Extended app > Profile picture > Settings > ReVanced Extended > Miscellaneous > Import/Export settings > Export settings > Save.

You'll probably also want to export the SponsorBlock settings as well. Tap on the profile picture > Settings > SponsorBlock > Import/Export settings. Now use the copy button or manually copy all of the text and save it until you are ready to paste it into the new YT ReVanced Extended app.

After installing the new YT ReVanced Extended app, open it and tap on the profile picture > Settings > ReVanced Extended > Miscellaneous > Import/Export settings > Import settings. Now select the settings file that you exported from the old app.

Now for the SponsorBlock settings. Tap on the profile picture > Settings > SponsorBlock > Import/Export settings. Now remove all of the text and paste in the text that you copied from the SponsorBlock settings in the old app.

The standard YouTube and Return YouTube Dislike settings will still need to be configured, as well as any settings for features that your old app didn't have.




# **More Info/Troubleshooting**

Check the [YT troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-troubleshooting.md#yt-revanced-extended-troubleshooting) for troubleshooting help.

Check the [Frequently Asked Questions](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/faq.md#frequently-asked-questions).

Check out [inotia00's GitHub](https://github.com/inotia00).