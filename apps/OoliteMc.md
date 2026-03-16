---
layout: app

permalink: /OoliteMc/
description: An OpenGL Elite-like space game
license: GPL-2.0-or-later

icons:
  - OoliteMc/icons/256x256/space.oolite.Oolite.png

screenshots:
  - OoliteMc/screenshot.png

authors:
  - name: mcarans
    url: https://github.com/mcarans

links:
  - type: GitHub
    url: mcarans/oolite
  - type: Download
    url: https://github.com/mcarans/oolite/releases

desktop:
  Desktop Entry:
    Name: oolite
    Comment: An OpenGL Elite-like space game
    Exec: run_oolite.sh
    Icon: space.oolite.Oolite
    Terminal: false
    Type: Application
    Categories: Game
    StartupWMClass: oolite
  AppImageHub:
    X-AppImage-Signature: 'directory ''/home/runner/.gnupg'' created keybox ''/home/runner/.gnupg/pubring.kbx''
      created [don''t know]: invalid packet (ctb=0a) no signature found the signature
      could not be verified. Please remember that the signature file (.sig or .asc)
      should be the first file given on the command line.'
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
---
