# Repository for Lily58

Contains scripts and Github action to compile firmware to be installed on the Lily58 keyboard.

[Instructions for how to edit and update the firmware](https://docs.typeractive.xyz/build-guides/lily58-wireless/firmware)

Edit the lily58.keymap file to your liking. You can find this file in the config folder.
For documentation on customizing your keymap, check out the ZMK documentation.
[Alternatively, use the visual online keymap editor by Nick Coutsos](https://nickcoutsos.github.io/keymap-editor/)

## Installing firmware

 1. Plug in your nice!nano to your computer.
 2. Enter the bootloader by double-tapping the reset button. (You can skip this if you haven't flashed the nice!nano before)
 3. Drag and drop the .uf2 file onto the NICENANO drive or copy it with your terminal.
 4. After flashing is complete, the drive will disappear and the nice!nano will reboot. Your computer may report an error when transferring the file, you can likely ignore this.
 5. If you haven't yet, you can turn the power switch on by pushing it up on the side of the keyboard.

