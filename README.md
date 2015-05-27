# DanmaQ

DanmaQ, pronounced as `/danmakju:/` is a small QT program to play danmaku on any screen.

## Warning

DanmaQ is still under development, documents might be outdated.

## Run Demo

### Dependencies

`danmaQ` depends on `Qt4` and `qjson`. 

For ArchLinux, run
```
yaourt -S danmaQ
```

For Ubuntu and Debian, run
```
sudo apt-get install libqjson0
```

For Fedora, run
```
sudo dnf install qjson
```

For OpenSUSE, run 
```
sudo zypper install libqjson0
```

if you use Windows, download bundled binary version from 
[releases page](https://github.com/bigeagle/danmaQ/releases/).

### Use TUNA Service

First u need to create a channel, go to http://dm.tuna.moe/ and create a channel, 
(let's use `ooxx` as the channel name and `passw0rd` as the password)

then run `danmaQ` and fill `http://dm.tuna.moe` to server, 
and your channel name (`ooxx`) and channel password (`passw0rd)`. 

then open http://dm.tuna.moe/ and click to your channel page, then post.

### Self Hosted Service

Clone https://github.com/tuna/gdanmaku-server and run `webserver.py` to start a publishing server.

### Installation

- **from source**: run `mkdir build && cd build && cmake .. && make && make install`.
- **windows binary**: https://github.com/bigeagle/danmaQ/releases/
- **Arch Linux**: [AUR](https://aur.archlinux.org/packages/danmaq-git/)

## TODO

- [x] Multi-Screen support
- [x] Chatting
- [ ] Deb package
- [ ] RPM package

## Screenshot

![](https://raw.githubusercontent.com/bigeagle/danmaQ/master/screenshots/xiaowang.png)
