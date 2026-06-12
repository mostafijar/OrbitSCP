<div align="center">

<img src="icon.png" width="120" alt="OrbitSCP Logo" />

# OrbitSCP

**A fast, modern file transfer client for SFTP · SCP · FTP · FTPS · WebDAV · S3**

[![Version](https://img.shields.io/badge/version-1.0.4-blue?style=flat-square)](../../releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-lightgrey?style=flat-square)](#installation)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)
[![Built with Tauri](https://img.shields.io/badge/built%20with-Tauri-24C8D8?style=flat-square&logo=tauri)](https://tauri.app)
[![Rust](https://img.shields.io/badge/backend-Rust-orange?style=flat-square&logo=rust)](https://www.rust-lang.org)

<img width="100%" alt="OrbitSCP Screenshot" src="screenshots.png" />

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

**🌐 Protocols**
- SFTP, SCP, FTP, FTPS
- WebDAV, Amazon S3

**📁 File Management**
- Dual-pane file manager
- Drag & drop uploads
- Transfer queue manager
- Remote file search
- Permissions editor (chmod)

**⚡ Performance**
- Single-round-trip SSH exec listing
- Virtual scroll for 1000+ item directories
- Connection pool with auto-reuse
- SSH keepalive — no idle disconnects

</td>
<td width="50%">

**🔐 Security & Auth**
- SSH key authentication
- PPK → OpenSSH auto-conversion
- SOCKS5 proxy support
- Host key verification (TOFU)

**🛠️ Productivity**
- Built-in xterm.js terminal
- Built-in code editor
- Auto-upload on save (file watcher)
- Two-way sync
- SSH keygen in-app
- Bandwidth throttle per connection

**🎨 Interface**
- Multiple dark mode themes
- Tab support — multiple connections
- Live RX/TX speed badge
- Session manager
- Optional debug log

</td>
</tr>
</table>

---

## 📥 Installation

### Windows

Download the latest **`.exe` installer** from the [**Releases**](../../releases) page.

### Linux

| Format | Distributions |
|--------|--------------|
| `.deb` | Ubuntu · Linux Mint · Debian |
| `.rpm` | Fedora · CentOS · RHEL · openSUSE |
| `.pacman` | Arch Linux · Manjaro |
| `.snap` | Any snap-enabled distro |
| `.AppImage` | Universal — no install needed |

> Download from the [**Releases**](../../releases) page and install with your package manager.

### macOS

🚧 Coming soon

---

## 🗑️ Uninstall

<details>
<summary>Click to expand uninstall instructions</summary>

```bash
# DEB — Ubuntu / Debian / Mint
sudo apt remove orbitscp

# RPM — Fedora / RHEL / CentOS
sudo dnf remove orbitscp

# RPM — openSUSE
sudo zypper remove orbitscp

# Snap
sudo snap remove orbitscp

# Pacman — Arch / Manjaro
sudo pacman -R orbitscp

# Remove saved sessions and settings (optional)
rm -rf ~/.config/orbitscp
rm -rf ~/.local/share/orbitscp
rm -rf ~/.orbitscp
```

</details>

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-----------|
| UI | HTML · CSS · JavaScript |
| Backend | Rust |
| Desktop runtime | [Tauri](https://tauri.app) |
| Terminal | Built-in terminal emulator |

---

## 🤝 Contributing

Pull requests are welcome.
For bugs or feature ideas, please [open an issue](../../issues).

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

<table>
<tr>
<td align="center">
<b>Mostafijar Rahman</b><br/>
<a href="https://github.com/mostafijar">GitHub</a> ·
<a href="mailto:mostafijar@mail.com">Email</a>
</td>
</tr>
</table>

---

<div align="center">

If OrbitSCP is useful to you, consider giving it a ⭐ on GitHub — it helps a lot!

</div>
