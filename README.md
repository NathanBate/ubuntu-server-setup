# My Ubuntu Server Setup Guide

## Install Parallels Tools

Make sure to disconnect the install CD. Shutdown the server and then go to the configuration settings for the VM 
and the sharing folders with your mac. Start the VM and then, go to the "Actions" Parallels Menu and choose "Install Parallels Tools".

Next, you should be able to mount the CDROM:

```
sudo mount /dev/cdrom /cdrom
```

Then, install the tools

```
cd /cdrom
sudo ./install
```

Restart the VM and then you should be able to see your mac folers mounted at `/media/psf`

## gh

### Install & Login

```
sudo apt update
sudo apt install gh
gh auth login
```

### Commands


