# SoftetherAutoInstallMultiPlatform
#Softether Auto Install Script for multi platforms
#An open source VPN project from University of Tsukuba Japan

#Instruction

#Choose your desired platform folder
#Download installer.sh using wget or transfer to your root directory using ftp

#Install wget first

#For centos and fedora
sudo yum install wget -y

#For debian and ubuntu
apt-get install wget -y

#Download and install the installer.sh by executing the commands below

#For centos and fedora
wget https://raw.githubusercontent.com/jaysonvelagio/SoftetherAutoInstallMultiPlatform/master/Centos/installer.sh
chmod +x installer.sh
./install.sh

#For debian and ubuntu
UPDATING THE SCRIPT
