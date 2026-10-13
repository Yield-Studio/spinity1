---
layout: default
title: Spinity
description: A native Spotify client, fast and lightweight.
---

{% assign version = site.data.versions.current %}

<div class="hero">
  <div class="hero-content">
    <img src="{{ site.baseurl }}/assets/images/logo.svg" alt="Spinity logo" width="88" height="88" class="hero-logo">
    <h1>Spinity</h1>
    <p class="hero-tagline"><strong>Spotify, native and fast.</strong></p>
    <p>A lightweight music app for Linux, macOS, and Windows.</p>
    <div class="hero-actions">
      <a href="{{ site.baseurl }}/download/" class="button primary">Download</a>
      <a href="{{ site.baseurl }}/getting-started/" class="button">Getting started</a>
      <a href="{{ site.baseurl }}/using-spinity/" class="button">User guide</a>
    </div>
  </div>
  <div class="hero-image">
    <img src="{{ site.baseurl }}/assets/images/screenshot.png" alt="Spinity Home with the playlist library, recommendations, queue, and player visible" width="800" height="500">
  </div>
</div>

<div class="features">
  <div class="feature">
    <h2>Your music, on your desktop</h2>
    <p>Browse playlists, Liked Songs, albums, artists, and podcasts. Search the catalogue and edit playlists you own.</p>
  </div>
  <div class="feature">
    <h2>Spotify Connect</h2>
    <p>Play on this computer or control playback on your other devices.</p>
  </div>
  <div class="feature">
    <h2>Themes</h2>
    <p>Choose light, dark, system appearance, or custom colours. Follow your desktop theme as it changes.</p>
  </div>
  <div class="feature">
    <h2>Desktop controls</h2>
    <p>Use keyboard shortcuts and media keys. Keep music playing from the tray when supported.</p>
  </div>
  <div class="feature">
    <h2>Winamp mini player</h2>
    <p>Use classic skins with an equalizer, playlist, and animated sound displays.</p>
  </div>
  <div class="feature">
    <h2>MilkDrop</h2>
    <p>Watch music-reactive visuals in a separate window or full screen.</p>
  </div>
</div>

<div class="milkdrop-showcase">
  <video autoplay loop muted playsinline preload="metadata" poster="{{ site.baseurl }}/assets/images/milkdrop-poster.jpg" aria-label="MilkDrop presets reacting to music in Spinity">
    <source src="{{ site.baseurl }}/assets/videos/milkdrop.mp4" type="video/mp4">
  </video>
</div>

<div class="sibling">
  <p>Spinity's sibling: the same native interface, for WhatsApp. Both are built on <a href="https://github.com/crmne/fastframe">fastframe</a>.</p>
</div>

<div class="acknowledgements">
  <p>Spinity uses <a href="https://github.com/librespot-org/librespot">librespot</a>,
  <a href="https://github.com/emilk/egui">egui</a>, the <a href="https://rsms.me/inter/">Inter</a>
  typeface (OFL), and <a href="https://lucide.dev">Lucide</a> icons (ISC).</p>
  <p>Spinity is an independent project and is not affiliated with Spotify.<br>Spotify is a trademark of Spotify AB.</p>
  <p>Licensed under the <a href="https://github.com/Yield-Studio/spinity1/blob/main/LICENSE">Apache License 2.0</a>.</p>
</div>
