Getting Started:
 ==============

To get started with Project Blaze, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/ProjectBlaze/manifest.git -b 13 --depth=1
```

Then to sync up:

```
repo sync -c -j$(nproc --all) --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune
```

---------------------------------------------------------------------------------------
 Compilation of ProjectBlaze:
 ==================

From root directory of Project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch blaze_$device-userdebug
$ brunch <device_codename>
```
NOTE:
If building for your device, adapt your tree to our configurations. Use this [commit](https://github.com/ProjectBlaze-Devices/device_xiaomi_onclite/commit/4a4dee0f51f21bb3c45b8b9e77639b43ae0eb556) as a reference.
---------------------------------------------------------------------------------------

# Credits:

 * [**LineageOS**](https://github.com/LineageOS)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**crDroid**](https://github.com/crdroidandroid)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**PixelExtended**](https://github.com/PixelExtended)
 * [**VoltageOS**](https://github.com/VoltageOS)
 * [**SparkROM**](https://github.com/Spark-Rom)
