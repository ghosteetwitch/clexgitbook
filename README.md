# ✅ Required Things for Windows Format, BIOS Update, and Installation

---

## 🖥 Hardware

- 💻 PC / Laptop
- 🔌 Power adapter (for laptops — keep it plugged in!)
- 🖱 Keyboard & Mouse

---

## 💾 Storage

- 📦 **16GB or larger USB flash drive** (for Windows install)
- 📦 Optional second USB flash drive (for BIOS update file)
---



# 💥 Windows Format, BIOS Update, and Install Guide

> ⚠ **WARNING:**  
> This will **erase all your data**. Backup everything important before you proceed.

---

## ⚔ Step 1: Backup & Prepare

- Backup all **files, photos, passwords, licenses, encryption keys**.
- Download Windows ISO:  
  [Windows 10/11 Download](https://www.microsoft.com/en-us/software-download/windows10)

- Download Rufus (bootable USB tool):  
  [Rufus Download](https://rufus.ie)

- Get a **16GB+ USB stick**.

---

## ⚙ Step 2: Make a Bootable USB

1. Plug in the USB.
2. Open **Rufus** → set:
   - **Device** → your USB  
   - **Boot selection** → Windows ISO  
   - **Partition scheme** → GPT (for UEFI BIOS)  
   - **File system** → NTFS  
   
3. Hit **START** → it will wipe the USB and make it bootable.

---

## 💥 Step 3: Enter BIOS

- Restart PC → **spam the bios keys**:
  - ASUS → Del  
  - MSI → Del  
  - Gigabyte → Del  
  - Dell → F2  
  - HP → F10  
  - Lenovo → F1 / F2

---

## 🔥 Step 4: Update BIOS

1. Go to motherboard/laptop website → download latest **BIOS file**.
2. Extract ZIP → copy `.CAP` / `.ROM` / `.BIN` file to **FAT32 USB**.
3. In BIOS → find:
   - EZ Flash (ASUS)  
   - M-Flash (MSI)  
   - Q-Flash (Gigabyte)  
   - Instant Flash (ASRock)

4. Select BIOS file → **start update**.

⚡ **DO NOT TURN OFF PC.**

---

## 💿 Step 5: Install Windows

1. Boot from USB.
2. Select **Custom Install**.
3. Delete old partitions (C:, Recovery, System).

---

## ⚙ Step 6: Install Drivers

- Motherboard site → **chipset, LAN, audio**.
- GPU site → **NVIDIA / AMD / Intel drivers**.
- Windows Update → **Check for updates** repeatedly.

---
