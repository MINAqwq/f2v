# F2V

This is hacked example code from ffmpeg. It takes a output destination and a input file. It will guess the encoding from the file suffix.

## Build
```sh
cc f2v.c -lavutil -lavformat -lavcodec -lswresample -lswscale -lm -o f2v
```

## Example
```sh
f2v kernel.raw /boot/vmlinuz-linux
```
