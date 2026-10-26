<div align="center">
<img src="https://github.com/gokadzev/Musify/raw/master/.github/assets/Musify-banner.png" width="100%">

# Musify

Unlock the full potential of music: Stream effortlessly with one app!

[![Stars](https://img.shields.io/github/stars/gokadzev/Musify?style=flat-square&color=D3BEAB)](https://github.com/gokadzev/Musify/stargazers)
[![Forks](https://img.shields.io/github/forks/gokadzev/Musify?style=flat-square&color=D3BEAB)](https://github.com/gokadzev/Musify/fork)
[![Downloads](https://img.shields.io/github/downloads/gokadzev/Musify/total?style=flat-square&color=D3BEAB)](https://github.com/gokadzev/Musify/releases)
[![GitHub release](https://img.shields.io/github/v/release/gokadzev/Musify?color=D3BEAB)](https://github.com/gokadzev/Musify/releases)
[![License](https://img.shields.io/github/license/gokadzev/Musify?color=D3BEAB)](LICENSE)

---

<a href="https://ko-fi.com/gokadzev" target="_blank" title="ko-fi">
  <img src="https://github.com/user-attachments/assets/1c204507-d124-4b34-878b-96c39c9bb3f8"  alt="ko-fi badge" style="width: 150px;">
</a>



---

## Features

<center>

Online song search with suggestions <br/>
Offline listening support <br/>
Import & export your data and never lose it <br/>
Add custom playlists with link <br/>
Listening Recaps <br/>
Spotify playlist import <br/>
Radio stations <br/>
Optimized sound experience <br/>
SponsorBlock support <br/>
Lyrics support <br/>
No ads <br/>
No subscriptions <br/>
Built-in updater <br/>
Built-in equalizer with presets <br/>
21 supported languages <br/>
Material UI & accent colors & dynamic colors (Android 12+) <br/>

</center>


---

## Screenshots

| ![Screenshot 1](https://raw.githubusercontent.com/gokadzev/Musify/master/fastlane/metadata/android/en-US/images/phoneScreenshots/01.jpg) | ![Screenshot 2](https://raw.githubusercontent.com/gokadzev/Musify/master/fastlane/metadata/android/en-US/images/phoneScreenshots/02.jpg) | ![Screenshot 3](https://raw.githubusercontent.com/gokadzev/Musify/master/fastlane/metadata/android/en-US/images/phoneScreenshots/03.jpg) | ![Screenshot 4](https://raw.githubusercontent.com/gokadzev/Musify/master/fastlane/metadata/android/en-US/images/phoneScreenshots/04.jpg) |
|----------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|

---

## Supported platforms

| Platform | Status | Dependencies |
|----------|--------|--------------|
| Android  | ✅ Supported | — |
| Linux    | ✅  Supported (Beta) | Will be added soon... |
| Windows    | ✅  Supported (Beta) | — |
| IOS    | ❌ Unsupported | — |

---

## Download


[<img src="https://github.com/gokadzev/Musify/raw/master/.github/assets/get-it-on-github.png" alt="Get it on Github" height="80">](https://github.com/gokadzev/Musify/releases/latest)
[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" alt="Get it on Fdroid" height="80">](https://f-droid.org/packages/com.gokadzev.musify.fdroid)


---

## Contributors

Special thanks to all contributors for their time and effort.

<a href="https://github.com/gokadzev/Musify/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=gokadzev/Musify" alt="Contributors"/>
</a>


---

## Contribute

Contributions are always welcome. Please read our [contributing guidelines](https://github.com/gokadzev/Musify/blob/master/CONTRIBUTING.md) before contributing.

---

## F.A.Q

You can see frequently asked questions and their answers [here](https://github.com/gokadzev/Musify/discussions/728).

---

## Credits

[Musify](https://github.com/Harsh-23/Musify) - Original inspiration for the concept and name. It is now completely reimplemented with new design and branding.


---

## License

```
Copyright © 2026 Valeri Gokadze

Musify is free software licensed under GPL v3.0. You may use, modify, and distribute
this software freely, but must keep the source code open and publicly available, retain
all copyright notices, disclose all changes made, and use the same GPL v3.0 license.

Prohibited: Closed-source distributions or commercial redistribution of modified versions.
```

See the [GNU General Public License](https://github.com/gokadzev/Musify/blob/master/LICENSE) for full details.

---

## Disclaimer

```
Musify and its contributors do not host, own, or distribute any copyrighted audio content.
The app provides access to content through plugins and external sources. All trademarks, songs, audio files, and related content remain the property of their respective owners and are protected by applicable copyright laws.
Included plugins are provided for interoperability and educational purposes only. Users are solely responsible for ensuring that their use of the app complies with local laws, copyright regulations, and the terms of service of the respective content providers.
The developers of Musify do not encourage or endorse copyright infringement and assume no liability for misuse of the software or third-party plugins.
```
---


## Browser edition (no APK)

This repository now includes a lightweight browser-based edition in the `web/` directory. It provides a responsive music-search interface, in-page YouTube playback, a persistent player, liked songs, local playlists, queue controls, volume, and light/dark appearance. Saved library data stays in the current browser using local storage.

The browser edition is separate from the Flutter mobile/desktop application and does not require installing an APK. Music discovery uses public third-party Piped instances and playback uses the YouTube embedded player; those services can be unavailable, rate-limited, region-restricted, or block embedding. The web edition therefore cannot guarantee that every track will play. Browser playback requires an internet connection and may be subject to YouTube's restrictions.

A GitHub Actions workflow in `.github/workflows/web-pages.yml` publishes the contents of `web/` to GitHub Pages when enabled in repository settings. After the first successful deployment, the site is normally available at `https://patrickmango49.github.io/Musify/`.
