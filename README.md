# Version Control System (VCS) with GUI

A simple **Version Control System** built in **C++** with a **Python GUI frontend** using `customtkinter`.  
This project allows you to create repositories, add/update files, commit versions, revert files to previous commits, view file differences, and even execute basic commands via **voice input**.

---

## Features

- Initialize a repository (`init`)
- Add files to the repository (`add`)
- Update file content (`update`)
- Commit files with timestamped versions (`commit`)
- Revert files to a previous version (`revert`)
- Compare current file content with the latest committed version (`diff`)
- Voice command support for common operations (`init`, `add`, `update`, `commit`, `revert`)
- Modern GUI interface with **customtkinter**

---

## Technologies Used

- **Backend:** C++ (VCS logic)
- **Frontend:** Python 3.13
  - `customtkinter` for GUI
  - `tkinter` for widgets
  - `PIL` (Pillow) for image handling
  - `speech_recognition` for voice commands
  - `difflib` for diff functionality
- **File System:** Local directories and timestamped commits

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/version-control-system.git
cd version-control-system
