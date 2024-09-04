# Snapp Public AOSP Local Manifest 

This manifest adds a number of targets to an AOSP build. To make use of this you should;

1. Init your repo with the appropriate URL and branch (e.g. `repo init -u https://android.googlesource.com/platform/manifest -b android-platform-15.0.0_r1 --git-lfs`).
2. Checkout this repo into the local manifests area (e.g. `git clone https://github.com/snappautomotive/firmware-local_manifest.git .repo/local_manifests -b android-15`).
3. Perform a repo sync (e.g. `repo sync`)
4. Use one of the additional targets (e.g. `snapp_car_x86_64-ap3a-userdebug`)
.
.
.
99. Profit!
