# My Homelab

## What is this?

This repository contains an Ansible playbook that mirrors most of the configuration of my primary home server: an HP MicroServer Gen8 running Alpine Linux with ZFS. This server hosts Samba file shares and a number of Docker applications I use in my day-to-day life. While the Gen8 MicroServer is quite old, and mine has an unimpressive Xeon E3-1220L V2 CPU, I still love them for their form factor and style.

This playbook is not intended to be a comprehensive record of the server's configuration. It does not cover ZFS, for example. It is more so a way for me to record changes I make over time, so that I have something to refer to when I inevitably forget what I had done.

## Background

This is not the first MicroServer I have owned. I purchased one almost ten years ago - my first server - brand new for only £164.99. However, in pursuit of bigger and better things, I foolishly sold it in favor of secondhand rack mount servers, which I have owned a number of over the years. In addition to the MicroServer, I currently have two Dell PowerEdge R730s. These are excellent systems - they are highly versatile and quiet despite being rack mount. My return to the MicroServer is part of my homelab simplification journey to cut out the extraneous (Exchange Server, Active Directory, VMware, etc.) and focus on the essentials (a few Docker applications, like Immich and Actual Budget). Plus, I think the MicroServer is just plain cool.

![My HP MicroServer Gen8 and two Dell PowerEdge R730s](https://github.com/user-attachments/assets/b56c8ff5-a150-47e8-bd24-c5fa24f3f8c3)
