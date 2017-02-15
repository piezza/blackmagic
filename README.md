Black Magic Probe firmware for ST-Link bootloader.

`dist` contains precompiled and encrypted firmware image.

build:
`make PROBE_HOST=stlink-bootloader`

encrypt:
`java -jar st_decrypt.jar blackmagic.bin f2_x.bin`
