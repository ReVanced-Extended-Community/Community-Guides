# **YT Music ReVanced Extended Troubleshooting**


> **For patching and installation troubleshooting, refer to the [general troubleshooting guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/general-troubleshooting.md).**


### **1. No internet connection / Home page not loading / Account sign-in issues**

Navigate to your device settings > Accounts > Manage accounts > Google ([blue icon](https://imgur.com/a/LXoLCV1)) > Remove account. You can sign in again if you want.

> If that doesn't work you can clear the app data of GmsCore (aka microG) or uninstall and reinstall [GmsCore](https://github.com/ReVanced/GmsCore/releases/latest).




### **2. The download feature isn't working**

To understand and set up the download feature, refer to section 2 of the [setup info guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#2-general-info-for-patching-and-feature-setup).




### **3. How do I get YT Music RVX on Android Auto?**


Refer to section 3 of the [setup guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#3-yt-music-setup).




### **4. Why can I only use the Radio feature?**

Google has made it so that Canadian users who do not have YT Premium can only use the Radio feature within YouTube Music. There was a workaround involving spoofing to an older version, but it has been [deprecated](https://github.com/inotia00/ReVanced_Extended/issues/2743). Currently, the only solutions are to use a VPN to a different country or purchase YT Premium.




### **5. Videos stop and buffer**

Make sure your YT Music RVX is [up-to-date](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#1-info-for-updating-revanced-extended) with the `Spoof player parameter` patch included. Then, open YT Music RVX and navigate to Settings > RVX > Miscellaneous > Spoof player parameter, **On**.

> If playback issues still occur, repatch (preferably with 7.16.53 or an earlier [supported version](https://github.com/inotia00/revanced-patches?tab=readme-ov-file#-json-format)) and include the `Spoof client` patch and **exclude** the `Spoof player parameter` patch. Then, open YT Music RVX and navigate to Settings > RVX > Miscellaneous > Spoof client, **On**. If issues still occur, try changing the "Default client". Note that each client has their own side-effects. If you continue to face playback issues refer to the workarounds outlined [here](https://github.com/inotia00/ReVanced_Extended/issues/2758).
