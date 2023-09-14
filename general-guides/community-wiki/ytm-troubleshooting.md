# **YT Music Extended Troubleshooting**



# **Issues Within YT Music ReVanced Extended**

(See below for patching and installation troubleshooting.)



#### **1. The download feature isn't working**

Refer to step 4 of the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_downloader_setup) to understand and set up the download function in YTM Extended.




#### **2. I'm having issues signing in to my Google account**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




#### **3. No internet connection / The home page isn't loading**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




#### **4. Why can I only use the Radio feature?**

Google has made it so that Canadian (and possibly other countries') users that do not have YT Premium can only use the Radio feature within YouTube Music.

Refer to step 4 of the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_spoof_app_version_setup_.28for_canadian_users.29) to solve this.




#### **5. How do I get YT Music ReVanced Extended on Android Auto?**

Refer to step 4 of the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_android_auto_setup).







# **Issues With Patching & Installation**



#### **6. My device is not supported**

You'll need to patch on a different Android device or on PC.

When patching on a different device or PC be sure to patch the APK variant that was built for the architecture of the device you plan to **install** the patched APK on. Refer to step 1 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_1._downloading_vanced_microg.2C_rvx_manager.2C_.26amp.3B_yt_music_apk) for info on downloading an APK for a specific architecture.

If you patch with the RVX Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the save icon when patching is completed as shown in [this image](https://imgur.com/a/FKD0okE). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in the [GitHub documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation).



#### **7. Patcher is aborting / failing to apply patches**

**a)** Make sure you are using the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

**b)** Make sure you are using the suggested YT Music version given in step 1 of the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_1._downloading_vanced_microg.2C_rvx_manager.2C_.26amp.3B_yt_music_apk).

**c)** If your device's language was set to a language that reads right-to-left when the failure occurred then set your device's language to English or any language that reads left-to-right. Then fully close the Manager, and try again.

* If it still doesn't work you can try searching the sub for your error. Alternatively, you can patch on a different device or use a different patching method.

If you patch on a different device or use a different patching method be sure to patch the APK variant that was built for the architecture of the device you plan to **install** the patched APK on. Refer to step 1 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_1._downloading_vanced_microg.2C_rvx_manager.2C_.26amp.3B_yt_music_apk) for info on downloading an APK for a specific architecture.

If you patch with the RVX Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the save icon when patching is completed as shown in [this image](https://imgur.com/a/FKD0okE). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in the [GitHub documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation).




#### **8. "Error: Non-root install is not possible with the current patches selection."**

Patch again and include the `MicroG Support` patch.




#### **9. "App not installed."**

**a)** If there was a Google Play Protect pop-up when trying to install it then you must press **"More details"** and then tap the **"Install anyway"** button. If you press the "Got it" button it will not install. [Here](https://imgur.com/a/Ck8nfhn) is an image demonstrating this.

**b)** Ensure that you have ample available storage on your device.

**c)** Uninstall the YT Music Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or private folder that your device features.

**d)** If the error message was **"App not installed as app isn't compatible with your device."** refer to troubleshooting issue **#12**.




#### **10. "App not installed as package conflicts with an existing package."**

**a)** Uninstall the YT Music Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or private folder that your device features.

**b)** It is possible your patched YTM APK that you are installing was exported from the RVX Manager but does not have the `MicroG Support` patch applied to it. You can verify if this is the case by doing the following:

Open the RVX Manager > Patcher > Select an application > Storage > Select the **patched** APK that you were trying to install.

Now check what it says the package name is near the top (in parenthesis). Make sure the package name starts with "app.rvx" like in [this image](https://imgur.com/a/AlYepUa). If it says something else, then you'll need to patch again and apply the `MicroG Support` patch this time.




#### **11. "App not installed as package appears to be invalid."**

This error most often means that you are trying to install an app that is an older version than the already installed version. Android doesn't allow app downgrading. In the context of installing YTM Extended, here are some possible scenarios and solutions:

**a)** You are installing the unpatched YT Music APK that you downloaded from APKMirror.com. It is not necessary to install it. Refer to step 2 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_2._patching_the_apk) for info on selecting the YTM APK from storage.

**b)** Your patched YTM APK that you are installing was exported from the RVX Manager but does not have the `MicroG Support` patch applied to it. You can verify if this is the case by doing the following:

Open the RVX Manager > Patcher > Select an application > Storage > Select the **patched** APK that you were trying to install.

Now check what it says the package name is near the top (in parenthesis). Make sure the package name starts with "app.rvx" like in [this image](https://imgur.com/a/AlYepUa). If it says something else, then you'll need to patch again and apply the `MicroG Support` patch this time.

**c)** You are installing a patched YTM Extended APK that is an older version than the YTM Extended that is currently installed. Uninstall YTM Extended before installing the older version.

**d)** You are installing an older version of Vanced MicroG than the one you already have installed. To uninstall the one you currently have installed, open your device Settings > Apps > Vanced MicroG > Uninstall.




#### **12. "App not installed as app isn't compatible with your device"**

The YT Music you patched APK doesn't match your device's architecture. Refer to step 1 in the [YTM guide](https://www.reddit.com/r/revancedextended/wiki/ytm-guide/#wiki_1._downloading_vanced_microg.2C_rvx_manager.2C_.26amp.3B_yt_music_apk) for info on downloading the correct APK/app.




#### **13. App crashes on startup**

3 common causes:

**a)** You do not have Vanced MicroG installed. Download and install [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest). Or you can use an updated forked version from [inotia00's GitHub](https://github.com/inotia00/VancedMicroG/releases/latest).

**b)** There was a failure or error while it was patching and you installed the broken APK. Refer to troubleshooting issue **#7** if this occured.

**c)** The email you are signing in with has parental control restrictions.