# ksu4rmx3834

- [Releases](https://github.com/ksu4rmx3834/manifest/releases)
- [How to Build](https://github.com/ksu4rmx3834/common/wiki)

## Issues

- [Kernel/kernel build](https://github.com/ksu4rmx3834/common/issues)
- [AnyKernel](https://github.com/ksu4rmx3834/mkanykernel/issues)
- [boot.img](https://github.com/ksu4rmx3834/mkbootimg/issues)

## Project struct

- ksu4rmx3834
    - manifest - Manifest for `repo` 
        - `master` - Point to `master` in common and `master-kernel-build-2021` in AOSP toolchain
        - `ksun` - `master`, but uses `ksun` in common and latest KernelSU tag
    - common - Kernel source code
        - `master` - Pure kernel source with build fixes 
        - `ksun` - `master` + KernelSU Next integration
    - mkbootimg - Tool to automatically generate `boot.img`
    - mkanykernel - Tool to automatically generate `UPDATE-AnyKernel3.zip`
