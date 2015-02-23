# Vagrant project  Rootkit Hunter [![rkhunter](https://github.com/Inuits/vagrant-rkhunter/blob/master/docs/Rkhunter.jpg)](http://rkhunter.sourceforge.net)
[![Inuits](https://pbs.twimg.com/profile_images/2632907428/49cdc6bf20e6dfde2d8f75b1a06e2dbd_normal.png)](https://inuits.eu)

## Vagrant Up

* **git clone https://github.com/Inuits/vagrant-rkhunter.git**
* **cd vagrant-rkhunter/**
* **git submodule update --init**
* **vagrant up**

##Documentation

* **Documentation you can find [here](https://github.com/thbe/puppet-rkhunter/blob/master/README.md)** or [here](docs/README.md)

##Try Rkhunter

* **vagrant ssh**
* **sudo su -**
* **rkhunter --propupd**
* **rkhunter --propupd --pkgmgr RPM**
* **rkhunter --check**

##Extra

* **rkhunter --help**: for more info.
* **tail -f /var/log/rkhunter/rkhunter.log**: log file
* **vi /etc/rkhunter.conf**: config file Rkhunter
