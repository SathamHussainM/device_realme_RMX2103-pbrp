TWRP Device configuration for Realme 7i
=============================================

![noah](https://github.com/Wave-Project/stuff/raw/main/devices/noah-wave.png)


###### How to compile

```sh
. build/envsetup.sh
export LC_ALL=C
lunch omni_noah-eng
mka -jX clobber && mka -jX recoveryimage
```
Note: 'X' in `mka -jX recoveryimage` is the number of cores your processor has.
For example, a quad-core processor would have `mka -j4 recoveryimage` as the command.
