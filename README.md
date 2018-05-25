# Softether Auto Install Multi Platform<br />
* Softether Auto Install Script for multi platforms updated version<br />
* Softether VPN server latest version 4.27-9666-beta-2018.04.21
* An open source VPN project from University of Tsukuba Japan<br />
* Centos 6 or 7 x64
* Debian 8 (jessie) (Debian 9 (stretch) x64 compatibility issue - compilation error)
* Ubuntu 14, 15, 16, 17 x64
# Instruction<br />
Choose your desired platform folder<br />
Download installer.sh using wget or transfer to your root directory using ftp<br /><br />

* Install wget first For centos and fedora<br />
$ sudo yum install wget -y<br /><br />

Download and install the installer.sh by executing the commands below<br />
* For centos and fedora<br />
$ wget https://raw.githubusercontent.com/jaysonvelagio/SoftetherAutoInstallMultiPlatform/master/Centos/installer.sh<br />
$ chmod +x installer.sh<br />
$ ./install.sh<br />
Enter 1 three times to proceed on compilation<br /><br />

* For debian and ubuntu<br />
$ wget https://raw.githubusercontent.com/jaysonvelagio/SoftetherAutoInstallMultiPlatform/master/Debian%20and%20Ubuntu/installer.sh<br />
$ chmod +x installer.sh<br />
$ ./install.sh<br />
Enter 1 three times to proceed on compilation<br /><br />

# VPN server commands<br />
$ /etc/init.d/vpnserver start - to start<br />
$ /etc/init.d/vpnserver restart - to restart<br />
$ /etc/init.d/vpnserver stop - to stop<br /><br />

* vpncmd is at /usr/local/vpnserver<br /><br />

If you can't connect to your vpn server using VPN server manager. Open this ports on your firewall dashboard if you are using Google cloud, Amazon AWS, Alibaba Cloud and Digital Ocean<br /><br />

TCP 443
TCP 992
TCP 1194
TCP 5555

