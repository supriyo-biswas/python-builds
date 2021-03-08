# python-builds

This project provides self-contained builds of Python for Linux which should
work on any glibc based Linux distribution.

# Installation

* Choose a release of your choice from the [releases](https://github.com/supriyo-biswas/python-builds/releases) page.
* Install it in the following manner:

```bash
wget https://github.com/supriyo-biswas/python-builds/releases/download/X.Y.Z/python-X.Y.Z-PLATFORM-ARCH.tar.bz2
sudo mkdir -p /opt/python3
sudo tar -C /opt/python3 -xf python-X.Y.Z-PLATFORM-ARCH.tar.bz2
sudo rm -rf /opt/python3/etc/ssl/certs
sudo ln -s /etc/ssl/certs/ /opt/python3/etc/ssl/certs
```
