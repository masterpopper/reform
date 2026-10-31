<div align="center">
  <img src="Velora%20logo.png" alt="Velora" width="160">
  <h1>Velora</h1>
  <p><strong>Movies, series, and live browsing—built for your TV remote.</strong></p>
  <p>
    <a href="https://github.com/masterpopper/reform/releases/latest"><img src="https://img.shields.io/github/v/release/masterpopper/reform?label=latest%20release&color=c6a66b" alt="Latest release"></a>
    <img src="https://img.shields.io/badge/Android-7.0%2B-3DDC84" alt="Android 7.0 or newer">
    <img src="https://img.shields.io/badge/Navigation-TV%20remote-c6a66b" alt="TV remote navigation">
  </p>
  <p><a href="https://github.com/masterpopper/reform/releases/latest"><strong>Download the latest APK</strong></a> · <a href="#installation">Installation</a> · <a href="#updates">Updates</a> · <a href="https://github.com/masterpopper/reform/issues">Report an issue</a></p>
</div>

---

## A home for your next watch

Velora is an Android TV app with a remote-friendly interface for browsing movies, series, Live TV, and Sports. Explore trending and popular titles, search the catalog, and keep separate local profiles for everyone using your TV.

### Features

- **TV remote navigation:** directional controls, visible focus, and Back navigation.
- **Movies and series:** trending, popular, and category collections, plus provider collections where metadata is available.
- **Flexible search:** matches ignore spaces and punctuation while preserving numbers. Equally relevant English-language titles receive preference, with popularity helping order the results.
- **Local profiles and My List:** each profile keeps its own saved titles and viewing history on the device.
- **Continue Watching:** return to a saved movie or episode position, subject to playback-source support.
- **Kids profiles:** a filtered family collection with ads disabled. Content classification depends on third-party metadata and may be incomplete.
- **Live TV and Sports:** listings supplied by the playback service; availability changes.
- **In-app updates:** check for the latest GitHub release directly from Settings.

Provider collections are Velora browsing pages, not the providers' official apps. Listings do not guarantee that a title or stream is available. Playback quality, language, and availability depend on the source.

## Installation

### Quick access

