# Nettool CLI

**A fast, lightweight, single-binary network and security toolkit for Linux and Windows terminals — written in C++.**

[![Website](https://shields.io)](https://vercel.app)
[![Language](https://shields.io)](https://github.com.)
[![Platforms](https://shields.io)](https://github.com.)
[![License](https://shields.io)](https://github.com.)

**Nettool CLI** brings 27 essential network diagnostic, recon, and security tools into a single, dependency-free command-line executable. Built in C++, it starts instantaneously, uses minimal memory, and prints clean, plain-text output ready for SSH sessions, scripts, and incident tickets.

> Looking for the visual desktop interface with 1-click Quick Actions, live traffic graphs, and built-in SSH? Check out **[Nettool 3.0 Desktop GUI](https://vercel.app)**.

---

## Features

* **Zero Dependencies:** Single standalone binary (`nettool-cli` on Linux, `nettoolwin-cli.exe` on Windows) — no Python, Node.js, or external runtime required.
* **Fast & Featherweight:** Pure C++ execution with negligible RAM and CPU overhead.
* **Clean, Copy-Pasteable Output:** Prints plain terminal text designed for easy reading, logging, and pasting straight into bug reports or tickets.
* **27 Built-in Tools:** Everything from subnet sweeps and banner grabbing to TLS inspection, HTTP timing, and breach checks.

---

## Quick Install

### Linux
Download the binary, make it executable, and run it:

```bash
curl -L -o nettool-cli https://github.com./raw/refs/heads/main/nettool-cli
chmod +x ./nettool-cli
./nettool-cli
```

*(Optional) Move it to your PATH to run `nettool-cli` from anywhere:*
```bash
sudo mv ./nettool-cli /usr/local/bin/nettool-cli
```

### Windows
1. Download **`nettoolwin-cli.exe`** from this repository.
2. Open **Command Prompt** or **PowerShell** in the download folder and run:

```powershell
.\nettoolwin-cli.exe
```

### Uninstall
To remove Nettool CLI, simply delete the downloaded binary (`rm ./nettool-cli` or `sudo rm /usr/local/bin/nettool-cli`).

---

## Included Tools (27 Total)

* **Discovery & Scanning:** Subnet sweep, Batch host check, Banner grab, Wait for port, Local port check, Open sockets, ARP table
* **Security & OSINT:** Breach check (email & domain), TLS certificate inspector, WHOIS
* **Web & DNS:** HTTP headers, HTTP timing, DNS resolver check, Reverse DNS, Public IP
* **Routing & Performance:** Bandwidth test, Path MTU, Traffic monitor, Traceroute, CIDR calculator, Ping

---

## Want a Modern Desktop GUI?

If you prefer a full graphical interface on **Linux or Windows**, check out **Nettool 3.0 Desktop**:
* Native **C++ / Qt 6** app running on **~33 MB of RAM** (no Electron bloat)
* Side-by-side tool menu, unified input forms, and built-in terminal output
* Live network interface stats, system info panel, and 1-click Quick Actions
* Native dark theme with compositor/KDE blur support

Learn more at **[nettool-flame.vercel.app](https://vercel.app)**.

---

## Contact & Feedback
* **GitHub Issues:** Report bugs or request new CLI tools right here in the repository.
