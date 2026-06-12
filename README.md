# OrbitSCP

A fast, cross-platform file transfer client with a modern dual-pane UI.
Supports SFTP, SCP, FTP, FTPS, WebDAV, and S3.
Built with [Tauri](https://tauri.app) (Rust + WebView).

![OrbitSCP Banner](build/icon-1.0.2.png)

---

## Features

- **Protocols** — SFTP, SCP, FTP, FTPS, WebDAV, Amazon S3
- **Dual-pane file manager** — local and remote side by side
- **Fast directory browsing** — single-round-trip SSH exec listing; virtual scroll for directories with 1000+ items
- **File transfers** — upload, download, drag & drop, transfer queue manager
- **Bandwidth throttle** — limit transfer speed per connection
- **SSH key authentication** — OpenSSH keys + automatic PPK → PEM conversion
- **Auto-reconnect** — detects dropped connections and reconnects silently
- **Sync** — two-way sync between local and remote directories
- **Built-in terminal** — full xterm.js terminal via SSH
- **Built-in code editor** — edit remote files directly (VS Code, or built-in)
- **Auto-upload on save** — watch local files and push changes automatically
- **Remote file search** — search by name across remote directories
- **Permissions editor** — view and change remote file permissions (chmod)
- **Keygen** — generate SSH key pairs in-app
- **Session manager** — save, organise, and quickly connect to saved sessions
- **Tabs** — multiple connections open at the same time
- **Live speed badge** — real-time RX/TX speed for all protocols
- **Dark mode themes** — multiple built-in themes
- **Debug log** — optional session log (off by default, toggle in settings)

---

## Screenshots

<img width="100%" alt="OrbitSCP Screenshot" src="./screenshot.png">

---

## Installation

### Windows

Download the latest `.exe` installer from the [Releases](../../releases) page.

### Linux

| Package | Distribution |
|---|---|
| `.deb` | Ubuntu, Linux Mint, Debian |
| `.rpm` | Fedora, CentOS, RHEL |
| `.pacman` | Arch Linux, Manjaro |
| `.snap` | Any snap-enabled distro |
| `.AppImage` | Universal (no install needed) |

### macOS

Coming soon.

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

# Remove saved sessions and settings (optional)
rm -rf ~/.config/orbitscp
rm -rf ~/.local/share/orbitscp
rm -rf ~/.orbitscp
```

---

## Contributing

Pull requests are welcome. For bugs or feature requests, open an issue.

---

## License

MIT License

---

## Author

**Mostafijar Rahman**
- GitHub: https://github.com/mostafijar
- Email: mostafijar7@gmail.com

---

If you find OrbitSCP useful, give it a star on GitHub.
