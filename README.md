CavvohOS
===========

Getting started
---------------

To get started with Android/CavvohOS, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository using the CavvohOS trees, use a command like this:
```
repo init -u https://github.com/Cavvoh/manifest.git -b A14 --git-lfs
```
Then to sync up:
```
repo sync
```

# Build

- Set up the build environment
```bash
. build/envsetup.sh
```

- Lunch a target
```bash
lunch lineage_codename-user
```

- To start compiling
```bash
m cavvoh
```
