# LineageOS 23.0 Custom Kernel - SukiSU Ultra for the Sony Xperia 1 V & Sony Xperia 5 V
<img src="https://github.com/spacealtctrl/sm8550_SukiSU_SUSFS/blob/main/assets/sonysuki.png" alt="SukiSU Ultra" width="100" height="150"/>

## Requirements
- **ROM**: LineageOS 23.0 (Android 16)
- **Device**: Sony Xperia 1 V (pdx234) / Sony Xperia 5 V (pdx237)
- **Recovery**: [TWRP](https://xdaforums.com/t/recovery-unofficial-updated-teamwin-recovery-project-3-7-1-for-xperia-1v-03-20-2024.4662645/)

## Features
- **SukiSU Ultra**
- **SUSFS (ඞ) 2.0.0**
- **[Baseband-guard](https://github.com/vc-teahouse/Baseband-guard)**
- **KPM**
- **BBR TCP**
- **LZ4KD**
- **LZ4 1.10.0** - Upgraded

## Installation
1. Ensure you're running **LineageOS 23.0**
2. Download the latest release from [Releases](../../releases)
3. Boot into custom recovery ([TWRP](https://xdaforums.com/t/recovery-unofficial-updated-teamwin-recovery-project-3-7-1-for-xperia-1v-03-20-2024.4662645/))
4. Flash the AnyKernel3 zip
5. Install the SukiSU Manager APK
6. Reboot

⚠️ **Warning**: Use [Horizon Kernel Flasher](https://github.com/libxzr/HorizonKernelFlasher) only when flashing on the fly.

📃 **Note**: In SUS SU Mode 2, it may show as disabled or incompatible because non-kprobe hooks are used during compilation, which are no longer needed.

## Build Variants
- **Stable Branch** (`susfs-main`) - Tested and stable
- **Dev Branch** (`susfs-test`) - Latest features, may be unstable

## Build Options
- **SUSFS** - Enable/disable filesystem hiding
- **KPM** - Enable/disable Kernel Patch Module
- **ZRAM** - Enable/disable LZ4KD optimizations

## Credits, Acknowledgments & Thanks
A post from someone called 'DeadEnd91' on XDA which made me decide to take on this project.

This wouldn't be possible without the amazing work from:

### Core Contributors
- **[tiann](https://github.com/tiann)** - Original KernelSU creator
- **[ShirkNeko](https://github.com/ShirkNeko)** - SukiSU Ultra development and patches
- **[simonpunk](https://gitlab.com/simonpunk)** - SUSFS development
- **[zzh20188](https://github.com/zzh20188)** - LZ4 1.10.0 upgrade patches and improvements
- **[vc-teahouse](https://github.com/vc-teahouse)** - Baseband-guard LSM development
- **[Tools-cx-app](https://github.com/Tools-cx-app)** - Kernel patches repository
- **[WildKernels](https://github.com/WildKernels/AnyKernel3)** - AnyKernel3 branch

### Special Thanks
- **LineageOS Team** - For the LineageOS 23.0 kernel source
- **Sony Open Devices Project** - For device support
- **[sidex15](https://github.com/sidex15)** - SUSFS module development
- **[libxzr](https://github.com/libxzr)** - Horizon Kernel Flasher
- **[osm0sis](https://github.com/osm0sis)** - Original AnyKernel3

### Community
- All testers and users who provided feedback
- The KernelSU community for continuous support
- Android kernel development community

## Resources
- **Manager**: [SukiSU-Ultra](https://github.com/SukiSU-Ultra/SukiSU-Ultra)
- **Modules**: [ksu_module_susfs](https://github.com/sidex15/ksu_module_susfs)
- **Baseband-guard**: [vc-teahouse/Baseband-guard](https://github.com/vc-teahouse/Baseband-guard)
- **Support**: Open an issue in this repository

## License
This kernel is based on the Linux kernel and inherits its GPLv2 license. All modifications are also released under GPLv2.

## Disclaimer
This kernel is provided as-is without any warranty. Use at your own risk. Always backup your data before flashing custom kernels.

---
[![Website](https://img.shields.io/badge/Website-spacealtctrl.net-blue?logo=firefoxbrowser&logoColor=white)](https://spacealtctrl.net)
