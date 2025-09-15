There are some notable updates regarding spoofing for playback in YouTube and YT Music.

# YouTube

In the recent patch release (v5.11.1), the following changes have been made:

- The `Android TV`, `iOS TV`, and `Android VR (Auth)` clients have been removed. See [this bug report](https://github.com/inotia00/ReVanced_Extended/issues/3166) for more information.

- The `Android Studio` and `visionOS` clients have been added.

See the [v5.11.1 release notes](https://github.com/inotia00/revanced-patches/releases/tag/v5.11.1) for the full list of changes.


### What does this mean for me?

If you face playback issues in YouTube RVX, you should switch to using the `TV Simply` JavaScript client. Ideally this is done while using the latest patches, but it can also be done with patches newer than v5.9.1 patches.

To use the `TV Simply` JavaScript client, open YouTube RVX and navigate to Settings > RVX > Miscellaneous > Spoof streaming data. Enable each of these settings in the following order. Restart the app each time you are prompted to:

1. Enable 'Spoof streaming data' (if disabled).
2. Enable 'Use JavaScript client' (and read the popup when enabling it).
3. Set the 'Default client' to `TV Simply`.
4. Enable 'Always show reload video button'. ('Show reload button' also needs to be enabled.)

Now if a video is taking a while to start or playback issues occur, simply press the 'Reload video button' in the video player.


### Why is the TV Simply client recommended?

`TV Simply` is recommended because it allows the 'Audio track' and 'Stable volume' options to be shown in the player flyout menu.

With the v5.11.1 patches, the 'Audio track' option does not appear in the player flyout menu when using the `Android Studio`, `Android VR (No Auth)`, `visionOS`, or `Mobile Web` clients. However, with the exception of `Android Studio`, the 'Disable forced auto audio track' setting is functional, as well as the 'Show audio track button' (which is a dedicated overlay button in the video player). Regarding the 'Stable volume' option, it is only supported by the `TV Simply`, `TV`, and `visionOS` clients.



# YT Music

In the recent patch release (v5.11.1), the following changes have been made:

- The `Fix playback` patch has been removed, and a new in-app option (associated with the `GmsCore support` patch) named 'Spoof streaming data' has been added to prevent playback issues. See [this bug report](https://github.com/inotia00/ReVanced_Extended/issues/3167) for more information.

See the [v5.11.1 release notes](https://github.com/inotia00/revanced-patches/releases/tag/v5.11.1) for the full list of changes.


### What does this mean for me?

If you face playback issues in YT Music RVX, update the app. The 'Spoof streaming data' option will be enabled by default, so playback issues should not occur.

Note: Users with YT Premium or an intact GmsCore/microG installation from before March 2024 need to disable the 'Spoof streaming data' option (by opening YT Music RVX and navigating to Settings > RVX > Miscellaneous).



# How do I patch/update an RVX app?

To patch an app, refer to the [Beginner guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/guide-for-beginners.md) or the [documentation](https://github.com/inotia00/revanced-documentation#readme).

To update a patched app, you must patch a new APK and then install the newly patched APK as an update to the currently installed app. Installing it as an update will preserve your settings configuration.



# How do I know which patch version an RVX app is using?

For YouTube RVX, open the app and navigate to Settings > RVX > Miscellaneous > Patch information. The patch version is listed under "ReVanced Patches".

For YT Music RVX, open the app and navigate to Settings > RVX > Miscellaneous > App info. The patch version is listed under "ReVanced Patches".