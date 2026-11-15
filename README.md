# Nettool

**27 network, security, and SSH tools in one native desktop app — running on ~33 MB of RAM.**

[![Built With](https://shields.io)](https://qt.io)

Nettool replaces cluttered terminal tabs, 1990s-era utilities (like PuTTY and Angry IP Scanner), and bloated Electron wrappers with a single, fast, modern command center for network diagnostics and security checks.

![Nettool Screenshot](docs/screenshot.png)
<!-- Replace the path above with your wide screenshot showing an active tool + the right-side info panel -->

---

## Why Nettool?

* **Featherweight Performance (~33 MB RAM):** Written from scratch in modern **C++ and Qt 6.10.2**. Starts instantly and uses a fraction of the memory of a single browser tab.
* **27 Tools in One Window:** No more remembering flags across a dozen separate binaries.
* **Modern Command Center UI:** Dark theme, native compositor blur support (e.g., KDE Blur on Linux), live network interface stats, system info, and 1-click Quick Actions.
* **Native on Linux & Windows:** Built specifically for desktop Linux and Windows with zero web-wrapper overhead.
* **100% Free Companion CLI:** Need to run checks over SSH or inside automated scripts? The full CLI shares the same C++ core and is completely free.

---

## Memory Footprint Comparison

| Application | Tech Stack | Idle RAM Usage |
| :--- | :--- | :--- |
| **Nettool 3.0** | **C++ / Qt 6** | **~33 MB** |
| Modern Electron Network Tools | Chromium / Node.js | ~450 MB – 900 MB |
| Legacy Utilities (PuTTY + Angry IP + Wireshark) | Win32 / Java / GTK | 150 ~ 240 |

---

## All 27 Built-in Tools

### Discovery & Recon
* **Subnet Sweep** — Fast local network host discovery
* **Batch Host Check** — Monitor and verify multiple targets simultaneously
* **Banner Grab** — Inspect service banners on open ports
* **Wait for Port** — Poll a host until a specific TCP port becomes reachable
* **Local Port Check** — Verify local port availability and bindings
* **Open Sockets** — View active network connections and listening sockets
* **ARP Table** — Inspect local IP-to-MAC address mappings

### Security & OSINT
* **Breach Check (Email)** — Check if an email address appears in known data breaches
* **Breach Check (Domain)** — Audit domain-wide exposure across breach datasets
* **TLS Certificate** — Inspect SSL/TLS certificate chains, issuers, and expiration dates
* **WHOIS** — Query domain and IP registration records

### Web & DNS
* **HTTP Headers** — Inspect raw response headers and server configurations
* **HTTP Timing** — Measure DNS lookup, TCP connect, TLS handshake, and TTFB latency
* **DNS Resolver Check** — Query and compare records across DNS resolvers
* **Reverse DNS** — Perform PTR lookups on IP addresses
* **Public IP** — Instantly detect your external WAN IP address

### Routing, Performance & Remote Access
* **SSH Client** — Built-in terminal access without leaving your diagnostic suite
* **Bandwidth Test** — Measure throughput and connection speed
* **Path MTU** — Discover maximum transmission unit size along a network path
* **Traffic Monitor** — Real-time bandwidth and interface activity visualization
* **Traceroute** — Trace packet hops and per-hop latency
* **CIDR Calculator** — Instant subnet mask, network range, and host count math
* *(Plus additional quick-access diagnostic utilities built right into the Command Center)*

---

## Installation

### Desktop GUI (Linux & Windows)
Download the latest native installer or portable binary for your platform from this github.
* **Linux:** `.deb`, `.AppImage`, or binary archive
* **Windows:** `.exe` installer / portable `.zip`

### Free CLI
The companion CLI is **100% free** for personal, commercial, and headless server use. Contact me for installation instructions and CLI documentation.

---

## Tips for Linux Compositors (KDE / Hyprland / Sway)
Nettool supports adjustable window opacity and background blur.
* On **KDE Plasma**, enable the **Blur** desktop effect for translucent glassmorphism behind the sidebar and panels.
* If you use a compositor without blur support, set **Window Opacity** to `100%` in **Settings → Appearance**.

---

## Feedback & Roadmap
Found a bug, want to request a new network tool, or have feedback on platform support?
* Open an issue right here on GitHub
