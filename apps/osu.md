---
layout: app

permalink: /osu/
description: Rhythm is just a *click* away.

icons:
  - osu/icons/1024x1024/osu!.png

screenshots:
  - osu/screenshot.png

authors:
  - name: ppy
    url: https://github.com/ppy

links:
  - type: GitHub
    url: ppy/osu
  - type: Download
    url: https://github.com/ppy/osu/releases

desktop:
  Desktop Entry:
    Type: Application
    Name: osu!
    Comment: Rhythm is just a *click* away.
    Icon: osu!
    Exec: osu!
    Path: "~"
    Terminal: true
    Categories: Game
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|ppy|osu|latest|osu.AppImage.zsync
    X-AppImage-Signature: 'Signature made Fri 14 Aug 2020 01:33:15 PM UTC using RSA
      key ID 117D6549 Can''t check signature: No public key'
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
---
