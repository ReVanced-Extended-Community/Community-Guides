# **YT Music ReVanced Extended Guide**


## **Things To Know Before You Begin**

**a)** This guide will use the non-root RVX Manager method. Check [inotia00's documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation) for info on root installs and the other patching methods.

**b)** There is a [YTM troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-troubleshooting.md#issues-with-patching--installation) which you should check if you get stuck at any point during this tutorial.




## **Requirements**

**a)** Your device must be running Android 8 or newer.

**b)** Your device must use the arm64-v8a architecture. (If you aren't sure what yours is, you will find out soon enough in the tutorial. If it is not arm64-v8a (ie: armeabi-v7a), refer to the [YTM troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-troubleshooting.md#issues-with-patching--installation) for instructions.)



## **1. Downloading RVX Manager, YT Music APK, & Vanced MicroG**

**a)** Download and install the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

(If you get an error saying "App not installed as app isn't compatible with your device." it means that your device isn't supported by the RVX Manager. Refer to the [YTM troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-troubleshooting.md#issues-with-patching--installation) for further instructions.)

**b)** Go to [this page](https://www.apkmirror.com/apk/google-inc/youtube-music/youtube-music-6-22-51-release/#downloads) and download the arm64-v8a variant of a YT Music `6.22.51` APK. You do not need to install it.

(If you are patching to install the patched APK on a non-armv64-v8a device, download the variant of a `6.22.51` YT Music APK that matches the architecture of the device you plan to install the patched APK on, as demonstrated [here](https://imgur.com/a/NYoAUGS). If an Android device is not arm64-v8a it is most likely armeabi-v7a.)

**c)** Download and install [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest). This will connect the patched YT Music app to the Google servers. You can use an updated forked version from [inotia00's GitHub](https://github.com/inotia00/VancedMicroG/releases/latest) if desired.




## **2. Patching The APK**

Open the RVX Manager and press Patcher > Select an application > **STORAGE** > and then select the YTM APK file that you downloaded from APKMirror. (It will probably be in your downloads folder.)

Now press "Selected patches". You may get a warning saying that you shouldn't change from the default patches selection. If you want to customize the patches selection you can enable the "Enable changing selection" toggle in the RVX Manager settings. To reset to the default selection, tap the "Default" button at the top of the patches selection menu.

You can see examples of what all of the patches do [here](https://github.com/ReVanced-Extended-Community/Patches-Documentation#youtube-music).

If you decide not to use the default selection, keep the following things in mind:

**a)** You **must** include the `MicroG Support` patch.

**b)** You can select which custom branding icon you want to use, but make sure to only select one custom branding icon patch. You can view a preview of the 3 icons [here on Imgur](https://imgur.com/a/tjuLog1). You can exclude all custom branding icon patches to get the YT Music icon.

**c)** If you are from Canada, include the `Spoof App Version` patch, which allows users to bypass the radio-only restriction that is in Canada. Additional setup is in step 4 of the guide.


When you are done selecting the patches that you want, press "Done" and then "Patch". Patching generally takes 2-5 minutes. If you leave the app it may cancel without warning. Take screenshots of any errors / failures that occur to make troubleshooting easier.




## **3. Installation**

When patching is finished I do not recommend using the "Install" button in the Manager. Instead, export the APK by tapping the save icon as shown in [this image](https://imgur.com/a/FKD0okE). Save it, and then install the exported APK from your file manager.

You may get a pop-up saying that the installation was blocked because it is an unknown app. Tap **"More details"** and then **"Install anyway"** as shown [here](https://imgur.com/a/iLP2m7l).

(If you get an installation error see the [YTM troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-troubleshooting.md#issues-with-patching--installation).)




# **4. Additional Setup**

Aside from the detailed setup instructions below that are for the more complex configurations, many settings / patches can be enabled/disabled in the YTM Extended app. 

To find these settings, open YT Music Extended > Profile picture > Settings. From there you can configure the ReVanced Extended, Return YouTube Dislike, and SponsorBlock settings (if you include the necessary patches).

You can see what all of the settings do [here](https://kazimmt.github.io/RVX-Features/rvx-features/ytm-rvx-features/).




### **Open Links By Default**

Follow these steps so that when you open a YouTube Music link it will open in the YTM Extended app instead of the official YouTube Music app.

(If you are using MIUI, you'll need to use [Hidden Settings for MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets). After you install it, open it and tap on Manage applications. Then continue with the steps below.)

**a)** Uninstall or disable the official YT Music app. Or go to the App info of official YT Music, Set as default / Open by default > Open supported links, **Off**.

**b)** Now open the App info of YTM Extended > Set as default / Open by default > Open supported links, **On**.

**c)** Then go back to the previous page. Tap "Supported web addresses" > turn them all **On**. (If you are on MIUI, tap on "Add link" and check off any URLs. Then press "Add".)




### **Android Auto Setup**

**Note:** From my experience and from what I heard, the YTM Extended home screen will not load on Android Auto. But you can start a song, playlist, or album from the app on your phone/tablet and you can then control it from Android Auto.

Here's how to set it up:

**a)** You need to have included the `Certificate Spoof` patch when you patched the app.

**b)** Once you have it installed with that patch, go to the Android Auto settings on your phone/tablet.

**c)** Scroll down to "Version and permission info".

**d)** Tap on it 10 times to enter developer mode and then tap "OK" on the popup.

**e)** Tap the 3 dots in the upper-right corner of your screen and open the Developer settings.

