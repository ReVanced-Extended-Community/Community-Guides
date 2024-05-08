# **YT ReVanced Extended Guide**



## **Things To Know Before You Begin** 

**This guide focuses on patching YT ReVanced Extended with inotia00's patches, although basic info is provided for patching with anddea's patches, which is a fork/adaption of inotia00's patches. For info on patching ReX, see the [ReX documentation](https://github.com/YT-Advanced/revanced-documentation).**

**a)** Check out the [Frequently Asked Questions](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/faq.md#frequently-asked-questions).

**b)** This guide will use the non-root RVX Manager method. Check [inotia00's documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation) or for info on root installs and the other patching methods.

**c)** There is a [YT troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-troubleshooting.md#issues-with-patching--installation) which you should check if you get stuck at any point during this tutorial.




## **Requirements**

**a)** Your device must be running Android 8 or newer.

**b)** Your device must use the arm64-v8a architecture. 

> If you aren't sure what yours is, you will find out soon enough in the tutorial. If it is not arm64-v8a (ie: armeabi-v7a), refer to the [YT troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-troubleshooting.md#issues-with-patching--installation) for instructions.




## **1. Downloading RVX Manager, YT APK, & GmsCore**

**a)** Download and install the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

> If you get an error saying "App not installed as app isn't compatible with your device." it means that your device isn't supported by the RVX Manager. Refer to the [YT troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-troubleshooting.md#issues-with-patching--installation) for instructions.

**b)** Download and install [ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases/latest). (If you are using Hauwei or Xiomi, be sure to select the special download for your device.)

**c)** This step varies depending on whether you want to use inotia00's or anddea's patches. Open the RVX Manager > Settings > Sources:

* For inotia00's patches, press the reset button in the top-right corner if your sources are not configured to the [default](https://imgur.com/a/MHOOnUW).

* For anddea's patches, set the sources like in [this image](https://imgur.com/a/vXTfyFV).

(All users continue here): Press "OK" and restart the RVX Manager to apply the changes. Reopen the RVX Manager > Patcher > Select an application, and press the button with the suggested YouTube version. It will open a search in your browser so you can download that APK. You want to download the `nodpi` variant of the suggested YouTube version from apkmirror.com. 

