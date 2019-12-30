# Notes Doc

## Building

```
./util/docker_build.sh massdrop/ctrl:endgame
```


## Download/Install
Remember to put the keyboard into flash mode by using `Fn + B`. Also use on-screen keyboard to help run download since you will not be able to use your keyboard while it's in flash mode.

```
sudo mdloader_linux --download massdrop_ctrl_endgame.bin --restart -p /dev/ttyACM0
```
