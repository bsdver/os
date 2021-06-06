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
<br><code>fetch https://github.com/bsdver/so/archive/main.zip</code>
<br><code>unzip main.zip</code>
<br><code>cd so-main</code>
<br>
<br>Add permission:
<br><code>chmod +x install</code>
<br>
<br>Finally, run it:
<br><code>./install</code>
<br>
<br>On other machine connect:
<br><code>ssh zeus@192.168.43.10</code>
<br>
<br>Run OneDrive
<br><code>onedrive</code>
<br>Run Google Drive
<br><code>drive init /home/ftp/</code>
<br><code>drive init /home/gdrive/</code>
<br>Run Mega
<br><code>megaget --bsd bsd@gmail.com --password 00 --path . /Root/bsd/bsd.tar.gz</code>
