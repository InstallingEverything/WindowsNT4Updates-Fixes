# Drivers

A tested collection of Windows NT 4.0 drivers for virtual machines, with a focus on VMware Workstation compatibility.

## Overview

These drivers are selected to improve USB, audio, and video support in NT 4.0 VMs.

## Compatibility

- VMware Workstation: fully tested and supported, including the VMware SVGA II video driver
- PCem and VirtualBox: USB and audio drivers are known to work
- VMware video driver: VMware Workstation only

## Included Drivers

1. Inside Out Networks USB Peripheral Drivers
2. Sound Blaster AudioPCI (Drivers only) Web Update
3. VMware SVGA II from VMware Tools `3.5.0-110268`

## Notes

- Install the VMware SVGA II driver only on VMware Workstation hosts.
- USB and audio drivers may work in other virtualization platforms, but were primarily validated in VMware.
- Always test driver installs in a snapshot or disposable VM first. 