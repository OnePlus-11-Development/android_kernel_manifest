## Repo Init ##
```bash
repo init -u https://github.com/OnePlus-11-Development/android_kernel_manifest.git -b common-android13-5.15
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
## Building Kernel ##
```bash
BUILD_KERNEL=1 ./build_oplus.sh
```