| Method | Code or link |
| --- | --- |
| **Downloader by AFTVnews** | **`6484220`** |
| **Unlinked library** | **`VeloraFS`** |
| **GitHub APK** | [Latest release](https://github.com/masterpopper/reform/releases/latest) |

### Fire TV / Fire TV Stick: Downloader

These instructions apply to **Android-based Fire TV devices that support APK installation**. Devices running a different operating system, such as Vega OS, cannot install this Android APK.

1. On your Fire TV, search the Amazon Appstore for **Downloader by AFTVnews** and install it.
2. Open **Settings → My Fire TV → Developer Options → Install unknown apps** and allow **Downloader** to install apps. Menu names vary by device; older versions may call this **Apps from Unknown Sources**.
3. If **Developer Options** is missing, open **Settings → My Fire TV → About**, highlight your device name, and press **Select seven times**. Go back to find Developer Options.
4. Open Downloader. In its URL/search field, enter **`6484220`** and select **Go**.
5. Follow the redirect and wait for the Velora APK to finish downloading. Check that the destination is a release under **`github.com/masterpopper/reform`**.
6. When Android's installer appears, select **Install**, then **Open** when installation completes.
7. You may delete the downloaded APK afterward to reclaim space. Deleting the installer file does not uninstall Velora.

If the code is unavailable or points to an older build, use the [latest GitHub release](https://github.com/masterpopper/reform/releases/latest) instead. Download the **`.apk` asset**; you do not need the source-code ZIP or TAR files.

Downloader reference: [official AFTVnews app page](https://www.aftvnews.com/downloader/).

### Android TV / Google TV

1. Install Downloader from your device's app store where available, or transfer the APK from the [latest release](https://github.com/masterpopper/reform/releases/latest) to your TV.
2. Allow the app opening the APK to **install unknown apps** when Android requests it. This is usually under **Settings → Apps → Special app access → Install unknown apps**; the path varies by manufacturer.
3. In Downloader, enter **`6484220`**, or open the transferred APK with your file manager.
4. Select **Install**, wait for completion, then open Velora from your apps list.

Velora requires **Android 7.0 / API 24 or newer** and a device that supports Android APKs. ARM, ARM64, x86, and x86_64 libraries are included. Compatibility and performance vary by device; this is not a guarantee of support for every TV. Samsung Tizen and LG webOS cannot install this APK directly.

### Unlinked

If you already use Unlinked:

1. Open Unlinked and choose **Add a new library**.
2. Enter **`VeloraFS`** as the library code.
3. Open the library, select Velora, and download the APK.
4. Choose **Install** and approve Android's installation prompt. If requested, allow installation from Unlinked in your device settings.

For information about Unlinked itself, use its [official website](https://unlinked.link/).

## Using Velora

| Remote button | Action |
| --- | --- |
| **Up / Down / Left / Right** | Move between controls and titles |
| **OK / Select** | Open the focused item or activate a button |
| **Back** | Close the current overlay or return to the previous browsing screen |

Choose a profile to keep its My List and viewing progress separate. Profiles are local to the device; they do not sync between TVs. Clearing app data or uninstalling can remove those profiles and lists.

Open a series to choose a season and episode. Continue Watching appears after sufficient playback has been recorded; completed titles leave that row.

## Updates

1. Open **Velora → Settings → Check for updates**.
2. If a newer version is available, download it and select **Install now**.
3. If Android requests permission, allow **Velora** to install updates, then return to the app and continue installation.
4. Complete Android's **Install** prompt and wait for confirmation before reopening Velora.

Automatic update checks can be controlled in Settings. They check for updates; Android still requires you to approve installation. You can also install a newer official APK over the existing app. **Do not uninstall first** if you want to retain local profiles and lists.

## Advertising and content settings

Velora displays a compact banner labeled **ADVERTISEMENT** while browsing. In version 2.1, the banner appears for up to 20 seconds initially and can appear again after returning from playback or a trailer. The ad WebView is destroyed when the cycle ends. Ads are hidden in Kids profiles and during playback.

Advertisements are third-party content, not Velora controls or installation/update notices. Use Velora's Settings or this repository's releases to update the app.

**Block adult content** is on by default and always enforced in Kids. It filters available metadata, which may be inaccurate or incomplete; it is not a guarantee that every inappropriate title will be excluded.

## Troubleshooting

<details>
<summary><strong>The APK downloads, but no installer appears</strong></summary>

Check that the downloading app has permission to install unknown apps. For Velora's built-in updater, return to Settings and select **Check for updates** again to reopen the downloaded update prompt. Complete the Android installer rather than waiting for a silent installation.

</details>

<details>
<summary><strong>Android says “App not installed” or reports a package conflict</strong></summary>

Confirm that the APK came from this repository, that there is enough storage, and that your device supports Android APKs. An existing copy signed with a different certificate cannot be updated in place. Report the exact message before uninstalling or clearing data, as those actions can remove your local profiles and lists.

</details>

<details>
<summary><strong>The app feels slow or a screen does not fit</strong></summary>

Install the latest release and restart Velora. Check available device storage. If the problem persists, report the device model, Fire OS/Android version, Velora version, affected screen, and the steps that reproduce it. Include whether the delay continues after the advertisement closes.

</details>

<details>
<summary><strong>A movie, channel, or event is missing or will not play</strong></summary>

Availability is controlled by the playback service and sources. Refresh the relevant collection and check your connection. A catalog entry does not guarantee a working stream, a particular quality, or English audio. Live and PPV events are not guaranteed to be listed.

</details>

<details>
<summary><strong>The app asks for activation</strong></summary>

Some builds may have an expiration date or require an activation code. Check the expiration information in Settings and obtain a valid code from the person who supplied the build. Reinstalling is not an activation method.

</details>

## Feedback

[Open an issue](https://github.com/masterpopper/reform/issues/new) with:

- Your device model and Android / Fire OS version.
- Your Velora version.
- What you did, what happened, and what you expected.
- Whether the issue occurs consistently.

Do not include passwords, activation codes, API keys, or other private information.

---

**Project downloads:** [GitHub Releases](https://github.com/masterpopper/reform/releases)  
Velora is not affiliated with Amazon, Google, Netflix, Disney, or the other providers referenced in its collections. Use only content and services you are authorized to access.
