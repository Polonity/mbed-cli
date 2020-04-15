This image contents is :

- arm-gcc-none-eabi compiler
- mbed cli (and packages to need for working mbed cli)

## Quick Start

1. Install visual studio code.
1. Install Remote Development visual studio code extention.
1. Open the root directory of this git repogitory with visual studio code.
1. visual studio code notify you "Folder contains a dev container configuration file. Reopen folder to develop in a container". You ask "Reopen in Container"

Your container is opened.

## Example build image with mbed-cli 

You get start to development by mbed cli is:

```
# mkdir example
# cd example
# mbed import http://os.mbed.com/teams/ST/code/mbed-os-example-blinky/
# cd mbed-os-example-blinky
# mbed compile -t {YOUR_TARGET_BOARD}
```

If complete compile, then you can get a image file at "./BUILD/{YOUR_TARGET_BOARD}/mbed-os-example-blinky.bin"
