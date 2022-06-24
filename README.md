## Recovery Device Tree for the Samsung Galaxy XCover Pro (Exynos)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_xcoverprosq-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_xcoverpro
