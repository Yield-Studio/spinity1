<p align="center">
  <img src="docs/assets/images/logo.svg" alt="Spinity logo" width="88" height="88">
</p>

<h1 align="center">Spinity</h1>

<p align="center"><strong>Spotify, native and fast.</strong><br>A lightweight music app for Linux, macOS, and Windows.</p>

<p align="center">
  <a href="https://github.com/Yield-Studio/spinity1/releases"><strong>Download</strong></a> \u00b7
  <a href="docs/_guide/getting-started.md">Getting started</a> \u00b7
  <a href="docs/_guide/using-spinity.md">User guide</a> \u00b7
  <a href="CONTRIBUTING.md">Contribute</a>
</p>

<p align="center">
  <a href="Cargo.toml"><img src="https://img.shields.io/badge/Built_with-Rust-1ed760" alt="Built with Rust"></a>
  <a href="https://github.com/Yield-Studio/spinity1/releases"><img src="https://img.shields.io/badge/Linux_%C2%B7_macOS_%C2%B7_Windows-24292f" alt="Linux, macOS, and Windows"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-1ed760" alt="Apache 2.0 license"></a>
</p>

Spinity is a Spotify client written in Rust with
[egui](https://github.com/emilk/egui). It plays music through
[librespot](https://github.com/librespot-org/librespot), typically uses
100\u2013250 MB of RAM, starts in well under a second, and has no browser engine.

The interface includes complete Spanish, Turkish, and Ukrainian translations.

**Playback needs Spotify Premium.** Free accounts can browse and search, but
cannot play music through Spinity.

![Spinity Home with the playlist library, recommendations, queue, and player visible](docs/screenshot.png)

<details>
<summary><strong>Watch Spinity in action</strong></summary>

https://github.com/user-attachments/assets/a5f669ce-b3b7-4f8e-9933-976a78876c7e

</details>

[Features](#your-music-on-your-desktop) \u00b7 [Install](#install) \u00b7 [First playback](#start-listening) \u00b7 [Mini player](#the-winamp-mini-player) \u00b7 [MilkDrop](#music-in-motion) \u00b7 [Help](#guides-and-help)

## Your music, on your desktop

| Feature | What you can do |
|---|---|
| **Library and search** | Browse playlists, Liked Songs, albums, artists, and podcasts. Search the catalogue and edit playlists you own. |
| **Spotify Connect** | Play on this computer or control playback on your other devices. |
| **Themes** | Choose light, dark, system appearance, or custom colours. On Omarchy, follow your desktop theme. |
| **Desktop controls** | Use keyboard shortcuts and media keys. Keep music playing from the tray when supported by your desktop and settings. |
| **Winamp mini player** | Use classic skins with an equalizer, playlist, and animated sound displays. |
| **MilkDrop** | Watch music-reactive visuals in a separate window or full screen. See platform availability below. |

## Install

| Platform | Installation |
|---|---|
| **macOS** | Build from source, or download from [Releases](https://github.com/Yield-Studio/spinity1/releases). |
| **Arch Linux** | Build from source or use AUR packages. |
| **Windows** | Choose your build from [Releases](https://github.com/Yield-Studio/spinity1/releases). |
| **Other Linux** | Find Flatpak, AppImage, Nix, and other options in the [Releases](https://github.com/Yield-Studio/spinity1/releases). |
| **From source** | Follow [Build from source](docs/_guide/getting-started.md) for dependencies and commands. |

On Windows, releases come as a Windows Installer package (`.msi`)
that needs no administrator password. Spinity installed with the earlier
setup program (`-setup.exe`) moves to it through its own updates and keeps its
settings.

Uninstalling while the installed `spinity.exe` runs removes nothing until it
is closed. The installer asks whether to close it (**Yes**), check again once
you have quit it (**No**), or **Cancel**; the earlier setup program offers
**Retry**, **Close Spinity**, or **Cancel**. Closing ends the installed process
immediately; unsaved changes may be lost. A silent uninstall stops without
removing files.

## Start listening

1. Open Spinity and choose **Sign in with Spotify**. Approve access in your
   browser, then return to the app to see your library.
2. To listen on this computer, open the device menu in the bottom player bar
   and choose **Set up playback here**, also available in Settings.
3. Complete the separate playback approval in your browser. Your computer
   appears as a Spotify Connect device named **Spinity**.

Library access and local playback have separate approvals. Spinity remembers
both using your computer's protected storage. See
[Getting started](docs/_guide/getting-started.md) for the full walkthrough
and [How it connects](docs/_reference/how-it-connects.md) for the details.

## The Winamp mini player

A classic look for your music, with Winamp 2 `.wsz` skins, an equalizer,
a playlist, and animated sound displays. Switch with **Ctrl+M**
(**Cmd+Shift+M** on macOS), the shrink button, or Settings.

<p align="center">
  <img src="docs/assets/images/winamp.png" alt="Spinity's Winamp mini player with the built-in skin, equalizer, and playlist" width="320">
</p>

[Explore the mini player](docs/_guide/winamp.md), including skins,
window sizes, controls, and the return to the main player.

## Music in motion

MilkDrop reacts to music playing on this computer, with more than 10,000
presets downloaded on first use. Open it from the visualiser button,
Settings, or the mini player's **V** menu.

![MilkDrop visualiser displaying coloured concentric patterns in Spinity](docs/assets/images/milkdrop-poster.jpg)

Included on **Linux**, **macOS**, and **Windows Intel/AMD** builds.
It is not included in the Windows on ARM download.
[Read the MilkDrop guide](docs/_guide/milkdrop.md) for presets,
controls, and fullscreen mode.

## Guides and help

The complete guide lives in the **docs/** directory of this repository.

| You want to\u2026 | Read |
|---|---|
| Sign in, set up playback, or configure themes, fonts, and proxies | [Getting started](docs/_guide/getting-started.md) |
| Learn shortcuts, command-line controls, and updates | [Everyday use](docs/_guide/using-spinity.md) |
| Find configuration and stored files | [Settings and files](docs/_reference/settings-and-files.md) |
| Understand scrolling performance and reduce loading delays | [Make it even faster](docs/_guide/make-it-even-faster.md) |
| Understand what is stored and sent | [Privacy](docs/_reference/privacy.md) \u00b7 [How it connects](docs/_reference/how-it-connects.md) |
| Check Spotify and librespot limitations | [What Spotify allows](docs/_reference/what-spotify-allows.md) |
| Understand account risk | [Will my account get banned?](docs/_guide/what-is-spinity.md/#will-my-spotify-account-get-banned) |
| Report a bug or propose a feature | Read [Contributing](CONTRIBUTING.md), then use the [issue forms](https://github.com/Yield-Studio/spinity1/issues/new/choose). |

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening an issue or pull
request. To look at the interface without a Spotify account, run:

```sh
cargo run --features demo -- --demo
```

Translations live in `assets/i18n/`; see
[Translating Spinity](docs/_reference/translating.md). Release packaging
is described in [PACKAGING.md](PACKAGING.md).

## More native apps

**Want WhatsApp just as fast and native?** Spinity is built on
[fastframe](https://github.com/crmne/fastframe).

## Sonos playback

Sonos speakers use the Spotify Connect session for playback control. Enable
local playback first, then select the speaker in the device picker.

## Acknowledgements

Spinity uses [librespot](https://github.com/librespot-org/librespot),
[egui](https://github.com/emilk/egui), the [Inter](https://rsms.me/inter/)
typeface (OFL), and [Lucide](https://lucide.dev) icons (ISC).

Spinity is an independent project and is not affiliated with Spotify.
Spotify is a trademark of Spotify AB.

Licensed under the [Apache License 2.0](LICENSE).
