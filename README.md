# framework-ststm8spl-c-splitter
STM8S/A Standard Peripherals Library based on v2.3.1 from [here](https://www.st.com/en/embedded-software/stsw-stm8069.html)

Note that accepting [Download-License_SLA0048_STSW-STM8069.pdf](Download-License_SLA0048_STSW-STM8069.pdf) was required for downloading the library from STMicroelectronics
and [MCD-ST Liberty SW License Agreement V2.pdf](MCD-ST%20Liberty%20SW%20License%20Agreement%20V2.pdf) was inside the package.

This framework is intended for [this](https://github.com/Zelberor/platform-ststm8-c-splitter) PlatformIO platform.

## Modifications
* Patched with [this](https://github.com/gicking/STM8-SPL_SDCC_patch/blob/cf8dcd8fe4d0f794cd239e4fb98fece10c184f3a/STM8S_StdPeriph_Lib_V2.3.1_sdcc.patch) patch
* Adjusted [stm8s.h](src/stm8s.h) with some fixes from [sduino](https://github.com/tenbaht/sduino)
* Added ```// <--#SPLIT#--> //``` markers for automatic splitting of the *.c files. This allows for lower memory usage when compiling with SDCC.




### Disclaimer
This repository is **NOT** affiliated with or endorsed by STMicroelectronics.
