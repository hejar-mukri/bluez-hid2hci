# bluez-hid2hci
For laptops to recognize the bluetooth device in Void Linux:

Bluez's dirvers itself wasn't enough for my laptop to recognize the bluetooth device. I discovered that I missed the "bluez-hid2hci" drivers 
that is not available on Void Linux repositories. My source packages are Cent-OS and Fedora's "rpm" packages from their repositories. Firstly 
I converted them to "deb" packages via "alien" in DebianOS; then to "xbps" via the "xdeb" app in Void Linux.

The drivers are inside the "binpkgs" folders. Both of them working on my laptop. You can use either one that are from different versions.
