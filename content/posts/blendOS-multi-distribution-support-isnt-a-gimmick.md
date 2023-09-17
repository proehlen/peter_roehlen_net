---
title: "Multiple Distribution Support in blendOS is no Gimmick"
date: 2023-09-17T13:26:09+07:00
draft: false
tags:
  - blendOS
---
I initially thought the ability of [blendOS](https://blendos.co/) to run packages from multiple Linux distros might turn out to be a gimmick but I was wrong. 

<!--more-->
I generally prefer to use Arch Linux for its bleeding edge packages but I wanted get a VS Code with PowerShell environment also set up and that’s easier and more supported on an Ubuntu LTS release. Ubuntu LTS releases are usually a year or two old so they aren't something I want to use for my daily driver OS. With blendOS, I don't need to choose between one environment or the other though as the below screenshot demonstrates.

![blendOS running Arch and Ubuntu LTS](/images/blendOS-multi-distribution-example.png)

In the above, I’m running VS Code with PowerShell on Ubuntu 22 and the Haskell compiler on Arch Linux. It’s largely irrelevant[^1] to me that they are running in different containers based on different distributions since they both share the same home folder and they are both launched via icons from my main OS.

I understand that a tool called [DistroBox](https://github.com/89luca89/distrobox) is doing most of the above magic so you could probably set it up on on any OS but I don’t know yet how much extra stuff blendOS does for you on the integration side.

[^1]: If I were regularly compiling the Linux kernel or Firefox from scratch, the small containerization overhead might become relevant - I don't know - but I'm guessing that for most people it wouldn't even be noticeable. From what I understand, it is nothing like the overhead of running a VM for example.
