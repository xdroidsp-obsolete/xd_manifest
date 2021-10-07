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
 * [**LineageOS**](https://github.com/LineageOS)
