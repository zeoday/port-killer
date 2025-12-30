# PortKiller

<p align="center">
  <img src="Resources/AppIcon.svg" alt="PortKiller Icon" width="128" height="128">
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT"></a>
  <a href="https://www.apple.com/macos/"><img src="https://img.shields.io/badge/macOS-15.0%2B-brightgreen" alt="macOS"></a>
  <a href="https://www.microsoft.com/windows"><img src="https://img.shields.io/badge/Windows-10%2B-0078D6" alt="Windows"></a>
  <a href="https://github.com/productdevbook/port-killer/releases"><img src="https://img.shields.io/github/v/release/productdevbook/port-killer" alt="GitHub Release"></a>
</p>

<p align="center">
A native app for finding and killing processes on open ports.<br>
Perfect for developers who need to quickly free up ports like 3000, 8080, 5173, etc.
</p>

### macOS

<p align="center">
  <img src=".github/assets/macos.png" alt="PortKiller macOS" width="800">
</p>

### Windows

<p align="center">
  <img src=".github/assets/windows.jpeg" alt="PortKiller Windows" width="800">
</p>

## Installation

### macOS

**Homebrew:**
```bash
brew install --cask productdevbook/tap/portkiller
```

**Manual:** Download `.dmg` from [GitHub Releases](https://github.com/productdevbook/port-killer/releases).

### Windows

Download `.zip` from [GitHub Releases](https://github.com/productdevbook/port-killer/releases) and extract.

## Features

- 📍 Menu bar integration (macOS) / System tray (Windows)
- 🔍 Auto-discovers listening TCP ports
- ⚡ One-click process termination
- 🔄 Auto-refresh
- 🔎 Search by port or process name
- ⭐ Favorites and watched ports
- 📂 Process type categorization (Web Server, Database, Development, System)
- 🔗 Port forwarding management (Kubernetes kubectl)
- ☁️ Cloudflare Tunnels integration

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for development setup.

## Sponsors

<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/productdevbook/static/sponsors.svg">
    <img src='https://cdn.jsdelivr.net/gh/productdevbook/static/sponsors.svg'/>
  </a>
</p>

## License

MIT License - see [LICENSE](LICENSE).
