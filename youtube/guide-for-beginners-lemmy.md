*Last updated on OCT/28/2023.*

### About this Guide:

* This guide is for patching YouTube.


* This guide is for non-root installs.


* This guide will use the RVX Manager patching method. Check the [documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation) for info on the other patching methods.

___

### **1. Requirements:**


* Your device must be running Android 8.0 or newer.


* Your device must use the arm64-v8a architecture.


##### **Downloading MicroG, YouTube APK, & the RVX Manager:**



**1.1** If you do not have Vanced MicroG installed, download and install [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest). Or you can use an updated forked version from [inotia00's GitHub](https://github.com/inotia00/VancedMicroG/releases/latest).



**1.2** Download, BUT DO NOT INSTALL the **YouTube** `v18.41.39` (`nodpi`) APK from APKMirror [here](https://www.apkmirror.com/apk/google-inc/youtube/youtube-18-41-39-release/youtube-18-41-39-2-android-apk-download/).



**1.3** Download and install the **RVX Manager** APK from [here](https://github.com/inotia00/revanced-manager/releases/latest). It is inotia00's fork of the official Manager made to be compatible with ReVanced Extended patches.



(*If you get an error saying* "App not installed as app isn't compatible with your device." *it means that your device is not supported by the RVX Manager.*)


### **2. Patching**



Open the RVX Manager. Your device may open a settings page for choosing which apps of yours have permission to install unknown apps. Find the RVX Manager and give it the permission.



Then in the Manager, go to Patcher > Select an application.



Press "**Storage**" [as shown in this image](https://imgur.com/a/vx64z3S).



Select the YouTube APK file that you just downloaded from APKMirror from your downloads folder.



The application will be selected and if it is your first time patching the Default list of patches will be selected. If you want to make sure the Default patches are selected, press the Default button at the top of the patches selection menu.


If you don't want to use the Default selection you **must** at least include the `MicroG Support` patch.



[Check out this repository to see what all the patches do! (still being updated)](https://github.com/ReVanced-Extended-Community/Patches-Documentation#patches-documentation)



When you are done selecting the patches press "**Done**" and then press "**Patch**".



Wait for the patching to be complete. It usually takes 2-5 minutes. Do not leave the app or it may cancel. Make sure no errors occur during this step.



### **3. Installing**



When patching is finished you can save the APK as a file so that you have it for later in case you have trouble installing it or want to share it. To do this, tap save icon in the lower left corner of the screen as shown [here](https://imgur.com/a/FKD0okE).



Press "Install" and wait for it to finish installing. You may get a message saying that the installation was blocked because it is an unknown app. Tap "**More details**" and then "**Install anyway**" as shown [here](https://imgur.com/a/iLP2m7l).

___

#### **Optional - Link Association:**



Follow these steps so that when you open a YouTube link it will open in the YT ReVanced Extended app instead of the official YouTube app:



(For MIUI users, use the [Hidden Settings For MIUI](https://play.google.com/store/apps/details?id=com.ceyhan.sets) app, and use its Manage Applications menu to do these steps.)



Go to the *App Info* of YT ReVanced Extended > Set as default > Open supported links, **On**. Then go back to the previous page. Tap "Supported web addresses" > turn them all **On**. You may also need to manually disable these settings for stock YouTube, or just disable/uninstall stock YouTube entirely. 



Alternatively, in YT ReVanced Extended there is a button to take you straight to the Default links settings. Tap the profile picture > Settings > ReVanced Extended > Miscellaneous > Open default app settings.

___

**You are done!**
