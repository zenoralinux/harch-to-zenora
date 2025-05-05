# Zenora Upgrade Utility

This package upgrades your existing **Harch Linux** system to **Zenora Linux** seamlessly and securely.

## 📦 Installation
if you seem any errors ,make sure this packages are removed:
```bash

sudo pacman -Rdd harch-back  harch-calamares-config harch-chromium-font harch-fake-apt  harch-gaming  harch-gnome-backgrounds harch-gnome-dconf harch-gnome-def-extentions harch-gnome-icons harch-gnome-pro harch-gnome-software  harch-openrgb  harch-phinger-cursor harch-plasma-desktop harch-pymouth-theme harch-qemu-kvm harch-release  harch-sddm-astronaut-theme harch-system-fonts harch-welcome harch-zsh-config --noconfirm 
 --noconfirm
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
