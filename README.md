# Homelab
This is a guide to my homelab and how it works

This page is a wip

## Overview

Currently working on:
- writing this document
- adding new services onto the homelab
- Set up Proxmox Mail Gateway


## Faust (NAS)
As of June 19th 2026 Faust is currently running on a Truenas Community Edition with no apps on it
### Specs
- CPU: Intel Core I5-7600 @ 3.50Ghz
- Memory: 24GB
- Disks
  - Toshiba HDEPF12NAA51 (4TB) (3)
  - CT1000BX500SSD1 SSD (Boot) (1TB) (1)
  - My Passport 2627 (1TB) filler storage (1)

## Yi Sang (ProxMox)
As of June 19th 2026 Yi Sang manages services on my network and is running on ProxMox Virtual Enviroment
### Specs
- CPU: Intel Core I5-9600 @ 3.1GHz
- Memory 24GB
- Disks
  - Sata 500GB WD
### Services
- <a href="https://jellyfin.org/">Jellyfin</a>
- <a href="https://github.com/bluestreamclub/jellyseerr">JellySeer</a>
- <a href="https://github.com/glanceapp/glance">Glance</a>
- <a href="https://immich.app/">Immich</a>
- <a href="https://github.com/passteque/gluetun">Gluetun</a>
- <a href="https://tailscale.com/">Tailscale</a>
- <a href="https://github.com/henrygd/beszel">Bezel</a>
- <a href="https://git.lolcat.ca/lolcat/4get">4get</a>
- <a href="https://github.com/qdm12/deunhealth">deunhealth</a>

## Meursault (Switch) 
### Cisco Catalyst 2960-X
### What I've done with it
- SSH into the switch
- Named it
- Reset password
- Configured VLans

# To Do Soon
- set up netbird (self hosted)
- set up grafana (for more details statistics/data)
- set up matrix
- set up proxmox mail gateway
- rackpeek for documentation
- work on more automation/monitoring
- add images to the github
