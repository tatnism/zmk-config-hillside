# Hillside ZMK firmware

[![Build](https://github.com/mmccoyd/zmk-config/actions/workflows/build.yml/badge.svg)](https://github.com/mmccoyd/zmk-config/actions/workflows/build.yml)

This repo provides interim [ZMK](https://zmk.dev/docs) firmware access
 while the [Hillside](https://github.com/mmccoyd/hillside) keyboard is integrated into ZMK.
Hillside 48 is a split ergonomic keyboard with 3x6+4+2 choc-spaced keys.

To build the firmware from this repo:
- Fork this repo on GitHub
- Clone your fork locally
- Make some change to this README to trigger a build.
- Push that change to your fork on GitHub
- That change will trigger a build action
- Look in the actions tab for the build triggered by that change
- Wait for the build to finish
- Click on the build link
- Download the artifact file with the firmware
- See [Installing The Firmware](https://zmk.dev/docs/user-setup#installing-the-firmware)
  for more details from there.

Once your board works with the default firmware,
  you can modify the keymap.
Your copy of the default Hillside 48 keymap is in
  ./config/hillside48.keymap.
Modify that as needed.
If you want to enable features,
  modify ./config/hillside48.conf.
The Hillside 48 shield definition *should not* need to be modified and is in ./config/boards/shields/hillside48.
The readme there has more information.

Once Hillside is integrated into ZMK,
  it is best to create a zmk-config repo based off of the ZMK
  [install instructions](https://zmk.dev/docs/user-setup)
  instead of using a clone of this repo, as it may change or be removed.


Initial Build
