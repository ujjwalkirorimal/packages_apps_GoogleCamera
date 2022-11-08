# Google Camera 8.1 by BSG

Source - https://www.celsoazevedo.com/files/android/google-camera/dev-bsg/f/dl88/

Variant - MGC_8.1.101_A9_GV2b_MGC.apk (com.android.mgc)

## How To Build

* Clone This Repository to "ROM_DIR/packages/apps/GoogleCamera"
* Add following defination in your device makefile
``` 
# GoogleCamera
$(call inherit-product-if-exists, packages/apps/GoogleCamera/gcam.mk)
```
* Now you can build normally.
