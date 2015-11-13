Cold Fusion AOSP

repo init -u https://github.com/ColdFusionAOSP/manifest.git -b mm6.0

repo sync

source build/envsetup.sh

lunch

make -j16 otapackage
