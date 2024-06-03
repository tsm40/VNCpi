# VNCpi

Below is the workflow for setting up a Virtual Network Computing (VNC) desktop for Raspberry Pi 4B running Debian.

You will need the following software on your Windows machine:

1. [PuTTY](https://putty.org/) - SSH and telnet client
2. [VNC Viewer](https://www.realvnc.com/en/connect/download/viewer/) - remote access client

In order to set up the SSH connection for the very first time, the Pi must be connected to the same WiFi. This can be accomplished by including a file named "wpa_supplicant.conf" in the boot partition on the Pi's SD card after creating a fresh Raspbian image. An example file is included in this repository.

## PuTTY Setup

1. The host name should be set to raspberrypi.local and the port should be 22 as default. The connection type should be SSH.
2. UNFINISHED

## VNC Server Setup

UNFINISHED

vncserver-virtual :1 -geometry 1920x1080 -depth 24

## VNC Viewer Setup

In VNC Viewer, enter the VNC Server address that is output from the Pi terminal, including port number.
