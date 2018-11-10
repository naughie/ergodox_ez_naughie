# About

This provides my own keymap for [Ergodox EZ](https://ergodox-ez.com/).
For more details, see the [official repository](https://github.com/kei-s/qmk_firmware) and the [documentation](https://docs.qmk.fm/#/).

# Prerequisites

## For mac
```
$ brew tap osx-cross/avr
$ brew tap PX4/homebrew-px4
$ brew install avr-gcc
$ brew install dfu-programmer
$ brew install dfu-util
$ brew install gcc-arm-none-eabi
$ brew install avrdude
```

# Compile

```
$ git clone https://github.com/kei-s/qmk_firmware.git
$ cd qmk_firmware
$ git clone https://github.com/naughie/ergodox_ez_naughie.git keyboards/ergodox_ez/keymaps/naughie
$ make ergodox_ez:naughie
```

