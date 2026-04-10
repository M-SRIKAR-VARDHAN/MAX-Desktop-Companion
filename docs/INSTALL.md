# 📥 Installation Guide

> *"The wormhole is open. Step through."*

---

## System Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10 / 11 |
| **RAM** | 4 GB minimum |
| **Disk** | ~80 MB |
| **Python** | Not required (bundled) |
| **Internet** | Not required (100% offline) |
| **Admin** | Not required (some features work better with admin) |

---

## Step 1: Download

<a href="https://github.com/M-SRIKAR-VARDHAN/MAX-Desktop-Companion/releases/latest">
  ⬇️ Download the latest release from GitHub Releases
</a>

Or visit the [Official Website](https://max-desktop-companion.vercel.app/) and click the download button.

---

## Step 2: Run the Installer

1. Double-click `MAX_Setup_v2.0.0.exe`
2. If **Windows SmartScreen** appears:
   - Click **"More info"**
   - Click **"Run anyway"**

> **Why does SmartScreen warn me?**
> We're students and don't have a $300+ code signing certificate yet. MAX has been submitted to the **Microsoft Store** for official certification. This warning appears only once. MAX is 100% offline and collects zero data.

3. If your **antivirus** flags MAX:
   - MAX interacts with your OS to do things like kill frozen processes, take screenshots, and manage windows. Some antivirus software incorrectly flags these system hooks as suspicious.
   - You can safely add MAX to your antivirus exclusion/allow list.

---

## Step 3: Launch

After installation, MAX will appear on your desktop. He'll land on your taskbar and start exploring.

- **Right-click MAX** to open the radial menu
- **Press Ctrl+M** to find MAX instantly
- **Type cheat codes** directly on your keyboard (e.g., `rave`, `giant`, `gravity0`)

For all features and shortcuts, see the [Cheat Sheet](CHEAT_SHEET.md).

---

## Where MAX Stores Data

MAX stores all his data locally on your machine. Nothing is sent anywhere.

| What | Location |
|------|----------|
| Settings & config | `%APPDATA%\ProjectMAX\` |
| Logs | `%APPDATA%\ProjectMAX\max.log` |
| Screenshots | `Desktop\MAX Captures\` |

---

## Uninstalling MAX

MAX is a portable/lightweight companion. To remove him completely:

1. **Right-click MAX** → select **Quit**
2. **Delete the MAX folder** where you installed it
3. *(Optional)* Delete his data folder:
   - Press `Win + R`
   - Type `%APPDATA%\ProjectMAX`
   - Press Enter
   - Delete the `ProjectMAX` folder

That's it. No registry entries. No background services. No traces left behind.

---

## Troubleshooting

| Problem | Solution |
|---------|----------|
| MAX disappeared | Check the system tray (near the clock). Right-click the tray icon. |
| MAX froze | Press **Escape** or double-click MAX to stop the active feature. |
| Physics feel broken | Set Windows Display Scaling to **100%** and retry. |
| Feels laggy | Close heavy apps. MAX will detect it and offer to ease up. |
| Still broken | Restart MAX and attach logs from `%APPDATA%\ProjectMAX\max.log` when [filing an issue](https://github.com/M-SRIKAR-VARDHAN/MAX-Desktop-Companion/issues/new?template=bug_report.yml). |

---

<div align="center">

*"The crash landing was rough. But he survived. And now he refuses to leave."*

</div>
