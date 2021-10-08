![XD](https://github.com/xyz-prjkt/xyz_assets/raw/main/xd_manifest_v2.png)
# xdroidCAF | rev2.0 mnmlistyou
a android based on AOSP with Minimalist UI Design.

### Requirements
- Around 500GB disk space.
- Around 18GB RAM running Linux.

### Sync our source ###
```bash
        repo init -u https://github.com/xdroidsp/xd_manifest -b xd.xii
```
```bash
        repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build our source ###
```bash
        . build/envsetup.sh
        lunch xdroid_$devicecodename-userdebug
        make xd -j$(nproc --all)
```

### Credits ###
 * [**AOSP**](https://android.googlesource.com)
 * [**CAF**](https://source.codeaurora.org)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**POSP**](https://github.com/PotatoProject)
 * [**StatixOS**](https://github.com/StatiXOS)
 * [**WeebProject**](https://github.com/WeebProject)
 * [**AOSPMasterVayu**](https://github.com/AOSP-Master-Vayu)
 * [**AEX**](https://github.com/AospExtended)
