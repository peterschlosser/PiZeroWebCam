# PiZeroWebCam
Pi Zero Stretch Setup Repo

201809140048 using a startup wpa_supplicant.conf we have headless wifi setup and ssh enabled.  connect ssh with DHCP IP address. initial login as pi:raspberry. add static IP using: sudo nano /etc/dhcpcd.conf. sudo raspi-config Boot Options = GUI Desktop No Login.  Interfacing Options = Enable Camera + VNC. Reboot.

201809140130 login gui desktop, complete raspian setup using wizard, but no updates. Reboot.

20180914 0150 gui praspi-config set hostname: planck, disable splash screen. Reboot.




