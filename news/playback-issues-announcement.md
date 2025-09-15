There are some notable updates regarding spoofing for playback in YouTube and YT Music.

# YouTube

In the upcoming patch release (v5.11.1), the following changes will be made:

- The `Android TV`, `iOS TV`, and `Android VR (Auth)` clients will be removed. See [this bug report](https://github.com/inotia00/ReVanced_Extended/issues/3166) for more information.

- The `Android Studio` and `visionOS` clients will be added.


### What does this mean for me?

If you face playback issues in YouTube RVX, you should switch to using the `TV Simply` JavaScript client. This is true for those using the v5.9.1 patches or newer, including those in the future that use the upcoming patches.

To use the `TV Simply` JavaScript client, open YouTube RVX and navigate to Settings > RVX > Miscellaneous > Spoof streaming data. Enable each of these settings in the following order. Restart the app each time you are prompted to:

1. Enable 'Spoof streaming data' (if disabled).
2. Enable 'Use JavaScript client' (and read the popup when enabling it).
3. Set the 'Default client' to `TV Simply`.
4. Enable 'Always show reload video button'. ('Show reload button' also needs to be enabled.)

Now if a video is taking a while to start or playback issues occur, simply press the 'Reload video button' in the video player.


### Why is the TV Simply client recommended?

`TV Simply` is recommended because it allows the 'Audio track' and 'Stable volume' options to be shown in the player flyout menu.

In the upcoming patch release, the 'Audio track' option will not appear in the player flyout menu when using the `Android Studio`, `Android VR (No Auth)`, `visionOS`, or `Mobile Web` clients. However, with the exception of `Android Studio`, the 'Disable forced auto audio track' setting will be functional, as well as the 'Show audio track button' (which is a dedicated overlay button in the video player). Regarding the 'Stable volume' option, it will only be supported by the `TV Simply`, `TV`, and `visionOS` clients.



# YT Music

In the upcoming patch release (v5.11.1), the following changes will be made:

- The `Fix playback` patch will be removed, and a new in-app option (associated with the `GmsCore support` patch) named 'Spoof streaming data' will be added to prevent playback issues. See [this bug report](https://github.com/inotia00/ReVanced_Extended/issues/3167) for more information.


### What does this mean for me?

Once the v5.11.1 patches release, if you update your YT Music RVX, you should not have any playback issues, since the 'Spoof streaming data' option will be enabled by default.

Note: Users with YT Premium or an intact GmsCore/microG installation from before March 2024 will need to disable the 'Spoof streaming data' option.


### How do I resolve playback issues right now?

If you face playback issues in YT Music RVX, patch YT Music with the v5.10.1 patches and include the `Fix playback` patch. After the app is patched and installed, open it and navigate to Settings > RVX > Miscellaneous. Make sure that the 'Spoof client' setting is OFF and that the 'Spoof video streams' setting is ON. 

Additionally, depending on your network, you may need to set a Private DNS provider in your device settings. Follow the instructions laid out on [this page](https://developers.google.com/speed/public-dns/docs/using?hl=en#android) to set up Private DNS. (This is only needed temporarily until you update to the v5.11.1 patches and use the 'Spoof streaming data' option.)



# How do I patch/update an RVX app?

To patch an app, refer to the [Beginner guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/guide-for-beginners.md) or the [documentation](https://github.com/inotia00/revanced-documentation#readme).

To update a patched app, you must patch a new APK and then install the newly patched APK as an update to the currently installed app. Installing it as an update will preserve your settings configuration.



# How do I know which patch version an RVX app is using?

For YouTube RVX, open the app and navigate to Settings > RVX > Miscellaneous > Patch information. The patch version is listed under "ReVanced Patches".

For YT Music RVX, open the app and navigate to Settings > RVX > Miscellaneous > App info. The patch version is listed under "ReVanced Patches".