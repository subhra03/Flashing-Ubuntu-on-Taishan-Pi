# Flashing-Ubuntu-on-Taishan-Pi
This project explains how to flash the Ubuntu 22.04 Preinstalled Desktop ARM64 image onto an SD card using Balena Etcher. The prepared SD card can then be used to boot Ubuntu on a Taishan Pi.

### 🛠 Requirements

**Software:**

* [Balena Etcher](https://www.balena.io/etcher) (Windows, macOS, or Linux)

**Hardware:**

* Computer (Windows/Linux/macOS)
* SD card (≥16GB recommended)
* SD card reader

**Image File:**

* `ubuntu-22.04-preinstalled-desktop-arm64-taishan.img`
  [Download Link](https://drive.google.com/file/d/13vBPck2h0YMKrjvbFPWSXtd08QmtlJQq/view)

---

### 🚀 Steps to Flash

1. **Install Balena Etcher**

   * Download from [balena.io/etcher](https://www.balena.io/etcher).
   * Install it for your OS.

2. **Insert SD Card**

   * Use an SD card reader to connect it to your computer.

3. **Open Balena Etcher**

   * Launch the application.

4. **Select Ubuntu Image**

   * Click **Flash from file**.
   * Choose `ubuntu-22.04-preinstalled-desktop-arm64-taishan.img`.

5. **Select Target Device**

   * Click **Select Target**.
   * Choose your SD card carefully (to avoid overwriting other drives).

6. **Flash the Image**

   * Click **Flash!**
   * Wait a few minutes (time depends on card/reader speed).

7. **Verify (Optional)**

   * Etcher automatically verifies after flashing to ensure no errors.

8. **Eject SD Card**

   * Safely remove the SD card.

---

### 🎯 Outcome

* The SD card now contains Ubuntu 22.04 ARM64 Desktop for Taishan Pi.
* Insert it into your board → boot Ubuntu.

---

### 📝 Notes

* Connect your Taishan Pi to a **monitor, keyboard, and mouse** for desktop use.
* For headless setups, you can configure SSH after first boot.

