# vimba-sdk-raspberrypi

Setting up Raspberry Pi (Recommend Raspberry Pi 4)
===============
1. Install [Ubuntu Desktop 21.04](https://ubuntu.com/download/raspberry-pi) on a Raspberry Pi
  - Follow this [instruction](https://projects.raspberrypi.org/en/projects/raspberry-pi-setting-up)

Setting up Vimba SDK
===============
1. Download Vimba SDK
  - Select "Downloads for ARMv8 64-bit" at [Vimba SDK](https://www.alliedvision.com/en/products/software.html)

2. Installing Vimba SDK
  Vimba comes as a tarball. To install it:
  1. Uncompress the archive to a directory you have writing privileges for, such as /opt:
              tar -xzf ./Vimba.tgz -C /opt
    In this directory, Vimba will be installed in its own folder. In this document, we refer to this path as [InstallDir].
  2. GigE camera users: Go to [InstallDir]/Vimba_x_x/VimbaGigETL. USB camera users: Go to [InstallDir]/Vimba_x_x/VimbaUSBTL.
  3. Execute the shell script Install.sh with root privileges (for example, sudo ./Install.sh or su -c.Install.sh).
    If you use GigE and USB cameras, perform this step for both TLs (transport layers).
