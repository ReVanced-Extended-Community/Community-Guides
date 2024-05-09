# **YT Music ReVanced Extended Guide**


## **Things To Know Before You Begin**

**a)** This guide will use the non-root RVX Manager method. Check [inotia00's documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation) for info on root installs and the other patching methods.

**b)** There is a [YTM troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-troubleshooting.md#issues-with-patching--installation) which you should check if you get stuck at any point during this tutorial.




## **Requirements**

**a)** Your device must be running Android 8 or newer.

**b)** Your device must use the arm64-v8a architecture. 

> If you aren't sure what yours is, you will find out soon enough in the tutorial. If it is not arm64-v8a (ie: armeabi-v7a), refer to the [YTM troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-troubleshooting.md#issues-with-patching--installation) for instructions.



## **1. Downloading RVX Manager, YT Music APK, & Vanced MicroG**

**a)** Download and install the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

> If you get an error saying "App not installed as app isn't compatible with your device." it means that your device isn't supported by the RVX Manager. Refer to the [YTM troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-troubleshooting.md#issues-with-patching--installation) for further instructions.

**b)** Go to [apkmirror.com](https://www.apkmirror.com/apk/google-inc/youtube-music/) and download the **arm64-v8a** variant (as demonstrated [here](https://imgur.com/a/NYoAUGS)) of a version supported by the patches, such as [**`6.50.51`**](https://www.apkmirror.com/apk/google-inc/youtube-music/youtube-music-6-50-51-release/#downloads). You do not need to install it.

> If you are patching to install the patched APK on a non-armv64-v8a device, download the variant of a supported YT Music version that matches the architecture of the device you plan to install the patched APK on. If an Android device is not arm64-v8a it is most likely armeabi-v7a.

**c)** Download and install [ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases/latest). (If you are using Hauwei or Xiomi, be sure to select the special download for your device.)




## **2. Patching The APK**

Open the RVX Manager and press Patcher > Select an application > **STORAGE** > and then select the YTM APK file that you downloaded from APKMirror. (It will probably be in your downloads folder.)

If you want to customize the patch selection or patch options, press "Selected patches".

> If you are prevented from changing the patch selection, you can enable the `Allow changing patch selection` toggle in the RVX Manager settings. If you need to reset to the default selection, tap the "Default" button at the top of the patch selection menu.

You can see examples of what some of the patches do [here](https://github.com/ReVanced-Extended-Community/Patches-Documentation#youtube-music). Note that it is a work-in-progress.

Patches that have the ⚙️ symbol have additional settings (AKA patch options) that you can configure before patching, such as the `Custom branding icon YouTube Music` patch, which has [3 preset app icons](https://imgur.com/a/tjuLog1) you can choose from.

> If you decide not to use the default selection, keep the following things in mind:

> **a)** You **must** include the `GmsCore support` patch.

> **b)** If you are from Canada, include the `Spoof App Version` patch, which will allow you to bypass the radio-only restriction that is in Canada. Additional setup is in step 4 of the guide.


When ready to patch, press "Done" and then "Patch". Patching generally takes 2-5 minutes. If you leave the app it may cancel without warning. If any errors or failures occur use the button in the bottom left corner to copy the full log in order to make troubleshooting easier.




## **3. Installation**

When patching is finished press "Install". You can also export the APK by tapping the save icon as shown in [this image](https://imgur.com/a/FKD0okE).

You may get a pop-up saying that the installation was blocked because it is an unknown app. Tap **"More details"** and then **"Install anyway"** as shown [here](https://imgur.com/a/iLP2m7l).

> If you get an installation error see the [YTM troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-troubleshooting.md#issues-with-patching--installation).




# **4. Additional Setup**

Aside from the detailed setup instructions below that are for the more complex configurations, many settings / patches can be enabled/disabled in the YTM Extended app. To find these settings, open YT Music Extended > Profile picture > Settings > ReVanced Extended.

You can see screenshots demonstrating what many of the settings do [here](https://kazimmt.github.io/RVX-Features/rvx-features/ytm-rvx-features/). Note that it is a work-in-progress.




### **Open Links By Default**

Follow these steps so that when you open a YouTube Music link it will open in the YTM Extended app instead of the official YouTube Music app.

> If you are using MIUI, you may need to use [Hidden Settings for MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets). After you install it, open it and tap on Manage applications. Then continue with the steps below.

**a)** Uninstall or disable the official YT Music app. Or go to the App info of official YT Music, Set as default / Open by default > Open supported links, **Off**.

**b)** Now open the App info of YTM Extended > Set as default / Open by default > Open supported links, **On**.

**c)** Then go back to the previous page. Tap "Supported web addresses" > turn them all **On**.




### **Android Auto Setup**

> **Note:** From my experience and from what I heard, the YTM Extended home screen will not load on Android Auto. But you can start a song, playlist, or album from the app on your phone/tablet and you can then control it from Android Auto.

Here's how to set it up:

**a)** You need to have included the `Certificate Spoof` patch when you patched the app.

