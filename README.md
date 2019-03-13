## Getting Started ##
---------------
```bash
$ repo init --depth=1 -u git://github.com/StollD/twrp-nb1-manifest.git -b android-8.1
$ repo sync -j12
$ export ALLOW_MISSING_DEPENDENCIES=true
$ . build/envsetup.sh
$ virtualenv2 .
$ . bin/activate
$ lunch omni_NB1-eng
$ LC_ALL=C make -j$(nproc --all) adbd recoveryimage
```
