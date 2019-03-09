# Post installation: fix audio and iGPU
  
  Download [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen/releases) and [AppleALC.kext](https://github.com/acidanthera/AppleALC/releases) to SSD's EFI/Clover/Other, WhateverGreen fixes lots of issues with IGPU, AMD, and Nvidia graphics, AppleALC.kext helps us get audio working.  Follow the [guide](https://www.tonymacx86.com/threads/an-idiots-guide-to-lilu-and-its-plug-ins.260063/) to generate a clover patch. The audio layout-id of Gigabyte-Z390I-WIFI should be `7`, the `PlatformId` of 9700k should be 
