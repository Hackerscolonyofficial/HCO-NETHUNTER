The most powerful Kali NetHunter installer for Termux.
Built with a stunning Rich UI by [HCO]

## ⚙️ Features

- [x] Rich-powered banner and UI
- [x] Auto-detects device architecture
- [x] Downloads and extracts the official Kali NetHunter RootFS
- [x] Creates easy-to-use `nethunter` and `nh` launchers
- [x] Automatically sets permissions and sudo access
- [x] Fixes UID for non-root Android Termux compatibility

## ⚠️ Disclaimer

> This tool is only for **ethical hacking** and **educational** purposes.  
> Any misuse of this tool is **strictly prohibited**.  
> The authors are **not responsible** for any illegal use.

## 🚀 Installation

Open **Termux** and run the following:

```python
apt update && apt upgrade -y
pkg install git python proot-distro wget tar -y
pip install pyfiglet rich requests 
git clone https://github.com/...
cd ..
python3 HCO-NETHUNTER.py
```
# Kali-menu error solution 
```
mkdir -p /usr/share/kali-menu

echo -e '#!/bin/sh\nexit 0' > /usr/share/kali-menu/update-kali-menu

chmod +x /usr/share/kali-menu/update-kali-menu
```

# Kex error solution 

```
rm -f /usr/bin/perl
find /usr/bin -type f -executable -name 'perl*'
ln -s /usr/bin/perl5.40-aarch64-linux-gnu /usr/bin/perl
perl -v
```

```
mkdir -p /root/.config/tigervnc
mkdir -p /root/.vnc
```
**now run**
```
kex
```
---

# ✅ Usage Instructions

After installation, use the following commands inside Termux:

nethunter             # Start Kali CLI
nethunter kex passwd  # Set GUI (KeX) password
nethunter kex &       # Start GUI mode
nethunter kex stop    # Stop GUI
nethunter -r          # Start as root user
nh                    # Shortcut alias
-------------------------------------

# 📷 Interface Preview

> All banners, prompts, and panels are styled with the Rich library for a clean and modern look


![Screenshot_20250531-094321](https://github.com/user-attachments/assets/835ddc4d-c2a3-4bcf-8346-2af5d532af53)

--------------------------------------

# 🤖 Requirements

Android with Termux

12GB+ free space

Internet connection

Python 3.x
-----------------------

# 👨‍💻 Author & Credits

Tool by: [HCO]

Channel: [YouTube –Hackers COLONY OFFICIAL](https://youtube.com/@hackers_colony_tech)

GitHub: [follow](https://github.com/Hackerscolonyofficial)

WhatsApp Community: [Join Us](https://chat.whatsapp.com/HB03qdGSK5K17wmQ5FXGiP)
