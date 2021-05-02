# termux-adb-dot-deb
Android Debug Bridge for Termux in a .deb package
### Installation 
- <b>Download and run the script</b></br>
```wget https://raw.githubusercontent.com/bapm394/termux-adb-dot-deb/master/install-repo ; chmod 777 ./install-repo ; ./install-repo```
- <b>And install adb</b></br>
```apt update ; apt install adb```
- <b>Make sure you install it on aarch64 or aarch (arm - arm64) architecture</b></br>
- <b>Also that you already have Termux-API installed, with which you can access the USB port you have through the termux-usb command, or you can access the IP of your target android</b></br>
### Uninstall
- <b>Run this</b></br>
```apt remove adb```
- <b>And if you regret the past just do this</b></br>
```apt install adb```

* The binaries are those of Android, (the ones that were once).
