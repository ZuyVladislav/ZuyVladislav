# Vladislav Zyuzin

![Adaptive IPsec Overlay](assets/banner.svg)

**AI Full-Stack & Systems Engineer** — production AI workflows, reliable backend/frontend systems, Linux/network infrastructure, and adaptive VPN research.

[![Portfolio](https://img.shields.io/badge/Portfolio-vladislav--it.com-0f172a?style=for-the-badge)](https://vladislav-it.com)
[![Telegram](https://img.shields.io/badge/Telegram-@vdzyuzin-26A5E4?style=for-the-badge)](https://t.me/vdzyuzin)
[![Adaptive Secure Overlay](https://img.shields.io/badge/Org-Adaptive--Secure--Overlay-166534?style=for-the-badge)](https://github.com/Adaptive-Secure-Overlay)

## Core Engineering & Open Templates

| Repository | Focus | Stack |
| --- | --- | --- |
| [ai-workflow-backend](https://github.com/ZuyVladislav/ai-workflow-backend) | Production template for structured LLM workflows, PII masking, idempotent jobs, and CI | Python, FastAPI, Pydantic, PostgreSQL, Docker |
| [ha-infra-blueprint](https://github.com/ZuyVladislav/ha-infra-blueprint) | Zero-downtime atomic symlink releases with rollback trap, WireGuard mesh audit, Nginx TLS, and PG backups | Bash, Python, Nginx, WireGuard, PostgreSQL |
| [antigravity-ru-localizer](https://github.com/ZuyVladislav/antigravity-ru-localizer) | Local static UI localizer and compatibility patcher for Google Antigravity | JavaScript, Node.js, Cross-platform CI |

Selected commercial products (full-stack web/mobile systems, document AI pipelines such as **Doc Autopilot**, infrastructure AI diagnostics, and US healthcare clinic engineering) are showcased at [vladislav-it.com](https://vladislav-it.com).

---

## Adaptive IPsec & Overlay Networking Lab

[![Hub](https://img.shields.io/badge/hub-adaptive--ipsec--overlay-0f172a?style=for-the-badge)](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay)
[![Linux](https://img.shields.io/badge/Linux-package-166534?style=for-the-badge)](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay-linux)
[![OpenWRT](https://img.shields.io/badge/OpenWRT-package-0f766e?style=for-the-badge)](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay-openwrt)
[![RouterOS 7](https://img.shields.io/badge/RouterOS%207-package-7f1d1d?style=for-the-badge)](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay-routeros7)
[![Android](https://img.shields.io/badge/Android-prototype-1d4ed8?style=for-the-badge)](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay-android)
[![Windows](https://img.shields.io/badge/Windows-endpoint-334155?style=for-the-badge)](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay-windows)

I build and test routed IKE control-plane schemes where negotiation can traverse selected intermediate nodes while ESP remains direct between endpoints after security associations are established.

### Featured Network Repositories

| Repository | Scope |
| --- | --- |
| [Adaptive-Secure-Overlay/adaptive-ipsec-overlay](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay) | Project hub, architecture, and cross-platform documentation |
| [Adaptive-Secure-Overlay/adaptive-ipsec-overlay-linux](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay-linux) | Linux endpoint and intermediate-node package |
| [Adaptive-Secure-Overlay/adaptive-ipsec-overlay-openwrt](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay-openwrt) | OpenWRT endpoint and intermediate-node package |
| [Adaptive-Secure-Overlay/adaptive-ipsec-overlay-routeros7](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay-routeros7) | MikroTik RouterOS 7 container profile for intermediate nodes |
| [Adaptive-Secure-Overlay/adaptive-ipsec-overlay-android](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay-android) | Kotlin Android client prototype for mobile endpoint integration |
| [Adaptive-Secure-Overlay/adaptive-ipsec-overlay-windows](https://github.com/Adaptive-Secure-Overlay/adaptive-ipsec-overlay-windows) | C# Windows endpoint and service lifecycle prototype |

### Research Direction & Lab Stack

- Split control-plane path hiding during IKE exchange and direct ESP data forwarding once the tunnel is established.
- Debian and OpenWRT nodes with strongSwan, plus MikroTik RouterOS 7 container intermediates.
- EVE-NG provider-style topologies and reproducible multi-hop experiments for doctoral research in information security.
