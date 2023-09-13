---
title: "blendOS Is Really Nice"
date: 2023-09-13T22:31:00+07:00
draft: false
tags: 
    - blendOS
---
I've been using [blendOS](https://blendos.co/) for a few days now and it’s really nice. I installed the KDE/Plasma version and everything just works really well which was a welcome relief after screwing around with Guix and NixOS for weeks.
<!--more-->
The immutable file system part is a bit of a challenge in light of their under-cooked declarative system config tool (it’s still only on version 3 of a distro that only dropped this year) but once it fleshes out it will be really excellent. In the meantime, being able to install containerized packages from different distributions (Arch, Ubuntu and a half dozen others) and have them integrate seamlessly with your home directory and core operating system is really nice.

I’ve also switched from/to the following in the past couple of weeks and I’m finding all of the changes to be an improvement:

1. bash -> zsh
2. Vim -> Neovim
3. XOrg -> Wayland
4. i3 -> [Sway](https://swaywm.org/)

Wayland is a bit of an eye opener. Being able to start in KDE/Plasma, switch to a tty session, start Sway (another complete window manager) and then switch back and forth is a revelation after years of using Xorg which can only handle one instance.

