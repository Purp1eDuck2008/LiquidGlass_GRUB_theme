# LiquidGlass GRUB Theme

![License](https://img.shields.io/badge/License-MIT-blue.svg) ![GRUB Version](https://img.shields.io/badge/GRUB-2-green) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

**LiquidGlass** is a sleek and minimalistic GRUB theme inspired by modern glassmorphic design. It emphasizes clean visuals, smooth animations, and transparent elements, making your boot menu stylish and user-friendly.

---

## Features

- Elegant glassmorphic design  
- Light and dark theme support  
- Easy installation and customization  
- Smooth hover animations  
- Compatible with GRUB 2  

---

## Installation

1. Copy the theme folder to the GRUB themes directory:

```bash
sudo cp -r LiquidGlass /boot/grub/themes/
```
2. Edit the GRUB configuration:

```bash
sudo nano /etc/default/grub
```

3. Add or modify the line:

```bash
GRUB_THEME="/boot/grub/themes/LiquidGlass/theme.txt"
```

4.Update GRUB:

```bash
sudo update-grub
```

Reboot your system and enjoy the new interface.
