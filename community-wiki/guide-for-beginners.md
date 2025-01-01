**Last updated on Jan 1st, 2025.**



### [For more resources like this, check the complete subreddit wiki.](https://reddit.com/r/revancedextended/w/index)

___

**[Coming from ReVanced? Use the RVX Manager created specifically for ReVanced Extended patches!](https://github.com/inotia00/revanced-manager/releases/latest)**

___





### **Things To Know Before You Begin**


* Read the [Frequently Asked Questions](https://www.reddit.com/r/revancedextended/wiki/faq/).


* This guide will use the RVX Manager patching method to do a non-root installation. Check the [documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation) for info on the other patching methods.


* Check the [troubleshooting section](https://www.reddit.com/r/revancedextended/wiki/troubleshooting/) if you get stuck during this guide.





# **1. Requirements:**


* Your device must be running Android 8.0 or newer.


* Your device's architecture must be arm64-v8a, armeabi-v7a, or x86-64. (You will find out if it is in a moment) 





#### **Downloading GmsCore, APK to patch, & the RVX Manager**


Download and install the **RVX Manager** APK from [here](https://github.com/inotia00/revanced-manager/releases/latest). It is inotia00's fork of the official ReVanced Manager.

> If you get an error saying *"App not installed as app isn't compatible with your device."* it means that your device is not supported by the RVX Manager. Refer to issue 1 in the [general troubleshooting guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/general-troubleshooting.md) for instructions.




Download, but do **not** install the APK you want to patch from apkmirror.com:

**YouTube**: [`v19.16.39` (`nodpi`) APK](https://www.apkmirror.com/apk/google-inc/youtube/youtube-19-16-39-release/youtube-19-16-39-android-apk-download/) *(If you currently have a patched YT ReVanced Extended installed that is a version higher than 19.16.39, see the [pinned comment below](https://www.reddit.com/r/revancedextended/comments/12vxggr/comment/le633vz/).)*

**YT Music**: [`v7.16.53` APK](https://www.apkmirror.com/apk/google-inc/youtube-music/youtube-music-7-16-53-release/#downloads). There will be [2-4 variants](https://i.imgur.com/KRmvhWh.png) of the APK, each for a different architecture. To choose the correct APK, open the RVX Manager and go to the settings. At the bottom of the settings it will list the supported architecture(s) of your device.

**Reddit**: [`v2024.17.0` (`nodpi`) APK](https://www.apkmirror.com/apk/redditinc/reddit/reddit-2024-17-0-release/reddit-2024-17-0-2-android-apk-download/)



> If you want to learn more how to find the correct APK without relying on this guide, check section 2 of the [setup info guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#2-general-info-for-patching-and-feature-setup).



If patching YouTube or YT Music:
> **GmsCore** is needed for patched YouTube and YT Music to run. If you do not have GmsCore installed, download and install [ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases/latest). (If you are using a Hauwei device, be sure to select the special download for your device.)





# **2. Patching**


Open the RVX Manager. Your device may open a settings page for choosing which apps of yours have permission to install unknown apps. Find the RVX Manager and give it the permission.


Then in the Manager, go to Patcher > Select an application.


Press "**Storage**" [as shown in this image](https://imgur.com/a/vx64z3S).


Select the APK file that you just downloaded from APKMirror from your downloads folder.


The application will be selected and if it is your first time patching the Default list of patches will be selected. If you want to make sure the Default patches are selected, tap on the selected patches and press the Default button at the top of the patches selection menu.


If you don't want to use the Default selection you **must** at least include the `GmsCore Support` patch.



> [Check out this repository to see what the patches do!](https://github.com/ReVanced-Extended-Community/Patches-Documentation#patches-documentation) (work-in-progress)


When you are done selecting the patches press "**Done**" and then press "**Patch**".


Wait for the patching to be complete. It usually takes 2-5 minutes. If you leave the app it may cancel. Make sure no errors occur during this step.





# **3. Installing**


> When patching is finished you can save the APK as a file so that you have it for later in case you have trouble installing it or want to share it. To do this, tap save icon in the lower left corner of the screen as shown [here](https://imgur.com/a/FKD0okE).


Press "Install" and wait for it to finish installing. You may get a message saying that the installation was blocked because it is an unknown app. Tap "**More details**" and then "**Install anyway**" as shown [here](https://imgur.com/a/iLP2m7l).





#### **Optional - Additional Setup:**

There's some additional setup you can do to make the patched app even better! Things like opening YouTube links in the patched YouTube app, or setting up the download feature in YouTube RVX and YT Music RVX. Refer to section 2 and 3 of the [setup info guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#2-general-info-for-patching-and-feature-setup) for information on setting up this sorta stuff.



**You are done!**

___





# **More Info/Troubleshooting**


Check the [troubleshooting section](https://www.reddit.com/r/revancedextended/wiki/troubleshooting/) for help.


Check out [this site](https://kazimmt.github.io/#revanced-extended-features) to see what all of the ReVanced Extended settings do! (Note that it is a work-in-progress)
