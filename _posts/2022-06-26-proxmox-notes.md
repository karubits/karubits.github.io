---
title: Proxmox Notes
date: 2022-06-25 05:00:00 -500
categories: [proxmox,virtualization]
tags: [proxmox,cli,virtualization,hypervisor]     # TAG names should always be lowercase
---

# Command line

Creating a new virutal machine

`qm create 8000 --memory 2048 --core 2 --name debian10template --net0 virtio,bridge=vmbr0`

Create a clone

`qm clone 8000 135 --name debian10-1 --full`

