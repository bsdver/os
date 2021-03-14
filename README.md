First, download distro and write to USB/DVD
https://download.freebsd.org/ftp/releases/amd64/amd64/ISO-IMAGES/

Second, using installer we install FreeBSD with dns:
tendawifi.com
8.8.8.8

Set time to UTC.
Create user "zeus" and reboot

Second step:
fetch https://github.com/bsdver/os/archive/main.zip
unzip main.zip
cd os-main

Add permission:
chmod +x install

Finally, run it:
./install

On other machine connect:
ssh zeus@192.168.43.10
