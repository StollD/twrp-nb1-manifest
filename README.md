## Getting Started ##
---------------
```bash
$ repo init -u git://github.com/omnirom/android.git -b android-8.1
$ repo sync
$ . build/envsetup.sh
$ lunch omni_NB1-eng
$ make -j$(nproc --all) adbd recoveryimage
```
