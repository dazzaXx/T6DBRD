# T6(D)BRD

A USB Security Dongle Emulator for Tekken 6 and Tekken 6 Bloodline Rebellion for the Namco System 357/369 systems.

(These are for the physical systems, these aren't needed if you're just using the arcade fork of RCPS3.)

For use with Raspberry Pi Zero / Zero 2. I personally have used it with a Pi Zero 2 W, so I assume other models of Zero work too.


NOTE: The emulated USB itself comes from the Pi Zero's USB OTG port, so you will need a micro usb cable to plug into the 357/369.
Also, the Pi Zero's CANNOT be powered by the 357/369 by itself, as it just browns out and constantly reboots the Pi Zero, so you
will need to either externally power it from another source, or use a usb hub. I personally use a usb hub off amazon and it works
fine. It's also handy as 357C's only have one usb port.



Run these commands too beforehand.
```
sudo mkdir /T6BRD
cd /T6BRD

Place script in newly created folder.

sudo chmod +x T6BRD.sh
sudo ./T6BRD.sh
```

The script is an all-in-one, just run it and done.

There is also one for the standard Tekken 6. This should work fine but needs to be tested.

The commands are pretty much the same, just instead of T6BRD, it's just T6D.

```
sudo mkdir /T6D
cd /T6D

Place script in newly created folder.

sudo chmod +x T6D.sh
sudo ./T6D.sh
```
