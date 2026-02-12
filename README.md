## 🚀 Actual firmware: 1.2.13 (22.09.2015)

This repository contains **only verified official Yi firmwares** for all series of Xiaomi cameras. These files have been checked to ensure they will not brick your device if installed correctly.

* 📜 [Firmware changelog](https://github.com/PJanisio/Xiaomi_Yi_firmware/blob/master/version%20changelog.md)
* 🔓 [Firmware hacks / Autoexec](https://github.com/PJanisio/Xiaomi_Yi_autoexec.ash)

---

## ⚠️ Important Warnings

> [!CAUTION]
> **ALWAYS CHECK MD5 HASH BEFORE INSTALLING NEW FIRMWARE!**
> A corrupted download can permanently damage your camera.

> [!IMPORTANT]
> Ensure your camera battery is **fully charged** or connected to a reliable power source before starting the update process.

---

## 🛠️ How to Install Firmware

Follow these steps carefully to update your Xiaomi Yi Action Camera.

### 1. Prepare your SD Card 💾
* Insert your MicroSD card into your computer.
* Format the card to **FAT32**.
* *Note: It is recommended to use a high-quality Class 10 card (4GB - 32GB).*

### 2. Download and Rename 📥
1. Download the correct `.bin` file for your camera serial number from the tables below.
2. **Verify the MD5 checksum** of the downloaded file against the table.
3. Rename the downloaded file (e.g., `Z22_1.2.13.bin`) to exactly:
   `firmware.bin`
4. Copy `firmware.bin` to the **root directory** of your MicroSD card.

### 3. Flash the Firmware ⚙️
1. Insert the MicroSD card into the camera.
2. Turn the camera **ON**.
3. The camera will start beeping and the LEDs will flash. **DO NOT TURN OFF THE CAMERA.**
   * 🔊 You will hear intermittent beeping.
   * 🔴 The red light will flash.
4. The process takes about **20-30 seconds**.
5. Once finished, the camera will emit a distinct sound (usually a triple beep) and automatically shut down or restart.

### 4. Clean Up 🗑️
1. Turn the camera on again.
2. Connect to the app to verify the version.
3. **Format the SD card** inside the camera (or delete the `firmware.bin` file manually) to prevent the camera from trying to update again every time you turn it on.

---