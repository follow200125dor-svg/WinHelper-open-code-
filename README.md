# WinHelper-open-code-

# 🚀 WinHelper — Your Windows Helper

Hello! This is your Windows helper. It has everything for comfortable PC use.  
**PLEASE: Read this README carefully before using.**

---

## 📋 What is WinHelper?

WinHelper is a launcher that creates **workspaces** — separate applications with many built-in tools.  
Each workspace works independently and stores its data in a separate `YourData_*` folder.

Think of workspaces as rooms: you can have one for school, one for personal projects, one for family.  
Each room has its own tasks, notes, calendar, files — nothing gets mixed up.

---

## 🔧 Features of each Workspace

| Tab | What it does |
|-----|-------------|
| 📋 **Tasks** | Create to-do list. Set time reminder. Mark as done. Edit or delete tasks. |
| 📝 **Notes** | Write text notes. Bold and Italic formatting. Save to list. Export as `.txt` file. |
| 📅 **Calendar** | Full calendar with Russian months. Add events with time. Enable reminders. See today's events. |
| 🌤 **Weather** | Enter city name (example: London, Moscow, Tokyo). Shows temperature, humidity, wind speed. Uses wttr.in free API. |
| 🌍 **Translator** | Translate between 29 languages. Select from and to language. Powered by Google Translate. |
| 🔢 **Calculator** | Simple calculator with buttons. Supports +, -, *, /. Clear and backspace. |
| ⏱ **Timer** | Stopwatch — counts up from zero. Countdown — set seconds, counts to zero with alert. Stop and Reset buttons. |
| ⏰ **Alarm** | Set alarm with hour:minute and message. Turn on/off. Delete alarms. Checks every 30 seconds. |
| 📊 **Table** | Spreadsheet like Excel. Add rows and columns. Edit cells. Save to file. |
| 📁 **Files** | File manager like WinRAR. Shows ALL drives (C:, D:, etc). Open files, folders. Download/Upload files. Create folders. Shredder for permanent delete. Extract ZIP archives. |
| 🎵 **Player** | Choose audio or video file. Play with system default player. |
| 🎨 **Draw** | White canvas for drawing. Choose color (name or HEX). Choose brush size. Clear canvas. |
| 💻 **CMD** | Built-in command line. Type any Windows command. See output. Timeout after 10 seconds. |
| 💬 **Chat** | Send messages visible in other workspaces. Shows last 50 messages with time and workspace name. |
| 🔒 **Password** | Set password to protect workspace. Asked on every open. Can remove password. |
| 🎨 **Theme** | Switch between Dark and Light theme. Changes all colors instantly. |
| 📦 **Backup** | Export all workspace data to ZIP file. Import from ZIP to restore. |
| 🏷 **Icon** | Choose icon for workspace title bar. 12 emoji icons to pick from. |

---

## 🛠 How to Install

### Automatic installation (recommended)
1. Go to `python_installer/` folder
2. Double-click `python_installer3.14.2.cmd`
3. Wait — it will download and install Python 3.14.2 + all needed libraries
4. Done!

### Manual installation
1. Download Python 3.14.2 from [python.org](https://python.org)
2. During installation check **"Add Python to PATH"**
3. Open CMD (Win+R, type `cmd`, Enter)
4. Type: `pip install deep-translator`
5. Done!

---

## 🚀 How to Run

1. Open CMD in the project folder
2. Type: `python app/WinHelper.py`
3. Or double-click `app/WinHelper.py` if Python is associated with `.py` files

---

## 📁 How to Use

### Create a Workspace
1. Launch WinHelper
2. Click **"➕ Create"**
3. Enter a name (example: "School", "Projects", "Family")
4. Click OK
5. New workspace appears in the list
6. A `.py` file and `YourData_Name` folder are created

### Open a Workspace
1. Select workspace in the list
2. Double-click it
3. Launcher hides, workspace opens
4. Use tabs to switch between tools
5. Close workspace — launcher comes back

### Delete a Workspace
1. Select workspace in the list
2. Click **"🗑️ Delete"**
3. Confirm deletion
4. `.py` file and data folder are removed

---

## 📊 Project Structure
WinHelper/
├── README.md ← this file
├── python_installer/
│ └── python_installer3.14.2.cmd ← installs Python + libraries
└── app/
└── WinHelper.py ← main launcher

text

After creating workspaces:
WinHelper/
├── ... (same as above)
├── YourData/ ← launcher data
├── YourWorkspace.py ← workspace file
└── YourData_YourWorkspace/ ← workspace data

text

---

## ❓ FAQ

**Q: Workspace won't open?**  
A: Make sure Python is installed. Run `python_installer3.14.2.cmd` first.

**Q: Translator doesn't work?**  
A: Internet connection required. Library `deep-translator` must be installed.

**Q: Weather shows error?**  
A: Check city name spelling. Internet connection required.

**Q: How to backup my data?**  
A: Use Export ZIP in workspace menu (📦 Data → Export ZIP).

**Q: Is my data safe?**  
A: All data is stored locally in `YourData_*` folders. Nothing is sent anywhere.

---

## 👤 Author

**Mark**, 10 years old

> "I love coding with AI but I don't know how myself" — and now look what I built! 🔥

---

## 📄 License
Free  code-modify and share