**b)** Once you have it installed with that patch, go to the Android Auto settings on your phone/tablet.

**c)** Scroll down to "Version and permission info".

**d)** Tap on it 10 times to enter developer mode and then tap "OK" on the popup.

**e)** Tap the 3 dots in the upper-right corner of your screen and open the Developer settings.

**f)** Scroll down and enable Unknown sources.




### **Spoof App Version Setup (for Canadian users)**

**a)** You need to have included the `Spoof App Version` patch when you patched the app.

**b)** Open YTM Extended > Profile picture > Settings > ReVanced Extended > General > Spoof app version, **On**.

**c)** Fully close and restart the app.

> You may need to navigate back to Settings > ReVanced Extended > Miscellaneous > Spoof app version target, and set it to `4.27.53`.

> If this does not work you can use an [old version of Vanced Music](https://www.apkmirror.com/apk/team-vanced/vanced-youtube-music/vanced-youtube-music-4-27-50-release/vanced-youtube-music-4-27-50-android-apk-download/) or use a VPN to a different country to get around the Radio-only restriction.




### **Downloader Setup**

**a)** You need to have included the `Hide action bar components` patch when you patched the app.

**b)** Open YTM Extended. Tap on the profile picture > Settings > ReVanced Extended > Action Bar > Override download action button, **On**. Fully close and restart the app.

Now when you press the [Download button in the player](https://imgur.com/a/phjYvbe) it will attempt to open [YTDLnis](https://github.com/deniscerri/ytdlnis/releases/latest) to download the media. You can check out [this post](https://www.reddit.com/r/revancedapp/comments/xft8vq) for the download links and info of several other downloaders you can use. (Keep in mind that PowerTube is no longer functioning for YT Music downloads.)

If you want to use a downloader other than YTDLnis, navigate to Settings > ReVanced Extended > Action Bar > External downloader package name. Then select the downloader from the list or enter the package name of the downloader, press "OK" and install it if prompted.




# **Updating ReVanced Extended**

To update YTM Extended you must patch a new APK of the same architecture and then install the newly patched APK on top of the old YTM Extended app as an update. Installing it as an update will preserve your settings configuration.

Normally, you do not need to uninstall your old YTM Extended app before installing the new one. However, there are two things to note.

**1)** Some bugs can persist or occur if you do not do a fresh install.

**2)** If the new and old YTM Extended APKs were not signed using the same keystore file, the new YTM Extended APK cannot be installed without uninstalling the old YTM Extended app first. (Read below to understand what a keystore is.)

If either of these issues apply to you, read below to learn how to import and export your YTM Extended settings so you don't need to reconfigure them.




### **Keystore Info**

The keystore is a file that the RVX Manager (and any other ReVanced patcher) uses to sign the patched APK. If the new YTM Extended APK was signed with the same keystore as the old YTM Extended APK then you will be able to install it as an update to the old YTM Extended.

If you uninstall or clear the app data of the RVX Manager the keystore file will be deleted. So be sure to export/backup the keystore before uninstalling or clearing the data of the Manager. You can export and import the keystore file from the RVX Manager settings.




### **Exporting / Importing The Settings**

If you need or want to uninstall the old YTM Extended APK and install the new APK as a fresh install, you can export the settings configuration from the old YTM Extended app and import it into the new app.

To do this, open the old YTM Extended app > Profile picture > Settings > ReVanced Extended > Miscellaneous > Import/Export settings, and either export as a `.txt` file or copy the text directly and save it to your clipboard until you are ready to paste it into the new YTM Extended app.

After installing the new YTM Extended app, open it and tap on the profile picture > Settings > Miscellaneous > Import/Export settings, and import the `.txt` file or replace the text with the text you copied.

The standard YT Music settings will still need to be configured, as well as any new ReVanced Extended settings.




# **More Info/Troubleshooting**

Check the [YTM troubleshooting page](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-troubleshooting.md#yt-music-extended-troubleshooting) for troubleshooting help.

Check the [Frequently Asked Questions](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/faq.md#frequently-asked-questions).

Check out [inotia00's GitHub](https://github.com/inotia00).
