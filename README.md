

Building TWRP for Xiaomi Mi Note 10

Working :

ADB

Decryption userdata

Screen brightness settings

Correct screenshot color

MTP.

To compile

build/envsetup.sh

export ALLOW_MISSING_DEPENDENCIES=true

lunch omni_tucana-eng

make -jX recoveryimage

