# Description: VirtualBox Administration on Ubuntu

### Install Oracle VirtualBox
```
sudo sh -c 'echo ""deb http://download.virtualbox.org/virtualbox/debian trusty contrib"" >> /etc/apt/sources.list'
wget -q http://download.virtualbox.org/virtualbox/debian/oracle_vbox.asc -O- | sudo apt-key add -
sudo apt-get update
sudo apt-get install virtualbox-4.3
```
