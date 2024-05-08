---
title: "Installing Ubuntu on a Bare metal"
date: 2024-01-23
description: "Installation of Ubuntu directly on a computer without virtualisation"
summary: "No virtualisation, direct installation on Bare Metal"
---

Bare metal is like a direct connection and in this scenario, your OS talks to the hardware without any middlemen. VM, on the other hand, is like a party hosted by another OS called the host OS. It uses a hypervisor (VMware, VirtualBox) to manage multiple virtual machines, each doing its own thing.

The Good, the Not-so-Good, and the Challenges of Bare Metal and VM

## Bare Metal Basics

Pros:

Smooth Performance: Your OS has the hardware all to itself, with no interruptions. It's all about optimal performance and reliability.

Top-Notch Security: Your OS stands alone, away from other OSs or VMs. Less drama, fewer risks.

Cons:

Not Very Flexible: Can't easily change hardware or add more resources. One OS at a time – pick your favourite.

Pricey Business: Needs its own hardware space, which can be costly. More hands-on maintenance too.

VM Vibes

Pros:

Flexible Fun: Can run on any hardware supporting the host OS and hypervisor. Mix and match OSs like a pro.

Budget-Friendly: Shares hardware resources, reducing costs. Automation magic for the win.

Cons:

Performance Bumps: Host OS and hypervisor involvement can slow things down. It's a party but with some hiccups.

Security Considerations: Exposed to host OS risks. Relying on host OS security.

Ubuntu Journey: From Windows Farewell to Fresh Start

So, you're feeling adventurous and want to switch from Windows to Ubuntu? Here's your guide to a clean slate:

Download Ubuntu: Grab the desktop version that matches your laptop's flavour (64-bit or 32-bit). [Download Ubuntu Desktop](https://ubuntu.com/download/desktop/thank-you?version=22.04.3&architecture=amd64)

Get Rufus: It's the tool that puts ISO files on USB flash drives. Free, easy, and efficient. [Download Rufus](https://rufus.ie)

USB Time: Plug in an 8GB+ USB flash drive and open Rufus.

Rufus Steps: Pick your USB, select the Ubuntu ISO file, and hit START. Let the writing commence!

Boot Up: Restart your laptop, press the special key (usually F12, F10, or ESC), and choose USB as your boot star.

Ubuntu Unveiling: Click 'Install Ubuntu,' follow the steps, and when you get to 'Installation type,' choose "Erase disk and install Ubuntu" for a full wipeout. Or get creative with "Something else" for manual partitioning.

Finish Line: Complete the installation, add your details, and voila! Reboot without the USB – Ubuntu is now running the show on your laptop.

