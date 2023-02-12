# cnc

# Установка отсюда
https://forum.linuxcnc.org/9-installing-linuxcnc/46381-installing-linuxcnc-2-9-or-master-on-linux-mint-21?start=0

#



==================
RT core
==================

http://ftp.debian.org/debian/pool/main/l/linux-signed-amd64/
===>>>>>
http://ftp.debian.org/debian/pool/main/l/linux-signed-amd64/linux-image-rt-amd64_6.1.11-1_amd64.deb
http://ftp.debian.org/debian/pool/main/l/linux-signed-amd64/linux-image-6.1.0-4-rt-amd64_6.1.11-1_amd64.deb

sudo dpkg -i linux-image-*


==================
LinuxCNC 
==================

# clone the repo and then ==>
debian/configure no-docs

# install all the packagesh that would be needed
dpkg-checkbuilddeps

debuild -uc -us


