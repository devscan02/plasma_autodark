# Auto Dark Mode for KDE Plasma 5 and 6

Auto Dark Mode is a lightweight utility for KDE Plasma that automatically switches your theme based on the system time of day.

**Created by:** devscan02

## Features

- 🌙 Automatic theme switching based on system time
- ⚙️ Easy installation and configuration
- 🔄 Systemd service integration
- 💾 Lightweight and efficient

## Prerequisites

- KDE Plasma 5 or 6
- Make (for building)

## Installation

### Build

```bash
make
```

### Install

```bash
make install
```

## Usage

### Start the service

```bash
systemctl --user start autodark.service
systemctl --user start autodark.timer
```

### Stop the service

```bash
systemctl --user stop autodark.service
systemctl --user stop autodark.timer
```

### Enable on system startup

```bash
systemctl --user enable autodark.service
systemctl --user enable autodark.timer
```

### Disable on system startup

```bash
systemctl --user disable autodark.service
systemctl --user disable autodark.timer
```

## Uninstallation

```bash
make uninstall
```

## License

See the repository for license information.