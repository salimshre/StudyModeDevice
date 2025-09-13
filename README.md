# FocusPhone 🔒➡️📵

A complete toolkit and guide to transform your Android phone into a focused, distraction-free device for studying, deep work, and digital wellbeing. Works for both **rooted** and **non-rooted** devices.

## ✨ What This Does

Tired of getting distracted by social media, YouTube, and other apps? This project helps you convert your phone into a minimalist tool by:

*   **Removing or restricting** distracting applications.
*   **Blocking internet access** for time-wasting apps (root required).
*   **Blocking ads and distracting websites** system-wide (root required).
*   **Providing guides** for non-rooted devices using standard apps.
*   Applying **focus-oriented launchers and settings**.

## 📁 Repository Contents

| File | Description |
| :--- | :--- |
| `DOCUMENTATIONS.docx` | The main guide. Covers flashing Magisk, debloating, and configuring your device for focus. |
| `afwall-backup-*.json` | Configuration backups for AFWall+ (Firewall). Use to quickly apply internet block rules. |
| `adaway-backup.json` | Hosts file backup for AdAway to block ads and distracting websites. |

## 🚀 Quick Start Guide

### For Rooted Users (Full Power)

1.  **Root Your Device:** Follow the guide in `DOCUMENTATIONS.docx` to install Magisk via TWRP recovery.
2.  **Install Essential Apps:** Install **AFWall+** (Firewall) and **AdAway** (Ad Blocker).
3.  **Restore Configurations:**
    *   **AFWall+:** Go to `Settings -> Backup & Restore` and import the `afwall-backup-*.json` file. Apply the rules.
    *   **AdAway:** Go to `Settings -> Backup & Restore` and import the `adaway-backup.json` file. Enable ad blocking.
4.  **Debloat:** Use a root app like **Titanium Backup** to remove system apps you don't need (e.g., Facebook, Instagram).
5.  **Set Up a Minimal Launcher:** Install a launcher like **Olauncher** or **Niagara Launcher** to hide all apps except your essential tools.

### For Unrooted Users (Still Powerful)

1.  **Use Built-in Tools:** Use **Digital Wellbeing** (Android) or **Screen Time** (iOS) to set app timers and focus mode.
2.  **App Blockers:** Install non-root apps like **AppBlock**, **Forest**, or **StayFocusd** to block distracting apps on a schedule.
3.  **Browser Extensions:** On mobile browsers like Kiwi (supports Chrome extensions), install **uBlock Origin** and **BlockSite**.
4.  **Minimal Launcher:** Install a minimal launcher from the Play Store (e.g., **Before Launcher**, **Olauncher**) to reduce visual clutter.

## 🔧 Tools & Apps You'll Need

*   **Root Required:** Magisk, AFWall+, AdAway, Titanium Backup, Greenify.
*   **No Root Required:** AppBlock, Forest, StayFocusd, Digital Wellbeing, Minimal Launchers (Olauncher, Niagara).

## 🤝 Contributing

Found a better way to block distractions? Have a great config to share?
Contributions are welcome! Please feel free to:
1.  Fork this project.
2.  Create a feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

## ⚠️ Disclaimer

This guide is provided for educational purposes. Modifying your device's software (especially rooting) can void your warranty and has risks, including the possibility of rendering your device inoperable. Proceed at your own risk. The maintainers of this repository are not responsible for any damage to your device.

---

**Turn your phone into a tool, not a distraction.** Happy Focusing!
