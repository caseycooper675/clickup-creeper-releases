# ClickUp Creeper — Releases

This repository contains **official Windows installer releases** for **ClickUp Creeper**, an internal productivity tool.

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

## Support (internal users only)

If something isn’t working, please include:
- App version
- What you expected vs what happened
- A screenshot if possible
- Logs (if the app provides any)

Send items to developer over email or teams.

---

## Versioning policy

ClickUp Creeper uses Semantic Versioning (`MAJOR.MINOR.PATCH`).

- **MAJOR**: Breaking changes (things that require users/admins to change config, URLs, or update procedures).
- **MINOR**: New features that are backward-compatible (no required changes for users).
- **PATCH**: Bug fixes and small improvements that do not change behavior in incompatible ways.

Examples:

v0.1.0 = first team deploy (“works end-to-end”)

v0.1.1 / v0.1.2 = early hotfixes

v0.2.0 = first meaningful feature expansion

### Pre-1.0 versions
Until `v1.0.0`, the project is considered “stabilizing.” We will still follow SemVer, but **minor versions may include larger internal changes** while keeping the app usable for the team.

---

## Notes
- This is an internal tool. Installers are published here to make deployment and updates easy.
- If you are not part of the intended internal audience, you can ignore this repository.
