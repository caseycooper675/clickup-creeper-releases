# ClickUp Creeper — Releases

This repository contains **official Windows installer releases** for **ClickUp Creeper**, an internal productivity tool used by the Kratos team.

✅ **Source code is not hosted here.**  
This repo exists only to provide a stable, public download location so the app can check GitHub Releases for updates without requiring GitHub authentication.

---

## What ClickUp Creeper Does (v0)

ClickUp Creeper helps users:
- See whether they have a **running ClickUp timer** at a glance (mini bar).
- Open the active task in ClickUp quickly (link-out).
- View their **assigned tasks** list.

**Safety-first design (v0):**
- **Read-only** with respect to ClickUp.
- No start/stop timer actions inside the app in v0.
- Actions are “view + link to ClickUp web” to avoid accidental changes.

---

## Download & Install

1. Open the **Latest Release**:
   - Click **Releases** on the right → open **Latest**
2. Download the installer named like:
   - `ClickUpCreeperSetup-X.Y.Z.exe`
3. Run the installer and follow the prompts.

### First-time setup
- Launch ClickUp Creeper from the Start Menu.
- Click **Connect ClickUp** and complete OAuth login in your browser.
- After connection, the app will show timer/task status when it can reach the internal backend.

---

## Updating

ClickUp Creeper checks this repository’s GitHub Releases to determine if updates are available.

- Use **Check for updates** inside the app (recommended), or
- Download and run the newest installer from the latest release.

Running the new installer will upgrade the existing installation.

---

## Release integrity (SHA256)

Some releases include a SHA256 checksum file:
- `ClickUpCreeperSetup-X.Y.Z.sha256.txt`

If present, it can be used to verify the installer download was not corrupted.

---

## Support (internal users)

If something isn’t working, please include:
- App version
- What you expected vs what happened
- A screenshot if possible
- Logs (if the app provides an “Open logs folder” menu item)

Internal contact: **[YOUR NAME / TEAM CONTACT]**

---

## Notes
- This is an internal tool. Installers are published here to make deployment and updates easy.
- If you are not part of the intended internal audience, you can ignore this repository.
