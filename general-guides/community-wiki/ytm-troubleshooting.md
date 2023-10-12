# **YT Music Extended Troubleshooting**



# **Issues Within YT Music ReVanced Extended**

(See below for patching and installation troubleshooting.)



### **1. The download feature isn't working**

Refer to step 4 of the [YTM guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-guide.md#downloader-setup) to understand and set up the download function in YTM Extended.




### **2. I'm having issues signing in to my Google account**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




### **3. No internet connection / The home page isn't loading**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




### **4. Why can I only use the Radio feature?**

Google has made it so that Canadian users who do not have YT Premium can only use the Radio feature within YouTube Music.

Refer to step 4 of the [YTM guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-guide.md#spoof-app-version-setup-for-canadian-users) to solve this.




### **5. How do I get YT Music ReVanced Extended on Android Auto?**

Refer to step 4 of the [YTM guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-guide.md#android-auto-setup).







# **Issues With Patching & Installation**



### **6. My device is not supported**

You'll need to patch on a different Android device or on PC.

When patching on a different device or PC be sure to patch the APK variant that was built for the architecture of the device you plan to **install** the patched APK on. Refer to step 1 in the [YTM guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-guide.md#1-downloading-rvx-manager-yt-music-apk--vanced-microg) for info on downloading an APK for a specific architecture.

If you patch with the RVX Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the save icon when patching is completed as shown in [this image](https://imgur.com/a/FKD0okE). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in [inotia00's documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation).




### **7. Nothing happens when I select the YT Music APK from storage**

Make sure you are using the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest). If you already are using the correct version, continue with the following steps:

**a)** Uninstall the vanilla YT Music app. Install the YT Music APK that you downloaded while following step 1 in the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-guide.md#1-downloading-rvx-manager-yt-music-apk--vanced-microg).

**b)** Open the RVX Manager > Patcher > Select an application > **YT Music**.

Continue from the middle of step 2 in the [YT guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-guide.md#2-patching-the-apk).




### **8. Manager isn't loading patches / "No patches found for the selected app"**

**a)** Make sure the RVX Manager is the [latest available version](https://github.com/inotia00/revanced-manager/releases/latest). 

**b)** Disable any VPNs or ad-blockers and restart the RVX Manager.




### **9. Patcher is aborting / failing to apply patches**

**a)** Make sure you are using the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

**b)** Make sure you are using the suggested YT Music version given in step 1 of the [YTM guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-guide.md#1-downloading-rvx-manager-yt-music-apk--vanced-microg).

**c)** If your device's language was set to a language that reads right-to-left when the failure occurred then set your device's language to English or any language that reads left-to-right. Then fully close the Manager, and try again.

* If it still doesn't work you can try searching the subreddit for your error. Alternatively, you can patch on a different device or use a different patching method.

If you patch on a different device or use a different patching method be sure to patch the APK variant that was built for the architecture of the device you plan to **install** the patched APK on. Refer to step 1 in the [YTM guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-guide.md#1-downloading-rvx-manager-yt-music-apk--vanced-microg) for info on downloading an APK for a specific architecture.

If you patch with the RVX Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the save icon when patching is completed as shown in [this image](https://imgur.com/a/FKD0okE). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in in [inotia00's documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation).




### **10. Manager is stuck on "Installing..."**

Export the patched APK by tapping the save icon as shown in [this image](https://imgur.com/a/FKD0okE). Save it, and then install the exported APK from your file manager. You will probably get an error while installing. Refer to the entries below for instructions for various installation errors.




### **11. "App not installed."**

**a)** If there was a Google Play Protect pop-up when trying to install it then you must press **"More details"** and then tap the **"Install anyway"** button. If you press the "Got it" button it will not install. [Here](https://imgur.com/a/Ck8nfhn) is an image demonstrating this.

**b)** Ensure that you have ample available storage on your device.

**c)** Uninstall the YT Music Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or private folder that your device features.

**d)** If the error message was **"App not installed as app isn't compatible with your device."** refer to troubleshooting issue **#12**.




### **12. "App not installed as package conflicts with an existing package."**

**a)** Uninstall the YT Music Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or private folder that your device features.

**b)** Patch again and include the `MicroG Support` patch.




### **13. "App not installed as package appears to be invalid."**

This error most often means that you are trying to install an app that is an older version than the already installed version. Android doesn't allow app downgrading. In the context of installing YTM Extended, here are some possible scenarios and solutions:

**a)** You are installing the unpatched YT Music APK that you downloaded from APKMirror.com. It is not necessary to install it. Refer to step 2 in the [YTM guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-guide.md#2-patching-the-apk) for info on selecting the YTM APK from storage.

**b)** Your patched YTM APK does not have the `MicroG Support` patch applied to it. Patch again and include the `MicroG Support` patch.

**c)** You are installing a patched YTM Extended APK that is an older version than the YTM Extended that is currently installed. Uninstall YTM Extended before installing the older version.

**d)** You are installing an older version of Vanced MicroG than the one you already have installed. To uninstall the one you currently have installed, open your device Settings > Apps > Vanced MicroG > Uninstall.




### **14. "App not installed as app isn't compatible with your device."**

The YT Music you patched APK doesn't match your device's architecture. Refer to step 1 in the [YTM guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/general-guides/community-wiki/ytm-guide.md#1-downloading-rvx-manager-yt-music-apk--vanced-microg) for info on downloading the correct APK/app.




### **13. App crashes on startup**

3 common causes:

**a)** You do not have Vanced MicroG installed. Download and install [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest). Or you can use an updated forked version from [inotia00's GitHub](https://github.com/inotia00/VancedMicroG/releases/latest).

**b)** There was a failure or error while it was patching and you installed the broken APK. Refer to troubleshooting issue **#8** if this occurred.

**c)** The email you are signing in with has parental control restrictions.
