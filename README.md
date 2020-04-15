This image contents is :

- arm-gcc-none-eabi compiler
- mbed cli (and packages to need for working mbed cli)

Using image, it's procedure for that you get start to development by mbed cli :

```
# mkdir example
# cd example
# mbed import http://os.mbed.com/teams/ST/code/mbed-os-example-blinky/
# cd mbed-os-example-blinky
# mbed compile -t {YOUR_TARGET_BOARD}
```

If complete compile, then you can get a image file at "./BUILD/{YOUR_TARGET_BOARD}/mbed-os-example-blinky.bin"