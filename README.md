# Kickstart Linux
Our Linux starter-kit repository contains Vagrant VM configurations and Shell scripts required to build, automate, and manage virtual machines on Linux, Windows, and Mac host machines.

## Supported Linux Distributions
The repository supports the following Linux distributions:
+ Alma Linux 8 and 9
+ Amazon Linux 2
+ CentOS 7
+ Rocky Linux 8 and 9
+ Ubuntu 18.04 and 22.04

## Supported Platforms
This repository is compatible with the following operating systems:

+ macOS
+ Windows
+ Linux

## Prerequisites
Before you begin, ensure that you have the following prerequisites installed on your system:
 
> [!NOTE]
Make sure to disable Secure Boot from your machine BIOS settings. If there is a Virtualization Technologies option available on BIOS settings, then please enable it to avoid unwanted issues when building VMs.

1. **VirtualBox** (for all platforms)
  - Linux Ubuntu: [How to install VirtualBox on Linux Ubuntu host machine?](https://sloopstash.zohodesk.com/portal/en/kb/articles/how-to-install-virtualbox-on-linux-ubuntu-18-04-desktop-machine)
  - Windows 10/11: [How to install VirtualBox on Windows host machine?](https://sloopstash.zohodesk.com/portal/en/kb/articles/how-to-install-virtualbox-on-windows-10-11-desktop-machine)
  - Mac: [How to install VirtualBox on Mac host machine?](https://sloopstash.zohodesk.com/portal/en/kb/articles/how-to-install-virtualbox-on-mac-desktop-machine)

2. **Vagrant** (for all platforms)
  - Linux Ubuntu: [How to install Vagrant on Linux host machine?](https://sloopstash.zohodesk.com/portal/en/kb/articles/how-to-install-vagrant-on-linux-ubuntu-18-04-desktop-machine)
  - Windows 10/11: [How to install Vagrant on Windows host machine?](https://sloopstash.zohodesk.com/portal/en/kb/articles/how-to-install-vagrant-on-windows-10-11-desktop-machine)
  - Mac: [How to install Vagrant on Mac host machine?](https://sloopstash.zohodesk.com/portal/en/kb/articles/how-to-install-vagrant-on-mac-desktop-machine)

3. **Git Bash** (for only Windows)
  - Windows 10/11: [How to install and configure Git Bash on Windows host machine?](https://sloopstash.zohodesk.com/portal/en/kb/articles/how-to-install-configure-git-bash-on-windows-10-11-desktop-machine)

## Getting Started

### Download Starter-kits from GitHub

```
# Download Linux starter-kit from GitHub to local filesystem path.
$ git clone https://github.com/your-username/kickstart-linux.git

# Switch to Linux starter-kit directory.
$ cd kickstart-linux

```

To build Ubuntu 18.04, use the following steps: 

```
# Boot Linux Ubuntu 18.04 VM using Vagrant.
$ VAGRANT_CWD=./vagrant/ubuntu-18-04/virtualbox/amd64/server vagrant up
```
```
# SSH to Linux Ubuntu 18.04 VM using Vagrant.
$ VAGRANT_CWD=./vagrant/ubuntu-18-04/virtualbox/amd64/server vagrant ssh
```
```
# Exit from Linux Ubuntu 18.04 VM.
$ exit
```
```
# Halt Linux Ubuntu 18.04 VM using Vagrant.
$ VAGRANT_CWD=./vagrant/ubuntu-18-04/virtualbox/amd64/server vagrant halt
```

Similarly, you can build Alma Linux 8 and 9, Amazon Linux 2, CentOS 7, Rocky Linux 8 and 9, and Ubuntu 22.04 server VMs.For more detailed documentation, please visit the [Kickstart-Linux Wiki](https://github.com/sloopstash/kickstart-linux/wiki) on our GitHub repository. The wiki provides additional information, troubleshooting guides, and useful tips to enhance your experience with the Kickstart-Linux Repository.
# Contributing
We welcome contributions! If you find a bug, have a feature request, or want to contribute in any way, please [create an issue](https://github.com/sloopstash/kickstart-linux/issues) or submit a [pull request](https://github.com/sloopstash/kickstart-linux/pulls).

# License
Distributed under the MIT License. See [LICENSE](https://github.com/sloopstash/kickstart-linux/blob/master/LICENSE) for more information.

# Contact
Sloopstash - support[@]sloopstash[.]com


