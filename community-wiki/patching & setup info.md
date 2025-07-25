# **1. Info for Updating ReVanced Extended**

### **1a. How do I know when my patched app can be updated?**

Each time there is a new [patch release](https://github.com/inotia00/revanced-patches/releases/) you can choose to update your patched apps. You can be notified of patch releases in one of three ways:

1. By "Watching" [inotia00's revanced-patches](https://github.com/inotia00/revanced-patches) repository for new releases. (You will get an email whenever there is a public or dev patch release.)

   <details>
   <summary><strong>How to "Watch" a GitHub repository:</strong></summary>
   <br>
   <img src="/images/watch-releases.gif" width="1200"/>
   </details>

2. By joining the [ReVanced Extended Discord server](https://discord.com/invite/yMnc3EywRZ) and obtaining the role for patch releases. (You will be pinged whenever there is a public or dev patch release.) 

3. By joining the [GitHub notifications Telegram channel](https://t.me/revanced_extended_repo). (You will be pinged whenever there is a public or dev patch release in any of inotia00's repositories.)

> [!IMPORTANT]
>
> **The version of your patched app is unrelated to whether it is up-to-date**. The suggested version may stay the same for months, while patches continue to be updated. Additionally, the suggested version is sometimes rolled back, so if your app version is newer than the [currently suggested version](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#2-general-info-for-patching-and-feature-setup) it means that your app is not up-to-date.



### **1b. How do I update a patched app?**

To update a patched app, you must [patch](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/guide-for-beginners.md) a new APK and then install the newly patched APK as an update to the currently installed app. Installing it as an update will preserve your settings configuration. 

> [!NOTE]
> If the new APK and the currently installed app were not signed using the same keystore file, the new APK would conflict with the current installation, which will need to be uninstalled before the new APK can be installed. (Read below for an explanation of the keystore.)
> 
> In the case where you need to uninstall the currently installed app, remember to export your settings configuration so you can easily reconfigure the new app. (Read below to learn how to export and import your settings configuration.)



### **1c. What is the keystore?**

The keystore is a file that the RVX Manager (and any other ReVanced patcher) uses to sign a patched APK. If you have a patched app installed and want to update it, you'll need the updated APK to be signed with the same keystore. Otherwise, you'll need to uninstall your currently installed APK before installing the updated version.

If you uninstall or clear the app data of the RVX Manager the keystore file will be deleted. So be sure to export/backup the keystore before uninstalling or clearing the data of the Manager. You can export and import the keystore file from the RVX Manager settings.



### **1d. Exporting / Importing Settings for YouTube and YT Music**

You can export and import the RVX settings configuration from/to a YouTube RVX or YT Music RVX.

To export the settings, open the YouTube RVX / YT Music RVX app you want to export the settings from. Navigate to Settings > RVX > Miscellaneous > Import / Export settings. Either export as a `.txt` file or copy the text directly and save it to your clipboard until you are ready to import it.

To import the settings, open the YouTube RVX / YT Music RVX app you want to import the settings into. Navigate to the "Import / Export settings" option using the path above, and import the `.txt` file or replace the text with the text you copied.

The non-RVX settings will still need to be configured, as well as any new ReVanced Extended settings.




# **2. General Info for Patching and Feature Setup**

### **2a. Which APK should I use for patching?**

Open the [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest) and navigate to Patcher > Select an application. The suggested version will be displayed for each app, as shown [here](https://imgur.com/a/TLcC2ZG). 

> [!TIP]
> To see all of the supported versions, you can read the JSON format [here](https://github.com/inotia00/revanced-patches?tab=readme-ov-file#-json-format).

Tap on the suggested version in the RVX Manager to open a search in your browser for the suggested APK (with an architecture supported by your device). Find and open the result from apkmirror.com with the suggested version. 

YouTube / Reddit (≤ v2024.29.0):
> If the apkmirror.com search result isn't for the `nodpi` variant of the APK, make sure to download the `nodpi` variant, as shown [here](https://imgur.com/a/XE6yF80).

YT Music:
> If the apkmirror.com search result isn't for a specific architecture, you will likely see [2-4 variants](https://i.imgur.com/KRmvhWh.png) of the APK, each for a different CPU architecture. You can find the supported architecture(s) of your device at the bottom of the RVX Manager settings. (If you plan to install the patched APK on another device, download the variant that matches the architecture of that device. You can search online to see which architecture(s) the device supports, but 99% of the time it will be arm64-v8a or armeabi-v7a.)



### **2b. Open Links By Default**

Follow these steps so that when you open a YouTube / YT Music / Reddit link it will open in the ReVanced Extended app instead of the official app.

> [!IMPORTANT]
> If you are using MIUI, you may need to use [Hidden Settings for MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets). After installing it, open it and tap "Manage applications". Then, continue with the steps below.

1. Go to the App info of the **unpatched** YouTube / YT Music / Reddit app and tap on "Set as default" / "Open by default" > Open supported links, **Off**.
   
> Alternatively, uninstall or disable the unpatched YouTube / YT Music / Reddit app. 

2. Open the App info of the **patched** YouTube / YT Music / Reddit app and tap on "Set as default" / "Open by default" > Open supported links, **On**.

3. Return to the previous page. Tap "Supported web addresses", and turn them all **On**.



### **2c. Downloader Setup**

The download feature in YouTube RVX / YT Music RVX is separate from the built-in download button, which is reserved for YouTube Premium members.

YouTube:
> You need to include the `Overlay buttons` patch.
>
> The download button can be enabled by going into Settings > RVX > Player > Player buttons > Show external download button, **On**. The download button will appear beside the fullscreen button in the video player.

YT Music:
> You need to include the `Hide action bar components` patch.
>
> To enable downloading, open the app and navigate to Settings > RVX > Action Bar > Override download action button, **On**. Now when you press the [Download button **in the player**](https://imgur.com/a/phjYvbe) it will open the downloader.

The default downloader is [YTDLnis](https://github.com/deniscerri/ytdlnis/releases/latest), which must be installed on the device. To change it, navigate to the downloader settings (using the path above) and open the "External downloader package name" setting. Select the downloader you want to use from the list or enter the package name of the downloader, press "OK" and install it if prompted. You can check out [this post](https://www.reddit.com/r/revancedapp/comments/xft8vq) for the download links and info on several other downloaders you can use. 




# **3. YT Music Setup**

### **3a.Android Auto Setup**

Here's how to set it up:

1. You need to include the `Certificate spoof` patch.

2. Once you have it installed with that patch, go to the Android Auto settings on your device.

3. Scroll down to "Version and permission info".

4. Tap on it 10 times to enter developer mode and then tap "OK" on the popup.

5. Tap the 3 dots in the upper-right corner of your screen and open the Developer settings.

6. Scroll down and enable Unknown sources.
