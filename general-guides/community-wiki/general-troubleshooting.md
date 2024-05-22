# **General Troubleshooting**


### **1. My device is not supported**

You'll need to patch on a different Android device or on PC.

YT Music:
> Note that when patching YT Music on a different device or PC, you'll need to patch the APK variant that was built for the architecture of the device you plan to **install** the patched APK on. 

> If you patch with the RVX Manager on a different device you'll need to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the save icon when patching is completed as shown in [this image](https://imgur.com/a/FKD0okE). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in [inotia00's documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation).




### **2. "Feature not implemented: This application is a split APK and cannot be selected."**

On non-root devices you must use a full (non-bundle) APK when patching. Refer to steps 1 and 2 in the [beginners guide](https://www.reddit.com/r/revancedextended/comments/12vxggr/revanced_extended_guide_for_beginners/) to download and select the full APK from storage.




### **3. Nothing happens when I select the APK from storage**

Make sure you are using the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest). If you already are using the correct version, continue with the following steps:

**1)** Uninstall the unpatched YouTube / YT Music / Reddit from your device. 

> If you cannot uninstall it, go to the App info of the app > Options menu (as shown in [this image](https://imgur.com/a/0js3AZR)) > Uninstall updates.

**2)** Install the APK that you downloaded from APKMirror.

**3)** Open the RVX Manager > Patcher > Select an application, and select the app from the app list.

Continue from the middle of step 2 in the [beginners guide](https://www.reddit.com/r/revancedextended/comments/12vxggr/revanced_extended_guide_for_beginners/).




### **4. The manager isn't loading patches or applications**

**a)** Make sure you are using the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

**b)** Disable any ad-blockers or VPNs and restart the RVX Manager.




### **5. Patcher is aborting / failing to apply patches**

**a)** Make sure you are using the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

**b)** Make sure you are using the suggested APK version given in step 1 of the [beginners guide](https://www.reddit.com/r/revancedextended/comments/12vxggr/revanced_extended_guide_for_beginners/).

**c)** If your device's language was set to a language that reads right-to-left when the failure occurred then set your device's language to English or any language that reads left-to-right. Then fully close the Manager, and try again.

* If it still doesn't work you can try searching and asking for support in the [subreddit](https://www.reddit.com/r/revancedextended/) or [Telegram group](https://t.me/revanced_extended_chat). Alternatively, you can patch on a different device or use a different patching method.

* If you want to patch on a different device refer to the info in issue **#1** above.




### **6. Installation errors**

If you encounter any installation error when installing the patched app, follow these steps until the issue is resolved:

1. **Google Play Protect Warning:**
If you see a Google Play Protect pop-up, tap **"More details"** and then **"Install anyway"**. Do not tap "Got it", as this will cancel the installation. [View Image](https://imgur.com/a/Ck8nfhn).

2. **Ensure Sufficient Storage:**
Make sure your device has enough storage space.

3. **Uninstall Existing Versions:**
Remove any existing installation of the app you are trying to install, even if it is in an alternate user profile or private folder.

4. **Check The APK**
If you are trying to install the unpatched APK from APKMirror.com, note that it is simpler to avoid installing it before patching. Instead, follow step 2 in the [beginners guide](https://www.reddit.com/r/revancedextended/comments/12vxggr/revanced_extended_guide_for_beginners) to select and patch the APK without installing it beforehand.

Youtube / YT Music:
> 5. **Patch with `GmsCore Support`:**
> Ensure that the `GmsCore Support` patch is applied when patching the APK.

YT Music:
> 6. **Check APK Compatibility:**
> Ensure that the APK you patched is built for your device's architecture. Refer to TODO for information on downloading the correct APK.





### **7. App crashes on startup**

If the app is crashing on startup, there are 3 common causes of it:

YouTube and YT Music:
> **a)** You do not have GmsCore installed. Download and install [GmsCore](https://github.com/ReVanced/GmsCore/releases/latest).

**b)** There was a failure or error while it was patching and you installed the broken APK. Refer to troubleshooting issue **#6** if this occurred.

