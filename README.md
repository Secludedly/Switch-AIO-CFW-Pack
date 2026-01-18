# Switch CFW Pack (Atmosphere + Hekate + ldm_mitm)

This repository provides a **ready-to-use, all-in-one pack** for Nintendo Switch Custom Firmware users.

It combines:
- **Atmosphere** (latest stable)
- **Hekate** (bootloader)
- **ldm_mitm** (sysmodule)

Designed for **easy copy & paste** directly to your SD card — no manual merging, no guessing.

---

## 📦 Included Components

| Component | Description |
|--------|------------|
| Atmosphere | Custom Firmware for Nintendo Switch |
| Hekate | Bootloader and payload launcher |
| ldm_mitm | Sysmodule required for layeredFS mod loading |
| Config Files | Preconfigured for common setups |

---

## ⚠️ Important Disclaimer

This repository **does not contain original work**.

All included projects belong to their respective authors:
- [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
- [Hekate](https://github.com/CTCaer/hekate)
- [ldm_mitm](https://github.com/Lusamine/ldn_mitm)

This pack is provided **for convenience only**.

---

## 🚀 Installation (Fresh or Existing Setup)

1. Power off your Switch
2. Insert your SD card into your PC
3. Backup your SD card (seriously, do it)
4. Extract the 7Z
5. Copy files to **root** of SD card
6. Overwrite everything, if asked
7. Safely eject the SD card through Windows before removing it
8. Place SD card back into the Switch
9. Connect Switch to PC via USB Type A to USB Type C
10. Place your jig into the right controller slot
11. Hold down VOL+ & Power for three seconds
12. Open [TegraRCMGUI](https://github.com/eliboa/TegraRcmGUI/releases)
13. Verify you see "RCM OK"
14. Inject the latest Hekate payload
15. Launch Atmosphere via Hekate
16. Done

That’s it. No extra steps.

---

## 🔄 Updating

When a new release is posted:
1. Download the latest 7Z
2. Copy to SD root
3. Overwrite when prompted
4. Done

---

## ❓ Who Is This For?

- New CFW users who want a clean setup
- Experienced users who don’t want to babysit updates
- People who are tired of merging folders manually

---

## 🧠 Notes

- This pack **does not include sigpatches**
- You are responsible for compliance with your local laws
- If you know what you’re doing, you can safely modify configs as needed

---

## ❤️ Credits

Massive thanks to the developers who make this possible.

---

## 📄 License

This repository redistributes unmodified releases from other projects.
Refer to each project’s individual license for terms.
