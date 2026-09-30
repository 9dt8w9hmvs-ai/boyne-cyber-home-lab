# Boyne Cyber Home Lab

A home infrastructure and cybersecurity lab built around Proxmox VE.

## Goals

- Build an always-on home infrastructure server
- Learn Proxmox and Linux administration
- Implement secure remote management
- Deploy internal DNS and DNS filtering
- Build monitoring and SIEM capability
- Develop SOC and detection engineering skills
- Document troubleshooting and design decisions

## Current Services

- PVE01 - Proxmox VE hypervisor
- DNS01 - Debian LXC running AdGuard Home
- Tailscale - secure remote administration

## Current Status

Foundation stage complete.
 
Current work includes:
- Proxmox
- DNS01 / AdGuard
- Tailscale remote access
- reliability testing
- documentation

## Planned

- MGMT01
- MON01
- backups
- SOC01 / Wazuh
- Sysmon telemetry
- detection engineering
- network monitoring

## Documentation

1. [Project Overview](docs/01-project-overview.md)
2. [Hardware and Proxmox](docs/02-hardware-and-proxmox.md)
3. [Storage Design](docs/03-storage-design.md)
4. [Temporary Networking](docs/04-temporary-networking.md)
5. [DNS01 and AdGuard](docs/05-dns01-adguard.md)

 [← Back to main project](../README.md)
7. [Tailscale Remote Access](docs/06-tailscale-remote-access.md)
8. [Troubleshooting](docs/07-troubleshooting.md)
9. [Reliability and Health Checks](docs/08-reliability-and-health-checks.md)
10. [Future Roadmap](docs/09-future-roadmap.md)
