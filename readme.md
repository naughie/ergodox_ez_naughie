# About

This provides my own keymap for [Ergodox EZ](https://ergodox-ez.com/).
For more details, see the [official repository](https://github.com/kei-s/qmk_firmware).

# For mac

## Prerequisites

```
$ brew tap osx-cross/avr PX4/homebrew-px4
$ brew install avr-gcc@7 dfu-programmer dfu-util gcc-arm-none-eabi avrdude
```

## Compile

```
$ git clone https://github.com/kei-s/qmk_firmware.git
$ cd qmk_firmware/keyboards/ergodox_ez
$ git clone https://github.com/naughie/ergodox_ez_naughie.git keymaps/naughie
$ make KEYMAP=naughie
```

