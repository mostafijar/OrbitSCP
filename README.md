<div align="center">

<img src="icon.png" width="120" alt="OrbitSCP Logo" />

# OrbitSCP

Fast, modern desktop file transfer client for SFTP, SCP, FTP, FTPS, WebDAV, and S3.

[![Version](https://img.shields.io/badge/version-1.0.4-blue?style=flat-square)](../../releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-lightgrey?style=flat-square)](#installation)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)
[![Built with Tauri](https://img.shields.io/badge/built%20with-Tauri-24C8D8?style=flat-square&logo=tauri)](https://tauri.app)
[![Rust](https://img.shields.io/badge/backend-Rust-orange?style=flat-square&logo=rust)](https://www.rust-lang.org)

<img width="100%" alt="OrbitSCP Screenshot" src="screenshots.png" />

</div>

---

## Why OrbitSCP

- Dual-pane workflow focused on speed.
- Smooth handling of large directories and large file diffs.
- Strong SSH and transfer tooling without heavy setup.

---

## Features

### Protocols

- SFTP, SCP, FTP, FTPS
- WebDAV / WebDAVS
- Amazon S3 (B2-compatible setups supported)

### File Operations

- Dual-pane file manager
- Split Commander mode (Server A <-> Server B copy)
- Drag and drop upload/download
- Transfer queue manager
- Remote file search
- Permissions editor (chmod/chown)
- Remote path bookmarks
- Last path memory for local pane and both remote panes

### Sync and Compare

- Two-way sync (upload, download, mirror)
- Include-directory filtering for sync scope
- Sync compares real content differences
- Whitespace-aware compare always enabled in sync
- Per-file Diff directly from sync result list
- Large-file quick diff preview with highlighted changes
- Diff window opens above sync modal for clear workflow

### Productivity

- Built-in terminal
- Built-in editor
- External editor integration
- Auto-upload on save watcher
- SSH key generation in-app
- Multi-connection tabs
- Session manager (save/import/export)

### Security and Reliability

- Password and SSH key authentication
- PPK to OpenSSH conversion support
- Host key verification (TOFU)
- SOCKS5 proxy support
- Keepalive and auto-reconnect behavior
- Optional transfer integrity verification
- Per-connection bandwidth throttle

---

## Installation

### Windows

Download the latest `.exe` installer from the [Releases](../../releases) page.

### Linux

| Format | Distros |
|--------|---------|
| `.deb` | Ubuntu, Linux Mint, Debian |
| `.rpm` | Fedora, CentOS, RHEL, openSUSE |
| `.pacman` | Arch Linux, Manjaro |
| `.snap` | Any snap-enabled distro |
| `.AppImage` | Universal, no install needed |

Download from the [Releases](../../releases) page and install with your package manager.

### macOS

Coming soon.

---

## Development

```bash
npm install
npm run tauri dev
```

Build release:

```bash
npm run tauri build
```

---

## Uninstall

```bash
# DEB (Ubuntu / Debian / Mint)
sudo apt remove orbitscp

# RPM (Fedora / RHEL / CentOS)
sudo dnf remove orbitscp

# RPM (openSUSE)
sudo zypper remove orbitscp

# Snap
sudo snap remove orbitscp

# Pacman (Arch / Manjaro)
sudo pacman -R orbitscp

# Optional: remove app data
rm -rf ~/.config/orbitscp
rm -rf ~/.local/share/orbitscp
rm -rf ~/.orbitscp
```

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| UI | HTML, CSS, JavaScript |
| Backend | Rust |
| Runtime | Tauri |
| Terminal | xterm.js |

---

## Contributing

Pull requests are welcome.
For bugs and feature ideas, open an issue at [Issues](../../issues).

---

## License

MIT License.

---

## Author

<div align="center">

**Mostafijar Rahman**  
[GitHub](https://github.com/mostafijar) · [Email](mailto:mostafijar@mail.com)

</div>

---

<div align="center">

If OrbitSCP helps you, a star on GitHub is appreciated.

</div>
