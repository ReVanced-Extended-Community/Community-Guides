- Note: This announcement has been edited after the v5.12.1 patches have been released.

There are some notable updates regarding spoofing for playback in YouTube and YT Music.

# YouTube

In the recent patch releases (v5.11.1 and v5.12.1), the following relevant changes have been made:

- The `Android TV` and `iOS TV` clients have been removed.

- The `Android Studio`, `ipadOS`, and `visionOS` clients have been added.

See the [v5.11.1](https://github.com/inotia00/revanced-patches/releases/tag/v5.11.1) and [v5.12.1](https://github.com/inotia00/revanced-patches/releases/tag/v5.12.1) release notes for the full list of changes.


### What does this mean for me?

If you face playback issues in YouTube RVX, you should switch to using the `TV` JavaScript client. Ideally this is done while using the latest patches, but it should still work as long as you are using patches v5.9.1 or newer.

To use the `TV` JavaScript client, open YouTube RVX and navigate to Settings > RVX > Miscellaneous > Spoof streaming data. Enable each of these settings in the following order. Restart the app each time you are prompted to:

1. Enable 'Spoof streaming data' (if disabled).
2. Enable 'Use JavaScript client' (and read the popup when enabling it).
3. Set the 'Default client' to `TV`.
4. Enable 'Always show reload video button'. ('Show reload button' also needs to be enabled.)

Now if a video is taking a while to start or playback issues occur, simply press the 'Reload video button' in the video player.


### Why is the TV client recommended?

`TV` is recommended because it allows the 'Audio track' and 'Stable volume' options to be shown in the player flyout menu and it is available in all regions. The `TV Simply (No PoToken)` client is similar, but may not be as reliable as the `TV` client.

> More details:
>
> The 'Audio track' option in the player flyout menu is only shown when using the `TV`, `TV Simply (No PoToken)`, and `iPadOS` clients. But the 'Show audio track button' and 'Disable forced auto audio track' settings are still functional when using the `Android VR (No Auth)`, `visionOS`, and `Mobile Web` clients. ('Show audio track button' creates a dedicated overlay button in the video player).
> 
> The 'Stable volume' option in the player flyout menu, it is only supported by the `TV`, `TV Simply (No PoToken)`, `ipadOS`, and `visionOS` clients. 
>
> Additionally, in some regions (such as India,) only the `TV`, `TV Simply (No PoToken)`, `Android VR (Auth)`, and `Android Studio` clients are available.



# YT Music

In the recent patch release (v5.11.1), the following relevant changes have been made:

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
