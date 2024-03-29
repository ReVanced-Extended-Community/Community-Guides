# **YT ReVanced Extended Troubleshooting**



# **Issues Within YT ReVanced Extended**

> See below for patching and installation troubleshooting.



### **1. No internet connection / The home page isn't loading**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

> If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




### **2. I'm having issues signing in to my Google account**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

> If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




### **3. The download feature isn't working**

Refer to step 4 of the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-guide.md#downloader-setup) to understand and set up the download function in YT ReVanced Extended.




### **4. Videos stop and buffer infinitely**

Make sure your YT ReVanced Extended is up-to-date.

If buffering persists, open YT ReVanced Extended and tap the profile picture > Settings > ReVanced Extended > Miscellaneous > Spoof player parameter, **On**. Restart the app. 




### **5. YouTube Shorts are/aren't hidden**

**To hide/unhide Shorts in feeds:**

Go to Settings > ReVanced Extended > Shorts > Hide shorts shelf, **On/Off**.

**To hide/unhide the Shorts button:**

Go to Settings > ReVanced Extended > Navigation > Hide shorts button, **On/Off**.




### **6. The player UI doesn't go away**

You may have set it to permanently show in Settings > Accessibility. Otherwise, this issue occurs randomly, and the only fix is to restart the app.




### **7. SponsorBlock is not working**

This likely means that the SponsorBlock servers are down. You can check the server status [here](https://status.sponsor.ajay.app/).




### **8. Watch history isn't being saved**

This is one of two issues:

**a)** The player parameter spoof is causing this issue (but nevertheless, you should not disable it unless you have YT Premium). 

There is a partial workaround:

First, go to Settings > General > Playback in feeds, **On**. Next, go to Settings > ReVanced Extended > Miscellaneous > Spoof player parameter in feed, **On**.

Now when you want to watch a video and have it added to your history, allow it to play in feed for 10-15 seconds before clicking into the video. However, YouTube will only consider the part of the video watched in feed as watched.

**b)** You must whitelist `s.youtube.com` in your ad-blocker, DNS-blocker, firewall, etc.








# **Issues With Patching & Installation**


### **9. My device is not supported**

You'll need to patch on a different Android device or on PC.

> If you patch with the RVX Manager on a different device you'll need to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the save icon when patching is completed as shown in [this image](https://imgur.com/a/FKD0okE). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in [inotia00's documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation).




### **10. "Feature not implemented: This application is a split APK and cannot be selected."**

On non-root devices you must use a full (non-bundle) APK when patching. Refer to steps 1 and 2 in the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-guide.md#1-downloading-rvx-manager-yt-apk--vanced-microg) to download and select the full APK from storage.




### **11. Nothing happens when I select the YT APK from storage**

Make sure you are using the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest). If you already are using the correct version, continue with the following steps:

**a)** Uninstall the stock YouTube app. If your device doesn't allow you to uninstall it then go to the App info of stock YouTube > Options menu (as shown in [this image](https://imgur.com/a/0js3AZR)) > Uninstall updates.

**b)**  Install the YouTube APK that you downloaded while following step 1 in the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-guide.md#1-downloading-rvx-manager-yt-apk--vanced-microg).

**c)** Open the RVX Manager > Patcher > Select an application > **YouTube**.

Continue from the middle of step 2 in the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-guide.md#2-patching-the-apk).




### **12. Manager isn't loading patches or applications**

**a)** Make sure the RVX Manager is the [latest available version](https://github.com/inotia00/revanced-manager/releases/latest). 

**b)** Disable any VPNs or ad-blockers and restart the RVX Manager.




### **13. "Error: Patch is not supported for this app version."**

Download an APK of the recommended/suggested version and patch that from storage. Refer to steps 1 and 2 in the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-guide.md#1-downloading-rvx-manager-yt-apk--vanced-microg).




### **14. Patcher is Aborting / failing to apply patches**

**a)** Make sure you are using the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

**b)** Make sure you selected the suggested APK from storage. Refer to steps 1 and 2 in the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-guide.md#1-downloading-rvx-manager-yt-apk--vanced-microg).

**c)** If your device's language was set to a language that reads right-to-left when the failure occurred then set your device's language to English or any language that reads left-to-right. Then fully close the Manager, and try again.

* If it still doesn't work you can try searching the [subreddit](https://www.reddit.com/r/revancedextended/) or [Telegram group](https://t.me/revanced_extended_chat) for your error. Alternatively, you can patch on a different device or use a different patching method.

> If you patch with the RVX Manager on a different device you'll need to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the save icon when patching is completed as shown in [this image](https://imgur.com/a/FKD0okE). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in [inotia00's documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation).




### **15. Manager is stuck on "Installing..."**

Export the patched APK by tapping the save icon as shown in [this image](https://imgur.com/a/FKD0okE). Save it, and then install the exported APK from your file manager. You will probably get an error while installing. Refer to the entries below for instructions for various installation errors.




### **16. "App not installed."**

**a)** If there was a Google Play Protect pop-up when trying to install it then you must press **"More details"** and then tap the **"Install anyway"** button. If you press the "Got it" button it will not install. [Here](https://imgur.com/a/Ck8nfhn) is an image demonstrating this.

**b)** Ensure that you have enough free storage. Depending on the device, it may require more than 1.5 gigabytes to install without issue.

**c)** Uninstall the YT ReVanced Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or private folder that your device features.

> You can backup your settings before uninstalling the currently installed YT ReVanced Extended. Refer to the "Exporting / Importing The Settings" section in the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-guide.md#exporting--importing-the-settings).




### **17. "App not installed as package conflicts with an existing package."**

**a)** Uninstall the YT ReVanced Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or private folder that your device features.

> You can backup your settings before uninstalling the currently installed YT ReVanced Extended. Refer to the "Exporting / Importing The Settings" section in the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-guide.md#exporting--importing-the-settings).

**b)** Patch again and include the `MicroG Support` patch.




### **18. "App not installed as package appears to be invalid."**

This error most often means that you are trying to install an app that is an older version than the already installed version. Android doesn't allow app downgrading. In the context of installing YT ReVanced Extended, here are some possible scenarios and solutions:

**a)** You are installing the unpatched YouTube APK that you downloaded from APKMirror.com. It is not necessary to install it. Refer to step 2 in the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-guide.md#2-patching-the-apk) for info on selecting the YT APK from storage.

**b)** Your patched YT APK does not have the `MicroG Support` patch applied to it. Patch again and include the `MicroG Support` patch.

**c)** You are installing a patched YT ReVanced Extended APK that is an older version than the YT ReVanced Extended that is currently installed. Uninstall YT ReVanced Extended before installing the older version. 

> You can backup your settings before uninstalling the currently installed YT ReVanced Extended. Refer to the "Exporting / Importing The Settings" section in the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/yt-guide.md#exporting--importing-the-settings).

**d)** You are installing an older version of Vanced MicroG than the one you already have installed. To uninstall the one you currently have installed, open your device Settings > Apps > Vanced MicroG > Uninstall.




### **19. App crashes on startup**

What most likely happened was there was a failure or error while it was patching and you installed the broken APK. Refer to troubleshooting issue **#14** if this occured.