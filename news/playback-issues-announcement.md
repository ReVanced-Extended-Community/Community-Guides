# YouTube

Over the past few patch releases there were notable changes regarding spoofing for playback in YouTube.

### What does this mean for me?

If you face playback issues in YouTube RVX, you should switch to using the `TV Simply` JavaScript client. Ideally this is done while using the latest patches, but it should still work as long as you are using patches v5.13.1 or newer.

To use the `TV Simply` JavaScript client, open YouTube RVX and navigate to Settings > RVX > Miscellaneous > Spoof streaming data. Enable each of these settings in the following order. Restart the app each time you are prompted to:

1. Enable 'Spoof streaming data' (if disabled).
2. Enable 'Use JavaScript client' (and read the popup when enabling it).
3. Set the 'Default client' to `TV Simply`.
4. Enable 'Always show reload video button'. ('Show reload button' also needs to be enabled.)

Now if a video is taking a while to start or playback issues occur, simply press the 'Reload video button' in the video player.


### Why is the TV Simply client recommended?

`TV Simply` is recommended because it allows the 'Audio track' and 'Stable volume' options to be shown in the player flyout menu and it is available in all regions. The `TV` and `TV (Legacy)` clients are similar, but may not be as reliable as the `TV Simply` client.

> More details:
> 
> The 'Audio track' option in the player flyout menu is only shown when using the `TV`, `TV Simply`, `TV (Legacy)`, and `Android (No SDK)`. But the 'Disable forced auto audio track' setting is still functional when using the `Android VR (No Auth)` client.
> 
> The 'Stable volume' option in the player flyout menu is only supported by the `TV`, `TV Simply`, `TV (Legacy)`, `Android (No SDK)`, and `visionOS` clients. 
> 
> Additionally, in some regions (such as India), only the `TV`, `TV Simply`, `TV (Legacy)`, `Android VR (Auth)`, and `Android Studio` clients are available.



# YT Music

Over the past few patch releases there were notable changes regarding spoofing for playback in YT Music.

### What does this mean for me?

If you face playback issues in YT Music RVX, update the app. The 'Spoof streaming data' option will be enabled by default, so playback issues should not occur.

Note: Users with YT Premium or an intact GmsCore/microG installation from before March 2024 need to disable the 'Spoof streaming data' option (by opening YT Music RVX and navigating to Settings > RVX > Miscellaneous).



# How do I patch/update an RVX app?

To patch an app, refer to the [Beginner guide](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/guide-for-beginners.md) or the [documentation](https://github.com/inotia00/revanced-documentation#readme).

To update a patched app, you must patch a new APK and then install the newly patched APK as an update to the currently installed app. Installing it as an update will preserve your settings configuration.



# How do I know which patch version an RVX app is using?

For YouTube RVX, open the app and navigate to Settings > RVX > Miscellaneous > Patch information. The patch version is listed under "ReVanced Patches".

For YT Music RVX, open the app and navigate to Settings > RVX > Miscellaneous > App info. The patch version is listed under "ReVanced Patches".
