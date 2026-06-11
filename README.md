# Vladislav Zyuzin

![Adaptive IPsec Overlay](assets/banner.svg)

Adaptive IPsec, overlay routing, and VPN research lab.

[![Hub](https://img.shields.io/badge/hub-adaptive--ipsec--overlay-0f172a?style=for-the-badge)](https://github.com/ZuyVladislav/adaptive-ipsec-overlay)
[![Linux](https://img.shields.io/badge/Linux-package-166534?style=for-the-badge)](https://github.com/ZuyVladislav/adaptive-ipsec-overlay-linux)
[![OpenWRT](https://img.shields.io/badge/OpenWRT-package-0f766e?style=for-the-badge)](https://github.com/ZuyVladislav/adaptive-ipsec-overlay-openwrt)
[![RouterOS 7](https://img.shields.io/badge/RouterOS%207-package-7f1d1d?style=for-the-badge)](https://github.com/ZuyVladislav/adaptive-ipsec-overlay-routeros7)

I build and test routed IKE control-plane schemes where negotiation can traverse
selected intermediate nodes while ESP remains direct between endpoints after
security associations are established.

Current focus:

- Adaptive IPsec/IKE overlay for Linux, OpenWRT, and MikroTik RouterOS 7 labs.
- Direct ESP data-plane after routed control-plane establishment.
- Research-grade prototypes for EVE-NG experiments and dissertation work.

## Featured repositories

- [adaptive-ipsec-overlay](https://github.com/ZuyVladislav/adaptive-ipsec-overlay):
  central hub, shared documentation, cross-platform structure
- [adaptive-ipsec-overlay-linux](https://github.com/ZuyVladislav/adaptive-ipsec-overlay-linux):
  Linux endpoint and intermediate-node package
- [adaptive-ipsec-overlay-openwrt](https://github.com/ZuyVladislav/adaptive-ipsec-overlay-openwrt):
  OpenWRT endpoint and intermediate-node package
- [adaptive-ipsec-overlay-routeros7](https://github.com/ZuyVladislav/adaptive-ipsec-overlay-routeros7):
  RouterOS 7 container profile for intermediate nodes

## Projects

| Repository | Scope |
| --- | --- |
| [adaptive-ipsec-overlay](https://github.com/ZuyVladislav/adaptive-ipsec-overlay) | Project hub and shared documentation |
| [adaptive-ipsec-overlay-linux](https://github.com/ZuyVladislav/adaptive-ipsec-overlay-linux) | Linux endpoint and intermediate-node package |
| [adaptive-ipsec-overlay-openwrt](https://github.com/ZuyVladislav/adaptive-ipsec-overlay-openwrt) | OpenWRT endpoint and intermediate-node package |
| [adaptive-ipsec-overlay-routeros7](https://github.com/ZuyVladislav/adaptive-ipsec-overlay-routeros7) | RouterOS 7 container profile for intermediate nodes |

## Research direction

The current prototype studies a split between:

- control-plane path hiding during IKE exchange;
- direct ESP forwarding after the tunnel is established;
- platform-specific deployment paths for Linux, OpenWRT, and RouterOS-based
  lab nodes.

The work is positioned as a research prototype rather than a production VPN
client.

## Lab stack

- Debian and OpenWRT nodes with strongSwan.
- MikroTik RouterOS 7 nodes as container-based overlay intermediates.
- EVE-NG provider-style topologies for multi-hop experiments.

## Status

Active lab development. Public repositories currently expose the packaging and
deployment side of the prototype.
