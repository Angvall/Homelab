# Homelab
This is a guide to my homelab and how it works

This is a wip and I named everything differently 

## Overview

Current project: writing this document and add new services


## Faust (NAS)
As of June 19th 2026 Faust is currently running on a basic truenas with no apps on it
### Specs
- CPU: Intel Core I5-7600 @ 3.50Ghz
- Memory: 24GB
- Disks
  - CT1000BX500SSD1 SSD (Boot) (1TB) (will change bootdrive later)
  - SKHynix_HFS001TEJ9X115N NVME (1TB)
  - My Passport 2627 (1TB) filler storage

## Yi Sang (ProxMox)
As of June 19th 2026 Yi Sang manages services on my network
### Specs
- CPU: Intel Core I5-9600 @ 3.1GHz
- Memory 24GB
- Disks
  - Sata 500GB (come back and edit these)
### Services
- <a href="https://jellyfin.org/">Jellyfin</a>
- <a href="https://github.com/bluestreamclub/jellyseerr">JellySeer</a>
- <a href="https://github.com/glanceapp/glance">Glance</a>
- <a href="https://immich.app/">Immich</a>
- <a href="https://github.com/passteque/gluetun">Gluetun</a>
- <a href="https://tailscale.com/">Tailscale</a>
- <a href="https://github.com/henrygd/beszel">Bezel</a>
- <a href="https://get.kiwix.org/en/">Kiwix</a>

## Meursault (Switch) 
### Cisco Catalyst 2960-X
### What I've done with it
- SSH into the switch
- Named it
- Reset password
- Configured VLans

# To Do Soon
- set up netbird
- set up grafana (for more details statistics/data)
- set up proxmox mail gateway
- rackpeek for documentation
- work on more automation/monitoring
- add images
