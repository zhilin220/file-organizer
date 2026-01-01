# File Organizer

A simple Windows utility (no installation required) to organize files in a folder by type.  
This tool scans a folder and moves files into categorized subfolders such as **Images**, **Documents**, **Videos**, **Audio**, **Programming**, **Applications**, and more.

This repository also includes a pre-built executable that you can download without installing Python.

---

## 📦 Features

- Recursively organizes files in any folder
- Sorts by file extension:
  - Images (`jpg`, `png`, `webp`, `heic`, ...)
  - Documents (`pdf`, `docx`, `txt`, `.xlsx`, ...)
  - Videos (`mp4`, `mkv`, `webm`, ...)
  - Audio (`mp3`, `wav`, `ogg`)
  - Programming files (`py`, `html`, `css`, ...)
  - Applications (`exe`, `msi`, ...)
- Unrecognized file types go into an **Others/** folder
- Safely re-runnable — doesn’t reorganize already organized files
- Allows skipping designated folders
- Portable Windows executable (no installation required)

---

## 📥 Download

Get the latest release here:

👉 https://github.com/zhilin220/file-organizer/releases/tag/v1.0

Download the ZIP file and extract it to any location.

---

## ▶️ How to Use (Windows)

1. Extract the downloaded ZIP file
2. Double-click the `file_organizer.exe`
3. Select a folder you want to organize
4. Click **Organize Files**
5. Done!

No installation needed — just run and go.

---

## 🛠️ How It Works

This program uses Python’s `os` and `shutil` modules to scan folders and move files into categorized subfolders based on file extensions.

The organization happens recursively, but it avoids going into existing destination folders to prevent infinite loops.

---

## ⚠️ Notes & Tips

- Recommended for personal or work folders (e.g., messy Downloads, Documents)
- Always try it first on a **test folder** to see how it behaves
- If your organization needs change (e.g., new file types), you can update the category lists in the source code

---

## 🧠 Want to Customize?

You can modify the source Python script in this repo:

- Add or remove categories
- Change how duplicates are handled
- Add a “dry run” preview mode
- Add logging or an enhanced GUI

---

## 📜 License

This project is open source and free to use.

---

## 👋 About

Created by **zhilin220** — a Python learner building real-life productivity tools.

Happy organizing!

