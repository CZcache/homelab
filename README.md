# Homelab: Infrastructure Playground

**Status:** Running / Build in Progress 
**Goal:** To learn networking and infrastructure and gain useful servcies in the process

## Quick Overview for Recruiters
- **Purpose:** Media Server, Reverse Proxy, VPN
- **Skills demonstrated:** Linux, Docker, Reverse Proxy
- **Time invested:** ~8 months, ~4 hours/week

- **Hypervisor:** Currently N/A | migrating to Proxmox
- **Firewall/Router:** Xfinity XB7
- **Core services:** WireGuard (VPN), Jellyfin (Media), NGINX (Reverse Proxy), VaultWarden (PW Manager)

## Hardware
| Component | Model | Why this choice? |
|-----------|-------|------------------|
| Server | HP ProDesk 600 G3 | Cheap, Room for expansion |
| Storage | 2TB HDD + 500GB NVME | SSD for boot, HHD becuase prices are out of control|

## Key Projects
1. **Discovering Reverse Proxy**  
   > After months of routing all traffic through Cloudflare Tunnels, I learned subdomain resolution could be handeled by a Reverse Proxy instead of dozens of       individual tunnels

## What I'm currently learning
- Wireguard VPN (stuck on portforwarding at the moment)
- 24-track.com (My website)

## What I would do differently
- Using casaOS on bare metal insead of a hypervisor (This is in progress to be resolved)

## Repo Contents
- `/configs` – Redacted production configs (Coming Soon™)
- `/docs` – Deep dives on architecture and decisions (Coming Soon™)
- `/scripts` – Automation I wrote (Coming Soon™)

## Cost Tracking
- Inital Setup: $260
- Monthly Power: $(?)
- Monthly Cloud: $2

---
**Want to chat about this?** [LinkedIn](https://www.linkedin.com/in/cole-zander/) | [My Website](24-track.com)
