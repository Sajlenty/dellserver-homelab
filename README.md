# Dellserver Homelab

A personal self-hosted environment built on a Dell Latitude 5400, used to develop practical skills in Linux system administration, Docker, networking, monitoring, and automation.

## Infrastructure

| Component | Specification |
|---|---|
| Hardware | Dell Latitude 5400 |
| Operating System | Ubuntu 24.04.3 LTS |
| Kernel | Linux 6.8.0-87-generic |
| Architecture | x86-64 |
| Memory | 8 GB RAM |
| Storage | 256 GB NVMe SSD |
| Container Runtime | Docker Engine 29.8.0 |
| Orchestration | Docker Compose v5.5.1 |

## Self-Hosted Services

| Service | Purpose |
|---|---|
| Homepage | Centralized dashboard |
| Uptime Kuma | Service availability monitoring |
| Portainer | Container management |
| Home Assistant | Home automation |
| Lodestone | Game server management |
| Rockstar Newswire Tracker | News tracking and notifications |
| Tautulli | Plex activity monitoring |
| Immich | Photo management |
| Plex | Media server |
| Minecraft | Game server |

Some services are currently stopped or undergoing maintenance.

## Repository Structure

- `docs/` — Infrastructure documentation and troubleshooting
- `docker/` — Sanitized Docker Compose files and application configurations
- `scripts/` — Maintenance and automation scripts

## Roadmap

- [ ] Document existing infrastructure and services
- [ ] Organize Docker Compose configurations
- [ ] Document container networking
- [ ] Review monitoring and alerts
- [ ] Implement backup and recovery procedures
- [ ] Explore Ansible for configuration management

## Security

This repository contains documentation and sanitized configuration examples. Credentials, tokens, API keys, private keys, and persistent application data must not be committed.

## Status

Work in progress. Configurations and documentation are being added incrementally.
