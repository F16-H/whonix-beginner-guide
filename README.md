
# Whonix Beginner Guide

<p align="center">
  <img src="images/banner.png" width="100%" />
</p>

<h1 align="center">Whonix Beginner Guide</h1>

<p align="center">
  A beginner-friendly guide to understanding, installing, and verifying Whonix safely.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-blue">
  <img src="https://img.shields.io/badge/VirtualBox-Supported-orange">
  <img src="https://img.shields.io/badge/Tor-Network-purple">
  <img src="https://img.shields.io/badge/Status-Active-success">
  <img src="https://img.shields.io/badge/Languages-English%20%7C%20Arabic-red">
</p>

---

## 🌐 Language
- 🇺🇸 English
- 🇸🇦 [العربية](README_AR.md)

---

<p align="center">
  <a href="#about">About</a> •
  <a href="#installation">Installation</a> •
  <a href="#wireshark-verification">Verification</a> •
  <a href="#security-tips">Security Tips</a> •
  <a href="#troubleshooting">Troubleshooting</a>
</p>

---

# About

This project was created to help beginners understand Whonix and privacy-focused environments in a practical and visual way.

---

# What is Whonix?

Whonix is a privacy-focused operating system designed to route all traffic through the Tor network using two isolated virtual machines:

- Whonix Gateway
- Whonix Workstation

```txt
User → Workstation → Gateway → Tor → Internet
```

---

# Installation

## Step 1 — Install VirtualBox

Official Website:
https://www.virtualbox.org

### Example

![VirtualBox Setup](images/virtualbox-install.png)

---

## Step 2 — Download Whonix

Official Download:
https://www.whonix.org/wiki/Download

Download:
- Gateway
- Workstation

---

## Step 3 — Import Virtual Machines

Open:

```txt
File → Import Appliance
```

Import:
- Gateway
- Workstation

### Example

![Import Appliance](images/import-whonix.png)

---

## Step 4 — Start Gateway First

Always start:

1. Gateway
2. Workstation

---

# Installation Checklist

- [ ] Install VirtualBox
- [ ] Download Whonix
- [ ] Import Gateway
- [ ] Import Workstation
- [ ] Start Gateway
- [ ] Verify Tor Connection
- [ ] Install Wireshark
- [ ] Analyze Traffic

---

# Wireshark Verification

Wireshark helps verify:
- Tor traffic
- DNS behavior
- Packet flow
- Network routing

---

## Install Wireshark

Official Website:
https://www.wireshark.org

Download:
https://www.wireshark.org/download.html

During installation:
- Install Npcap
- Keep default settings

---

## Start Capturing

1. Open Wireshark
2. Select your active adapter
3. Start capture
4. Open Tor Browser inside Whonix

### Example

![Wireshark](images/wireshark-example.png)

---

# Helpful Filters

## TCP

```txt
tcp
```

## DNS

```txt
dns
```

## Tor

```txt
tor
```

---

# Comparison Table

| Feature | Whonix | Tor Browser | VPN |
|---|---|---|---|
| Full System Routing | ✅ | ❌ | ❌ |
| Traffic Isolation | ✅ | ❌ | ❌ |
| Identity Separation | ✅ | ❌ | ❌ |
| Beginner Friendly | ⚠️ | ✅ | ✅ |

---

# Security Tips

- Keep systems updated
- Use strong passwords
- Avoid suspicious downloads
- Separate identities
- Avoid random browser extensions

---

# Troubleshooting

## No Internet

Possible fixes:
- Restart Gateway
- Check VirtualBox network settings
- Verify host internet access

---

## Tor Connection Failed

Possible fixes:
- Sync system time
- Restart Whonix
- Check firewall settings

---

# Folder Structure

```txt
whonix-beginner-guide/
│
├── README.md
├── README_AR.md
├── images/
├── verification/
├── troubleshooting/
└── resources/
```

---

# Recommended Tools

- https://www.whonix.org
- https://www.virtualbox.org
- https://www.wireshark.org
- https://www.torproject.org

---

# Future Improvements

- [x] Installation Guide
- [x] Wireshark Verification
- [ ] Advanced Networking
- [ ] OPSEC Section
- [ ] Qubes OS Integration

---

# Disclaimer

This project is intended for educational and privacy-awareness purposes only.

---

# Author

Created by Feras Hamamdeh
