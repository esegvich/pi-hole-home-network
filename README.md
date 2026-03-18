# Pi-Hole Home Network

Network-wide ad and tracker blocking using Pi-hole on a Raspberry Pi.

## Overview
- Blocks ads, trackers, and malicious domains at the DNS level
- Covers every device on the network automatically
- Configured router DHCP to assign the Pi as the primary DNS server

## Hardware
- Raspberry Pi 4 Model B
- 32GB microSD

## Setup
1. Installed Pi-hole on Raspberry Pi OS
2. Configured static IP for the Pi on the router
3. Set Pi's IP as the DNS server in router DHCP settings
4. Imported blocklists via the Pi-hole admin dashboard

## Stats
- 81,000+ domains blocked across blocklists
- Blocking ~14% of all DNS queries on the network

## Planned Expansions
- [ ] Create HTTPS admin panel for secure access
- [ ] WireGuard VPN for secure remote access to admin panel
