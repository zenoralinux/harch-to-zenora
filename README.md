# Zenora Upgrade Utility

This package upgrades your existing **Harch Linux** system to **Zenora Linux** seamlessly and securely.

## 📦 Installation
if you seem any errors ,make sure this packages are removed:
```bash

sudo sh -c 'pacman -Rdd harch-back --noconfirm 2>/dev/null || true; pacman -Rdd harch-calamares-config --noconfirm 2>/dev/null || true; pacman -Rdd harch-chromium-font --noconfirm 2>/dev/null || true; pacman -Rdd harch-fake-apt --noconfirm 2>/dev/null || true; pacman -Rdd harch-gaming --noconfirm 2>/dev/null || true; pacman -Rdd harch-gnome-backgrounds --noconfirm 2>/dev/null || true; pacman -Rdd harch-gnome-dconf --noconfirm 2>/dev/null || true; pacman -Rdd harch-gnome-def-extentions --noconfirm 2>/dev/null || true; pacman -Rdd harch-gnome-icons --noconfirm 2>/dev/null || true; pacman -Rdd harch-gnome-pro --noconfirm 2>/dev/null || true; pacman -Rdd harch-gnome-software --noconfirm 2>/dev/null || true; pacman -Rdd harch-openrgb --noconfirm 2>/dev/null || true; pacman -Rdd harch-phinger-cursor --noconfirm 2>/dev/null || true; pacman -Rdd harch-plasma-desktop --noconfirm 2>/dev/null || true; pacman -Rdd harch-pymouth-theme --noconfirm 2>/dev/null || true; pacman -Rdd harch-qemu-kvm --noconfirm 2>/dev/null || true; pacman -Rdd harch-release --noconfirm 2>/dev/null || true; pacman -Rdd harch-sddm-astronaut-theme --noconfirm 2>/dev/null || true; pacman -Rdd harch-system-fonts --noconfirm 2>/dev/null || true; pacman -Rdd harch-welcome --noconfirm 2>/dev/null || true; pacman -Rdd harch-zsh-config --noconfirm 2>/dev/null || true'
```
To download and install the package in one step, run the following command:

```bash
sudo pacman -Syu wget
wget https://github.com/zenoralinux/harch-to-zenora/releases/download/1.0.1/harch-upgrade-to-zenora-1.0-1-x86_64.pkg.tar.zst
sudo pacman -U --noconfirm ./harch-upgrade-to-zenora-1.0-1-x86_64.pkg.tar.zst
```

## 🚀 Running the Upgrade

Once installed, initiate the upgrade process with the command below:

```bash
appzenora-upgrade
```

Alternatively, you may run it with `sudo`:

```bash
sudo appzenora-upgrade
```

> **Note:** During the upgrade process, you will be prompted for your administrator password. Please enter it when requested.

### ⚠️ Important:

- **Do not** close or interrupt the upgrade program while it is running.
- Make sure your system is connected to the internet.
- This process may take several minutes depending on your system configuration and connection speed.

## 🧹 Uninstallation

If you wish to remove the upgrade utility after the process, run:

```bash
sudo pacman -Rns harch-upgrade-to-zenora
```

---

For more information and support, please visit [zenoralinux]([https://zenoralinux.org](https://t.me/Zenoralinux)).
