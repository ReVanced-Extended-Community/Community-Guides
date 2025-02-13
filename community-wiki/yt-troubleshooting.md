# **YouTube ReVanced Extended Troubleshooting**


> **For patching and installation troubleshooting, refer to the [general troubleshooting guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/general-troubleshooting.md).**


### **1. No internet connection / Home page not loading / Account sign-in issues**

Navigate to your device settings > Accounts > Manage accounts > Google ([blue icon](https://imgur.com/a/LXoLCV1)) > Remove account. You can sign in again if you want.

> If that doesn't work you can uninstall GmsCore and then reinstall [GmsCore](https://github.com/ReVanced/GmsCore/releases/latest).




### **2. The download feature isn't working**

To understand and set up the download feature, refer to section 2 of the [setup info guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#2-general-info-for-patching-and-feature-setup).




### **3. Videos stop and buffer infinitely**

Make sure your YT ReVanced Extended is [up-to-date](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#1-info-for-updating-revanced-extended) with the `Spoof streaming data` patch included. Then, open YT ReVanced Extended and navigate to Settings > RVX > Miscellaneous > Spoof streaming data > Spoof streaming data, **On**. (If issues still occur, try changing the "Default client".)

> Note that there are several clients you can spoof to, and each has their own side-effects.



### **4. YouTube Shorts are/aren't hidden**

**To hide/unhide Shorts in feeds:**

You need to include the `Shorts components` patch. Then, open YT ReVanced Extended and navigate to Settings > RVX > Shorts > Hide Shorts shelves, **On/Off**.

**To hide/unhide the Shorts button:**

You need to include the `Navigation bar components` patch. Then, open YT ReVanced Extended and navigate to Settings > RVX > General > Navigation buttons > Hide Shorts button, **On/Off**.




### **5. The player UI doesn't go away**

You may have set it to permanently show in Settings > Accessibility. Alternatively, this issue may be a random bug, and the only fix is to restart the app.




### **6. SponsorBlock is not working**

This likely means that the SponsorBlock servers are down. You can check the server status [here](https://status.sponsor.ajay.app/).




### **7. Watch history isn't being saved**

Make sure your YT ReVanced Extended is [up-to-date](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#1-info-for-updating-revanced-extended) with the `Watch history` patch included. Then, open YT ReVanced Extended and navigate to Settings > RVX > Miscellaneous > Watch history. At the bottom, the reasons for why watch history may not work will be listed. Here are the possible listed reasons and their respective solutions:

- **"Watch history may not work with a brand account."**: [Update](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#1-info-for-updating-revanced-extended) the app.

- **"Watch history may not work due to DNS or VPN."**: Change the `Watch history type` to "Replace domain". Alternatively, whitelist `s.youtube.com` in your ad-blocker, DNS-blocker, firewall, etc. 

- **"Watch history is blocked"**: Change the `Watch history type` to one other than "Block watch history".