**f)** Scroll down and enable Unknown sources.




### **Spoof App Version Setup (for Canadian users)**

**a)** You need to have included the `Spoof App Version` patch when you patched the app.

**b)** Open YTM Extended > Profile picture > Settings > ReVanced Extended > Miscellaneous > Spoof app version, **On**.

**c)** Fully close and restart the app.

If this does not work you can use an [old version of Vanced Music](https://www.apkmirror.com/apk/team-vanced/vanced-youtube-music/vanced-youtube-music-4-27-50-release/vanced-youtube-music-4-27-50-android-apk-download/) or use a VPN to a different country to get around the Radio-only restriction.




### **Downloader Setup**

**a)** You need to have included the `Hook Download Button` patch when you patched the app.

**b)** Open YTM Extended. Tap on the profile picture > Settings > ReVanced Extended > Action Bar > Hook download button, **On**. Fully close and restart the app.

Now when you press the Download button it will attempt to open [YTDLnis](https://github.com/deniscerri/ytdlnis/releases/latest) to download the media. You can check out [this post](https://www.reddit.com/r/revancedapp/comments/xft8vq) for the download links and info of several other downloaders you can use. (Keep in mind that PowerTube is no longer functioning for YT Music downloads.)

If you want to use a downloader other than YTDLnis, install the downloader and open YTM Extended and navigate to Settings > ReVanced Extended > Action Bar > External downloader package name. Then enter the package name of the downloader and restart the app.




# **Updating ReVanced Extended**

To update YTM Extended you must patch a new APK and then install the newly patched APK on top of the old YTM Extended app as an update. Installing it as an update will preserve your settings configuration.

Normally, you do not need to uninstall your old YTM Extended app before installing the new one. However, there are two things to note.

**1)** Some bugs can persist if you do not do a fresh install.

**2)** If the new and old YTM Extended APKs were not signed using the same keystore file, the new YTM Extended APK cannot be installed without uninstalling the old YTM Extended app first.




### **Keystore Info**

The keystore is a file that the RVX Manager (and any other ReVanced patcher) uses to sign the patched APK. If the new YT ReVanced Extended APK was signed with the same keystore as the old YT ReVanced Extended APK then you will be able to install it as an update to the old YT ReVanced Extended.

If you uninstall the RVX Manager or clear the app data, the keystore file will be deleted. So be sure to export/backup the keystore before uninstalling or clearing the data of the Manager. You can export and import the keystore file from the RVX Manager settings.




### **Exporting / Importing The Settings**

If you need or want to uninstall the old YTM Extended APK and install the new APK as a fresh install, you can still export the settings from the old YT ReVanced Extended app and then import them into the new app so that you won't need to reconfigure all of your settings.

To do this, open the old YTM Extended app > Profile picture > Settings > ReVanced Extended > Miscellaneous > Import / Export > Copy. Save it in your clipboard until you are ready to paste it into the new YTM Extended app.

After installing the new YT ReVanced Extended app, open it and tap on the profile picture > Settings > Import / Export. Remove any text from the textbox and paste the text you copied from the old app. Press "Import" and restart the app.



# **More Info/Troubleshooting**

Check the [YTM troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-troubleshooting.md#yt-music-extended-troubleshooting) for troubleshooting help.

Check the [Frequently Asked Questions](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/faq.md#frequently-asked-questions).

Check out [inotia00's GitHub](https://github.com/inotia00).