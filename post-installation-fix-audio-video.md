# Post installation: fix audio and iGPU

  Without audio and video patch, system has no sounds and gpu mem size is 3MB only.

  ![before-video-patch-system-info](./screenshots/fix-audio-video/before-video-patch-system-info.png)

  Download [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen/releases) and [AppleALC.kext](https://github.com/acidanthera/AppleALC/releases) to SSD's EFI/Clover/Other, WhateverGreen fixes lots of issues with IGPU, AMD, and Nvidia graphics, AppleALC.kext helps us get audio working.  Follow the [guide](https://www.tonymacx86.com/threads/an-idiots-guide-to-lilu-and-its-plug-ins.260063/) to generate a clover patch. The audio layout-id of Gigabyte-Z390I-WIFI should be `7`, the `PlatformId` should be `3E0B0007` if you don't use eGPU, otherwise should be `3E920003`

- download and open [hackintool](https://www.tonymacx86.com/threads/release-hackintool-v1-9-6.254559/)
- select `macOS 10.14` at the menubar
  ![./screenshots/fix-audio-video/select-macos.png]
- select `Coffee Lake` as IntelGen. `3E9B0007` or `3E920003` as PlatformId.
  ![./screenshots/fix-audio-video/platform-id.jpg]
- select `7` as layout id at audio tab
  ![./screenshots/fix-audio-video/layout-id.jpg]
- generate patch
  ![./screenshots/fix-audio-video/generate-patch-1.jpg]
  ![./screenshots/fix-audio-video/generate-patch-2.jpg]
- copy patch output to config.plist
- after reboot.
  ![./screenshots/fix-audio-video/after-patch-system-info.jpg]
  ![./screenshots/fix-audio-video/after-patch-hackintool-info.jpg]
