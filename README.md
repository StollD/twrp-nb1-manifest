## Getting Started ##
---------------
```bash
$ repo init -u git://github.com/StollD/twrp-nb1-manifest.git -b android-8.1
$ repo sync
$ . build/envsetup.sh
$ virtualenv2 .
$ . bin/activate
$ lunch omni_NB1-eng
$ make -j$(nproc --all) adbd recoveryimage
```
