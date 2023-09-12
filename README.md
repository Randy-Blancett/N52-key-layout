# N52-key-layout
This is the layout for Belkin nostromo SpeedPad n52

# Install
Copy Files ./install.sh

Find the keyboard you want to replace
``` shell
xinput list
```

replace keyboard
```shell
setxkbmap -device 13 -config ./n52-config.keyboard -v
```