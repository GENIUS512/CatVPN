<div align="center">

<img src="icons/catvpn.png" width="160" alt="CatVPN"/>

# 🐾 CatVPN

### Free VPN client with a black cat that never gives up.

**OpenVPN · VPN Gate · Custom profiles · Shadowsocks · "Never give up" engine**

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PyQt6](https://img.shields.io/badge/PyQt6-6.x-41CD52?style=for-the-badge&logo=qt&logoColor=white)](https://pypi.org/project/PyQt6/)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#-requirements)
[![License](https://img.shields.io/badge/License-MIT-ff8fb1?style=for-the-badge)](LICENSE)
[![Stars](https://img.shields.io/github/stars/YOUR_USERNAME/CatVPN?style=for-the-badge&color=ff8fb1)](https://github.com/YOUR_USERNAME/CatVPN/stargazers)
[![Forks](https://img.shields.io/github/forks/YOUR_USERNAME/CatVPN?style=for-the-badge&color=8b7bff)](https://github.com/YOUR_USERNAME/CatVPN/network/members)

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=FF8FB1&center=true&vCenter=true&width=700&lines=Free+VPN+servers+from+VPN+Gate;OpenVPN+%2B+Shadowsocks+in+one+app;A+black+cat+that+walks+while+you+connect;Never+gives+up+until+the+tunnel+is+up" alt="Typing SVG" />

<br/>

<a href="#-features"><img src="https://img.shields.io/badge/✨_Features-ff8fb1?style=for-the-badge" alt="Features"/></a>
<a href="#-installation"><img src="https://img.shields.io/badge/📦_Installation-8b7bff?style=for-the-badge" alt="Installation"/></a>
<a href="#-screenshots"><img src="https://img.shields.io/badge/📸_Screenshots-19b5fe?style=for-the-badge" alt="Screenshots"/></a>
<a href="#-faq"><img src="https://img.shields.io/badge/❓_FAQ-ffcf70?style=for-the-badge" alt="FAQ"/></a>

</div>

---

<div align="center">

## ✨ What is CatVPN?

</div>

**CatVPN** is a desktop VPN client that brings together the best free public VPN servers from **VPN Gate** and your **own OpenVPN profiles** into one friendly app. It is powered by a **"never give up" connection engine**: it walks through every server, protocol, port and compatibility mode in rounds until something connects — or you press *Cancel*.

And yes — there is a **black cat** living in the connect button. 🐈‍⬛

- 🌙 At night she sits on a moonlit rooftop, tail swaying, eyes glowing.
- 🚶 While you connect, she walks along the ledge and the city scrolls past.
- 🛡 When the tunnel is up, a glowing green shield closes around her.
- 🍜 At meal times (7–9, 13–15, 19–21) she eats from a bowl with little sparkles.
- 💤 The rest of the day she sleeps and puffs "z" clouds into the air.

<div align="center">

**The cat reflects the real state of your connection — idle, connecting or protected.**

</div>

---

<div align="center">

## 📸 Screenshots

</div>

> 💡 *Add your own screenshots below. Drop them into `docs/` and replace the paths.*

<div align="center">

| Home — idle | Connecting | Protected |
|:---:|:---:|:---:|
| <img src="docs/screenshot-idle.png" width="260"/> | <img src="docs/screenshot-connecting.png" width="260"/> | <img src="docs/screenshot-connected.png" width="260"/> |

| Servers list | Settings |
|:---:|:---:|
| <img src="docs/screenshot-servers.png" width="420"/> | <img src="docs/screenshot-settings.png" width="420"/> |

</div>

---

<div align="center">

## ✨ Features

</div>

<table>
<tr>
<td width="50%" valign="top">

### 🎯 Connection engine
- 🔁 **Never give up** — rounds of servers × protocols × ports until connected
- 🌐 **Auto / UDP / TCP** protocol selection
- 🔌 **Auto / TUN / TAP** tunnel mode
- 🧩 **Compatibility mode** for old servers (legacy ciphers, TLS 1.0)
- 🛰 **HTTP / SOCKS proxy** for TCP attempts
- ⏱ Configurable attempt timeout and TCP probe timeout
- 🔄 **Auto-reconnect** when the tunnel drops
- ✅ **Real handshake test** for every server (green = really works)

</td>
<td width="50%" valign="top">

### 🐱 The cat
- 🌙 Night/day sky — follows your real system time
- 🏙 Parallax city skyline with flickering windows
- 🐾 Hand-drawn fur, rim light from the moon, blinking eyes
- 🍜 Eats at meal times, sleeps the rest of the day
- 🛡 Green shield ring when the tunnel is up
- 🎨 5 themes: **Neko · Ocean · Sunset · Forest · Graphite**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📂 Profiles
- 📥 Import `.ovpn`, `.conf`, `.cfg`, `.txt`, `.ini`, `.zip`
- 🗂 Drop files into `servers/configs` — loaded automatically
- 🔗 Paste OpenVPN text or **Shadowsocks `ss://` links**
- 📁 Certificates & keys next to a config are used automatically
- 🗑 Delete your own profiles from the app
- 🌍 Public VPN Gate servers with country flags

</td>
<td width="50%" valign="top">

### 🛡 Security & UX
- 🚫 `--block-outside-dns` on Windows (DNS leak protection)
- 🔍 External IP verification after connecting
- 🎭 **Real IP is hidden** — only the changed (VPN) IP is shown
- ⚠ Security warning before connecting to free servers
- 🖥 **System SOCKS proxy** support (Windows / macOS / GNOME) for Shadowsocks
- 🌐 **English & Русский** interface

</td>
</tr>
</table>

---

<div align="center">

## 🚀 Installation

</div>

### 1️⃣ Install OpenVPN

CatVPN is a **front-end** for OpenVPN — the actual tunnel is created by it.

| Platform | Command / Link |
|---|---|
| 🪟 **Windows** | [Download OpenVPN](https://openvpn.net/community-downloads/) — install as administrator, keep the TAP/Wintun drivers enabled |
| 🐧 **Linux** | `sudo apt install openvpn` · `sudo dnf install openvpn` · `sudo pacman -S openvpn` |
| 🍎 **macOS** | `brew install openvpn` |

### 2️⃣ Install Python dependencies

```bash
pip install PyQt6 psutil
