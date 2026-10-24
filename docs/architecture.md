# Infrastructure Architecture

## Overview

Dellserver is a personal homelab running Ubuntu Server on repurposed Dell laptop hardware.

The environment hosts multiple self-managed applications using Docker containers, with Docker Compose used for configuration and deployment of many services.

## Hardware

| Component | Specification |
|---|---|
| Model | Dell Latitude 5400 |
| Architecture | x86-64 |
| RAM | 8 GB |
| Physical Storage | 256 GB NVMe SSD |

## Operating System

- Ubuntu 24.04.3 LTS
- Linux kernel 6.8.0-87-generic
- LVM-based system storage
- 100 GiB root logical volume

## Container Infrastructure

- Docker Engine 29.8.0
- Docker Compose v5.5.1
- Portainer for container management
- Homepage for centralized access to applications
- Uptime Kuma for service availability monitoring

Application configurations are primarily stored in dedicated directories under the server user's home directory.

## Network Architecture

Network topology, Docker networks, port mappings, and access methods will be documented after verification.

## Storage

The system uses an NVMe SSD with an LVM-based root filesystem.

Application data is stored in a combination of bind-mounted directories and Docker-managed storage. Individual service mounts will be documented as configurations are reviewed.

## Future Improvements

- Document container networks and dependencies
- Review exposed ports and remote access
- Establish backup and recovery procedures
- Standardize Docker Compose configuration management
- Explore automated provisioning with Ansible
