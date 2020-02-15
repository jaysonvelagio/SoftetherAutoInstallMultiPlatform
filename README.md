# Softether Auto Install Multi Platform<br />
* Softether Auto Install Script for multi platforms updated version<br />
* Softether VPN server latest version v4.27-9666-beta-2018.04.21
* Revised to last known stable version due to compilation error from their latest release
* An open source VPN project from University of Tsukuba Japan<br />
* Centos 6 or 7 x64
* Debian 8 (jessie) <b>(Not compatible for Debian 9 (stretch) x64 - compilation error)</b>
* Ubuntu 14, 15, 16 x64 <b>(Not compatible for Ubuntu 17 and 18 x64 - compilation error)</b>
# Instruction<br />
Choose your desired platform folder<br />
Download installer.sh using wget or transfer to your root directory using ftp<br /><br />

<b>Download and install the installer.sh by executing the commands below</b><br /><br />
<b>For centos and fedora</b> (copy all the text below and paste on your terminal)<br /><br />
```yum install wget -y && wget https://raw.githubusercontent.com/jaysonvelagio/SoftetherAutoInstallMultiPlatform/master/Centos/installer.sh && chmod +x installer.sh && ./installer.sh ```<br /><br /><br />


<b>For debian and ubuntu</b> (copy all the text below and paste on your terminal)<br /><br />
```wget https://raw.githubusercontent.com/jaysonvelagio/SoftetherAutoInstallMultiPlatform/master/Debian%20and%20Ubuntu/installer.sh && chmod +x installer.sh && ./installer.sh```<br /><br /><br />


# VPN server commands<br />
```/etc/init.d/vpnserver start - to start```<br />
```/etc/init.d/vpnserver restart - to restart```<br />
```/etc/init.d/vpnserver stop - to stop```<br /><br />

* vpncmd is at /usr/local/vpnserver<br /><br />

If you can't connect to your vpn server using VPN server manager. Open this ports on your firewall dashboard if you are using Google cloud, Amazon AWS, Alibaba Cloud and Digital Ocean<br />

TCP 443<br />
TCP 992<br />
TCP 1194<br />
TCP 5555<br />


For more information message me on facebook: Jayson Velagio
