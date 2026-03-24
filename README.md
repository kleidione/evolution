# Evolution-X for Redmi Note 15 5G (kunzite)

Evolution-X is an custom ROM with Google Pixel extras, designed to provide a clean, smooth, and feature-rich stock Android experience.

---

## 📱 Device Specifications

| Feature | Details |
| :--- | :--- |
| **Device** | Redmi Note 15 5G |
| **Codename** | `kunzite` |
| **Maintainer** | [@kleidione](https://github.com/kleidione) |
| **Android Version** | 17 (Cinnamon Bun) |

---

## 📥 Downloads

| File | Link |
| :--- | :--- |
| **Evolution-X ROM & Recovery** | [Download from SourceForge](https://sourceforge.net/projects/kunzite-files/files/evolution/) |

---

## 🖼️ Screenshots

<p align="center">
  <img src="./Screenshots/1.jpg" width="280" alt="Screenshot 1"/>
  <img src="./Screenshots/2.jpg" width="280" alt="Screenshot 2"/>
</p>

<p align="center">
  <img src="./Screenshots/3.jpg" width="280" alt="Screenshot 3"/>
  <img src="./Screenshots/4.jpg" width="280" alt="Screenshot 4"/>
</p>

<p align="center">
  <img src="./Screenshots/5.jpg" width="280" alt="Screenshot 5"/>
  <img src="./Screenshots/6.jpg" width="280" alt="Screenshot 6"/>
</p>

<p align="center">
  <img src="./Screenshots/7.jpg" width="280" alt="Screenshot 7"/>
  <img src="./Screenshots/8.jpg" width="280" alt="Screenshot 8"/>
</p>

<p align="center">
  <img src="./Screenshots/9.jpg" width="280" alt="Screenshot 9"/>
  <img src="./Screenshots/10.jpg" width="280" alt="Screenshot 10"/>
</p>

---

## ⚡ What's Working

- [x] Boot
- [x] Wi-Fi & Bluetooth
- [x] RIL (Calls, SMS, Mobile Data)
- [x] Camera & Camcorder
- [x] Audio / Media Playback
- [x] Fingerprint / Face Unlock
- [x] Sensors & GPS
- [x] VoLTE / VoWiFi

---

## 🛠️ Installation Guide

> ⚠️ **Warning:** Perform a full backup before proceeding. Factory Reset will wipe all internal storage.

1. **Prerequisites:**
   - Unlocked Bootloader.

2. **Flashing Recovery via Fastboot:**
   - Boot your phone into **Fastboot Mode** (`Volume Down + Power`).
   - Connect your device to the PC via USB and flash the recovery image:
     ```bash
     fastboot flash recovery recovery.img
     ```

3. **Flashing Steps:**
   - Boot into **Recovery Mode** (`Volume Up + Power`).
   - Go to **Factory Reset** > **Format Data / Factory Reset** and confirm.
   - Flash Regional Firmware:
   - Go to **Apply update** > **Apply from ADB**.
   - Sideload your regional firmware zip file:
     ```bash
     adb sideload /path/to/Firmware_region.zip
     ```
   - Reboot back into Recovery:
   - Return to the main menu, select **Advanced** > **Reboot to recovery**.
   - Flash Evolution-X ROM:
   - Once back in Recovery, go to **Apply update** > **Apply from ADB**.
   - Sideload the Evolution-X ROM zip file:
     ```bash
     adb sideload /path/to/EvolutionX-17.0-XXXXXXXX-kunzite-12.2-Community.zip
     ```
   - Select **Reboot system now** and enjoy Evolution-X!

---

## 📄 License & Credits

- **Evolution-X Team** for the base ROM.
