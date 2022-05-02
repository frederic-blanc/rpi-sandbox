# use arm64 ubuntu
The 64bits image can be found here: https://ubuntu.com/download/raspberry-pi

You can use [20.04 LTS version](https://cdimage.ubuntu.com/releases/20.04/release/ubuntu-20.04-preinstalled-server-arm64+raspi.img.xz) or [22.04 LTS version](https://cdimage.ubuntu.com/releases/22.04/release/ubuntu-22.04-preinstalled-server-arm64+raspi.img.xz) one.

To manage ip setting and an ubuntu account not expired (as well as a non update kernel at boot first, this will be managed by the ansible install), we use cloud-init files. 

Template files can be found in the cloud-init folder and it must copied in the /boot partition just after the image burn. Just Change your targeted IP address in the network-config file.

à tester :
https://discourse.ubuntubudgie.org/t/ubuntu-budgie-plans-for-raspberry-pi/4310/23?page=2
