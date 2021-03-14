<br>First, download distro and write to USB/DVD
<br>https://download.freebsd.org/ftp/releases/amd64/amd64/ISO-IMAGES/
<br>
<br>Second, using installer we install FreeBSD with dns:
<br>tendawifi.com
<br>8.8.8.8
<br>
<br>Enable sshd and moused
<br>Set time to UTC
<br>Create user "zeus" and reboot
<br>
<br>Second step:
<br>fetch https://github.com/bsdver/os/archive/main.zip
<br>unzip main.zip
<br>cd os-main
<br>
<br>Add permission:
<br>chmod +x install
<br>
<br>Finally, run it:
<br>./install
<br>
<br>On other machine connect:
<br>ssh zeus@192.168.43.10
