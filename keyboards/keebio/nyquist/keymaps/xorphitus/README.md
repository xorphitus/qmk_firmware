# xorphitus's Nyquist layout

## pre-installation

```bash
$ sudo pacman -S avr-gcc arduino-avr-core
```

## installation

```bash
$ git clone git@github.com:xorphitus/qmk_firmware.git
$ cd qmk_firmware
$ make git-submodule
$ make nyquist/rev1:xorphitus
$ sudo make nyquist/rev1:xorphitus:avrdude
```