> Example: In [this example](https://imgur.com/a/ly91opd), the Manager is suggesting version `19.02.39`. After tapping on the suggested version, a search opened up for an APK of that YouTube version. The result from apkmirror.com that is of the nodpi variant and of the suggested version is the one to use, as shown in [this screenshot](https://imgur.com/a/O5HXm2M). If you can't find it, go to [apkmirror.com/youtube](https://www.apkmirror.com/apk/google-inc/youtube/) and manually find the suggested version. Download the nodpi variant from the download page, as shown in [this screenshot](https://imgur.com/a/1NHzM2B).




## **2. Patching The APK**

Open the RVX Manager and press Patcher > Select an application > **STORAGE**, and then select the YouTube APK that you downloaded from APKMirror. (It will probably be in your downloads folder.)

If you want to customize the patch selection or patch options, press "Selected patches". 

> If you are prevented from changing the patch selection, you can enable the `Allow changing patch selection` toggle in the RVX Manager settings. If you need to reset to the default selection, tap the "Default" button at the top of the patch selection menu.

You can see examples of what some of the patches do [here](https://github.com/ReVanced-Extended-Community/Patches-Documentation#youtube). Note that it is a work-in-progress.

Patches that have the ⚙️ symbol have additional settings (AKA patch options) that you can configure before patching. Noteable ones are the `Theme` and `Custom branding icon YouTube` patches, the latter of which has [3 preset app icons](https://imgur.com/a/qlelvZk) you can choose from.

> If you decide not to use the default selection, you still **must** include the `GmsCore support` patch for non-root installs.


When ready to patch, press "Done" and then "Patch". Patching generally takes 2-5 minutes. If you leave the app it may cancel without warning. If any errors or failures occur use the button in the bottom left corner to copy the full log in order to make troubleshooting easier.




## **3. Installation**

When patching is finished press "Install". You can also export the APK by tapping the save icon as shown in [this image](https://imgur.com/a/FKD0okE).

You may get a pop-up saying that the installation was blocked because it is an unknown app. Tap **"More details"** and then **"Install anyway"** as shown [here](https://imgur.com/a/iLP2m7l).

> If you get an installation error follow the prompts in the Manager to try to resolve the issue, or see the [YT troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-troubleshooting.md#issues-with-patching--installation).




# **4. Additional Setup**

Aside from the detailed setup instructions below that are for the more complex configurations, many settings / patches can be enabled/disabled in the YT ReVanced Extended app. To find these settings, open YT ReVanced Extended > Profile picture > Settings > ReVanced Extended.

You can see screenshots demonstrating what many of the settings do [here](https://kazimmt.github.io/RVX-Features/rvx-features/yt-rvx-features/). Note that it is a work-in-progress.



### **Open Links By Default**

Follow these steps so that when you open a YouTube link it will open in the YT ReVanced Extended app instead of the official YouTube app.

> If you are using MIUI, you may need to use [Hidden Settings for MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets). After you install it, open it and tap on Manage applications. Then continue with the steps below.

**a)** Uninstall or disable the official YouTube app. Or go to the App info of official YouTube, tap on Set as default / Open by default > Open supported links, **Off**.

**b)** Now open the App info of YT ReVanced Extended > Set as default / Open by default > Open supported links, **On**.

**c)** Then go back to the previous page. Tap "Supported web addresses" > turn them all **On**.




### **Downloader Setup**

There are three important things to know about downloading in YT ReVanced Extended.

**a)** You need to have included the `Overlay buttons` patch.

**b)** The ReVanced Extended download function is separate from the built-in download button which is reserved for YT Premium members. The ReVanced Extended download button can be enabled by going into Settings > ReVanced Extended > Player > Player buttons > Show external download button, **On**. The download button will appear beside the full-screen button in the video player.

**c)** When you press the download button it will attempt to open [YTDLnis](https://github.com/deniscerri/ytdlnis/releases/latest) to download the media. You can check out [this post](https://www.reddit.com/r/revancedapp/comments/xft8vq) for the download links and info of several other downloaders you can use. 

If you want to use a downloader other than YTDLnis, navigate to Settings > ReVanced Extended > Player > Player buttons > External downloader package name. Then select the downloader from the list or enter the package name of the downloader, press "OK" and install it if prompted. 





# **Updating ReVanced Extended**

To update YT ReVanced Extended you must patch a new APK and then install the newly patched APK on top of the old YT ReVanced Extended app as an update. Installing it as an update will preserve your settings configuration.

Normally, you do not need to uninstall your old YT ReVanced Extended app before installing the new one. However, there are two things to note.

**1)** Some bugs can persist or occur if you do not do a fresh install.

**2)** If the new and old YT ReVanced Extended APKs were not signed using the same keystore file, the new YT ReVanced Extended APK cannot be installed without uninstalling the old YT ReVanced Extended app first. (Read below to understand what a keystore is.)

If either of these issues apply to you, read below to learn how to import and export your YT ReVanced Extended settings so you don't need to reconfigure them.




### **Keystore Info**

The keystore is a file that the RVX Manager (and any other ReVanced patcher) uses to sign the patched APK. If the new YT ReVanced Extended APK was signed with the same keystore as the old YT ReVanced Extended APK then you will be able to install it as an update to the old YT ReVanced Extended.

If you uninstall or clear the app data of the RVX Manager the keystore file will be deleted. So be sure to export/backup the keystore before uninstalling or clearing the data of the Manager. You can export and import the keystore file from the RVX Manager settings.




### **Exporting / Importing The Settings**

If you need or want to uninstall the old YT ReVanced Extended APK and install the new APK as a fresh install, you can export the settings configuration from the old YT ReVanced Extended app and import it into the new app.

To do this, open the old YT ReVanced Extended app > Profile picture > Settings > ReVanced Extended > Miscellaneous > Import / Export settings, and either export as a `.txt` file or copy the text directly and save it to your clipboard until you are ready to paste it into the new YT ReVanced Extended app.

After installing the new YT ReVanced Extended app, open it and tap on the profile picture > Settings > ReVanced Extended > Miscellaneous > Import / Export settings, and import the `.txt` file or replace the text with the text you copied. 

The standard YouTube settings will still need to be configured, as well as any new ReVanced Extended settings.




# **More Info/Troubleshooting**

Check the [YT troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-troubleshooting.md#yt-revanced-extended-troubleshooting) for troubleshooting help.

Check the [Frequently Asked Questions](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/faq.md#frequently-asked-questions).

Check out [inotia00's GitHub](https://github.com/inotia00).