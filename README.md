# ToDo App — Offline CA Intermediate Study Planner & Task Manager

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(64--bit)-blue?logo=windows)](https://github.com)
[![License](https://img.shields.io/badge/License-Proprietary%20%2F%20Personal-green)](https://github.com)
[![Architecture](https://img.shields.io/badge/Offline-100%25%20Local%20SQLite-success)](https://github.com)

A modern, standalone desktop productivity suite and study planner designed for **CA Intermediate (January 2028)** aspirants and professionals. Everything runs locally on your PC — no cloud subscriptions, no external database, and zero tracking.

---

## 📥 Download Latest Version

👉 **[Download ToDo-App-Setup.exe (Latest Release)](../../releases/latest)**

*(Go to the **Assets** section under the latest release and click on `ToDo-App-Setup-x.x.x.exe`)*

---

## ✨ Key Features

- **Clean Slate Workspace:**
  - Starts with a clean, personal task dashboard — no pre-loaded clutter.
  - Optional profession study plan templates (e.g. CA Intermediate) can be imported in seconds via JSON restore.
- **Multi-Profile & Offline Authentication:**
  - Support for multiple independent profiles on a single computer.
  - Set your own custom name, email, and password during initial setup.
  - Each profile has its own password (hashed with secure `scrypt`), private tasks, routines, and category.
  - Built-in Super Admin controls to manage accounts and reset passwords.
- **Study Plan Templates & Checklists:**
  - CA Intermediate Jan 2028 template available with **785 curated tasks** and **1,673 checklist steps** across Group 1 & Group 2.
  - Phase-wise breakdown: First Reading, Detailed Revision, and Mock Test preparation.
  - Automated exam countdown to Paper 1.
- **Daily Habit & Routine Tracker:**
  - Track water intake, meals, sleep schedule, and morning routines with streak tracking.
- **100% Offline & Private:**
  - Stored in a lightweight local **SQLite** database (`%APPDATA%\ToDo App\todo.db`).
  - No internet required, zero telemetry, everything stays on your PC.
- **Backup, Restore & Template Import:**
  - Export your complete task and habit records as JSON anytime.
  - Import downloadable profession study templates with 1 click.
- **Theme Support:**
  - Clean, distraction-free Light and Dark modes.

---

## 💻 System Requirements

| Specification | Minimum Requirement | Recommended |
|---|---|---|
| **Operating System** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **Processor** | Intel Core i3 / AMD equivalent | Intel Core i5 / AMD Ryzen 5 or higher |
| **RAM** | 4 GB | 8 GB |
| **Disk Space** | 300 MB free space | 500 MB free SSD space |

---

## 🚀 Installation Guide (Step-by-Step)

### Step 1: Download
Download the latest installer file (`ToDo-App-Setup-x.x.x.exe`) from the [Releases](../../releases) tab.

### Step 2: Run the Installer
Double-click the downloaded `.exe` file.

> [!NOTE]
> **Windows SmartScreen Notice:**
> Because this is a newly released personal build without an expensive enterprise digital certificate, Windows Defender SmartScreen might display:
> 
> *"Windows protected your PC"*
> 
> 1. Click **More info** (अधिक जानकारी).
> 2. Click **Run anyway** (फिर भी चलाएं / Run anyway).
> 
> *The application is completely open and safe — all code runs locally and does not transmit data over the network.*

### Step 3: Complete Setup
1. Choose whether you want to install for your user account or customize the destination folder (Default: `%LOCALAPPDATA%\Programs\ToDo App`).
2. Select whether to create desktop and start menu shortcuts.
3. Click **Install**, then click **Finish** to launch ToDo App.

### Step 4: First-Time Setup
1. On first launch, enter your **Name**, **Email**, and choose your **Category / Profession** (e.g. General, CA, CS, CMA).
2. Choose a secure **Admin Password** (at least 8 characters).
3. Click **Set password and continue** — you'll enter your brand-new clean task dashboard.

---

## 📚 How to Import Profession Study Plans (Optional)

If you are preparing for **CA Intermediate (January 2028)**:
1. Download the [`ca-intermediate-jan2028-plan.json`](https://github.com/nidhi7733/ToDo-App-Releases/blob/main/ca-intermediate-jan2028-tracker.html) template file from this repository or the release assets.
2. Inside ToDo App, click on **Admin** (or **Profile**) in the sidebar.
3. Scroll to **Backup & Restore** and click **Restore from backup file**.
4. Select `ca-intermediate-jan2028-plan.json`.
5. All **785 tasks and 1,673 checklist steps** will be loaded instantly into your workspace!

---

## 🔄 How to Update to a Newer Version

When a new version is released:
1. Download the latest `ToDo-App-Setup-x.x.x.exe`.
2. Run the installer while closing the previous version.
3. Your data, tasks, habits, and user profiles are stored in `%APPDATA%\ToDo App\todo.db` outside the program folder, so **your existing data will remain completely intact and untouched during updates**.

---

## 🛠️ Data Location & Backups

- **Database Path:**  
  `%APPDATA%\ToDo App\todo.db`
- **Manual Backup:**  
  Inside the app, go to **Admin / Profile** -> **Backup & Restore** -> Click **Download backup JSON**. Save this file to your Google Drive or external drive periodically for safety.

---

## ❓ Frequently Asked Questions (FAQ)

<details>
<summary><b>1. Does this app require internet connection?</b></summary>
No. The desktop version is completely offline and does not require an internet connection once installed.
</details>

<details>
<summary><b>2. Can another user on my computer access my tasks?</b></summary>
No. Each profile requires its password to sign in. Switching between profiles is protected by password validation.
</details>

<details>
<summary><b>3. What happens if I forget my password?</b></summary>
If you are a standard user, ask the Super Admin profile on the same PC to reset your password from the Admin panel.
</details>

<details>
<summary><b>4. How do I uninstall the app?</b></summary>
Go to Windows <b>Settings > Apps > Installed apps</b>, search for <i>ToDo App</i>, and click <b>Uninstall</b>. Your database file is kept safe unless manually deleted.
</details>

---

## 📄 License & Credits

Created by **Premendra Nidhi**.  
Designed specifically for CA Intermediate Jan 2028 preparation and structured personal development.
