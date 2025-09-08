# Patuyyy's Homelab

**[Features]() • [Get Started]() • [Documentation]()**


This project focuses on documenting the setup, configuration, and continuous development of my homelab. It serves as a personal learning platform where I experiment with various technologies in networking, virtualization, monitoring, and security. Over time, it can also be used as a reference or framework for others who want to build their own homelab environment.

> **What is a homelab?**
>
> Homelab is a laboratory at home where you can self-host, experiment with new technologies, practice for certifications, and so on.
> This repository documents my journey in building and maintaining a **personal home lab**, starting from the physical setup to the deployment of various software and services.  
The purpose of this project is to create a flexible, self-managed environment for continuous learning, experimentation, and hands-on practice with modern IT infrastructure.

---

## Overview

Project status: **ONGOING**

This project will continue to evolve with improvements in both software and hardware.
Everything documented in this repository reflects the progress I have made so far.
For any questions or inquiries, please feel free to reach out to [Raihan](https://www.linkedin.com/in/hanihsan/), the owner of this project.

### Hardware

The hardware powering this project, which will continue to evolve and expand as the home lab advances ![Hardware](https://github.com/patuyyy/home-lab/blob/main/assets/server-1.jpeg)

- 1 × `Custom PC`  :
    - CPU: `Intel Xeon E5-2680 v4 (14 Core, Cache 35MB)`
    - RAM: `32GB`
    - SSD: `512GB`
    - VGA: `Nvidia Geforce GT610 2GB DDR3`

### IP and Domain
I have a public IP address and a custom domain configured for this server.
Domain: patuyyy.com
DNS Management: Handled via Cloudflare

### Features

- [x] Proxmox based virtualization for host
- [x] Server and Network monitoring with Zabbix and Grafana
- [x] Network simulation application: PNetlab and GNS3
- [x] Reverse proxy with NGINX
- [x] VPN access (OpenVPN and Wireguard)
- [x] Media management (Jellyfin)
- [x] Ansible automation
- [x] HTTPS certificate management for all services using Let's Encrypt


| Proxmox Virtual Environtment                                                                                    |
| :--:                                                                                                            |
| ![Proxmox](https://github.com/patuyyy/home-lab/blob/main/assets/proxmox.png)                                    |
| Monitoring dashboard powered by [Grafana](https://grafana.com)                                                  |
| ![grafana](https://github.com/patuyyy/home-lab/blob/main/assets/grafana.png)                                    |
| VPN access by [Wireguard](https://www.wireguard.com)                                                            |
| ![wireguard](https://github.com/patuyyy/home-lab/blob/main/assets/wireguard.png)                                |
| Jellyfin media system                                                                                           |
| ![jellyfin](https://github.com/patuyyy/home-lab/blob/main/assets/jellyfin.png)                                  |

