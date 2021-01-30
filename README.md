# termux-adb-dot-deb
Android Debug Bridge for Termux in a .deb package
### Installation 
- <b>Download and run the script</b></br>
```wget https://raw.githubusercontent.com/bapm394/termux-adb-dot-deb/main/install-repo ; chmod 777 ./install-repo ; ./install-repo```
- <b>And install adb</b></br>
```apt update ; apt install adb```
- <b>Make sure you install it on aarch64 or aarch (arm - arm64) architecture</b></br>
- <b>You need to have php installed</b></b>
- <b>Also that you already have Termux-API installed, with which you can access the USB port you have through the termux-usb command, or you can access the IP of your target android</b></br>
### Uninstall
- <b>Run this</b></br>
```apt remove adb```
- <b>And if you regret the past just do this</b></br>
```apt install adb```

* Chris Renshaw created the binaries, [here the link to xda](https://forum.xda-developers.com/t/tools-zips-scripts-osm0sis-odds-and-ends-multiple-devices-platforms.2239421/) and [Github](https://github.com/osm0sis)
