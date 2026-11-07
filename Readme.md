# Homelab Infrastructure

## Hardware

- Dell OptiPlex Micro
- Intel CPU
- 16GB RAM
- 256GB SATA SSD
- 1GbE Ethernet

## Hypervisor

- Proxmox VE
- Hostname: pve01
- Management IP: 192.168.1.10

## Network

- Gateway: 192.168.1.1
- Network: 192.168.1.0/24
- DHCP: Router

## Planned Services

| Service | Type | Purpose |
|---|---|---|
| Proxmox | Bare metal | Virtualization |
| Pi-hole | LXC | DNS filtering |
| Unbound | LXC | Recursive DNS |
| Tailscale | VM | Remote access |
| Caddy | LXC | Reverse proxy |
| Immich | VM | Photo management |