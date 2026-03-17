---
layout: app

permalink: /OoliteMc/
description: Open-world space opera
license: GPL-2.0-or-later

icons:
  - OoliteMc/icons/256x256/space.oolite.Oolite.png
screenshots:
- https://raw.githubusercontent.com/OoliteProject/oolite/1.92-maintenance/installers/FreeDesktop/oolite-999.png

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

appdata:
  Type: desktop-application
  ID: space.oolite.Oolite
  Name:
    C: Oolite
  Summary:
    C: Open-world space opera
  Description:
    C: >-
      <p>Oolite is inspired by the 8-bit classic Elite, and many aspects of gameplay will be familiar to players of that game.
      In the tradition of open-world games, there&apos;s no overall story: you can be a millionaire trader, a veteran combateer,
      a feared pirate, a lonely miner, a notorious smuggler, or all of them, or something else entirely, based on your own actions.</p>
  ProjectLicense: GPL-2.0-or-later
  Url:
    homepage: https://oolite.space
    bugtracker: https://github.com/OoliteProject/oolite/issues
    faq: https://wiki.alioth.net/index.php/Oolite_FAQ
  Launchable:
    desktop-id:
    - space.oolite.Oolite.desktop
  Screenshots:
  - default: true
    caption:
      C: The universe awaits. Go explore and seek your fortune!
    thumbnails: []
    source-image:
      url: https://raw.githubusercontent.com/OoliteProject/oolite/1.92-maintenance/installers/FreeDesktop/oolite-999.png
      lang: C
  - caption:
      C: Choose from a diverse range of interstellar craft.
    thumbnails: []
    source-image:
      url: https://raw.githubusercontent.com/OoliteProject/oolite/1.92-maintenance/installers/FreeDesktop/oolite-008.png
      lang: C
  - caption:
      C: Find safety in massive orbital stations.
    thumbnails: []
    source-image:
      url: https://raw.githubusercontent.com/OoliteProject/oolite/1.92-maintenance/installers/FreeDesktop/oolite-064.png
      lang: C
  - caption:
      C: Access the expansion pack manager and quick reference guides on the start screen.
    thumbnails: []
    source-image:
      url: https://raw.githubusercontent.com/OoliteProject/oolite/1.92-maintenance/installers/FreeDesktop/oolite-001.png
      lang: C
  - caption:
      C: Learn to fly with the tutorial covering piloting, combat, and travel.
    thumbnails: []
    source-image:
      url: https://raw.githubusercontent.com/OoliteProject/oolite/1.92-maintenance/installers/FreeDesktop/oolite-002.png
      lang: C
  - caption:
      C: Fly to Maraus, a wealthy industrial world, one of 2000 systems to be discovered.
    thumbnails: []
    source-image:
      url: https://raw.githubusercontent.com/OoliteProject/oolite/1.92-maintenance/installers/FreeDesktop/oolite-004.png
      lang: C
  Releases:
  - version: 1.92.1
    unix-timestamp: 1773705600
    description:
      C: >-
        <p>This stable release fixes these bugs:</p>
  
        <ul>
          <li>Centre main window after showing splash.</li>
          <li>Smooth resizing of game window.</li>
          <li>Fix for crash when no network.</li>
        </ul>
  - version: '1.92'
    unix-timestamp: 1770076800
    description:
      C: >-
        <p>First release of Oolite for Flatpak and AppImage.</p>
  ContentRating:
    oars-1.1:
      violence-fantasy: moderate
      drugs-alcohol: mild
      drugs-narcotics: mild
---
