# Project-Zephyrus

CodeLinaro based Project-Zephyrus is a minimal custom Android ROM focused on UI/UX and performance, with a touch of security, privacy and minimal set of features.

## Getting source code

First, make sure you have an [Android build environment](https://source.android.com/setup/build/initializing) and the [repo tool](https://source.android.com/setup/build/downloading) set up. After that, run the following commands:

Initialize local repository:
```
repo init -u https://github.com/Project-Zephyrus-CAF/android_manifest -b tm
```
Alternateively, shallow clone everything to save a lot of space,
```
repo init --depth=1 -u https://github.com/Project-Zephyrus-CAF/android_manifest -b tm
```

Then sync:
```
repo sync
```

Or to save time and space (Not Infinity Stones),
```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

This is a large download that will take approximately 100 GB of disk space, so plan accordingly.

## Building

You will need to create a device tree to build this ROM for your device. Below are some examples that have been customized to work well with Project-Zephyrus.

Good luck!
