# Version Control System (VCS) with GUI

A lightweight **Version Control System** built with a **C++ backend** and a **Python GUI frontend** using `customtkinter`. This project enables users to **create repositories**, **add/update files**, **commit changes with timestamped versions**, and **revert files** to previous commits. It also provides a **diff feature** to compare the current file content with the latest committed version.

The Python GUI offers a modern interface with panels for **repositories**, **files**, **commit history**, and an **editable workspace**. Users receive **real-time suggestions** and can perform common VCS operations via **voice commands** (`init`, `add`, `update`, `commit`, `revert`).

This project demonstrates **core version control concepts**, **file management**, and integration of **GUI with backend logic**, making it ideal for beginners to explore **VCS functionality** and **interactive desktop applications**.

---

## Installation

1. **Install Python dependencies**  

---
pip install customtkinter pillow SpeechRecognition
## Installation

1. **Clone the repository**  
```bash
git clone https://github.com/yourusername/version-control-system.git
cd version-control-system
Install Python dependencies

bash
Copy code
pip install customtkinter pillow SpeechRecognition
Compile the C++ backend
Open init.cpp in your C++ IDE or use g++:

bash
Copy code
g++ init.cpp -o myvcs.exe
Ensure myvcs.exe is in the same directory as vcs_app.py.

Run the GUI

bash
Copy code
python vcs_app.py
Usage
Open or create a repository
Enter a repository name in the top input field and click Open/Create Repository.

Add or update files
Enter the file name and click Add File or Update Content.

Commit changes
Edit content in the workspace. Click Commit to save a new version with a timestamp.

Revert files
Select a timestamp from the dropdown and click Revert to restore the file.

View file differences
Click Show Diff to see changes between the latest commit and current content.

Voice Commands
Click Voice Command and speak operations like init, add, update, commit, or revert.

Project Structure
csharp
Copy code
version-control-system/
│
├── vcs_app.py            # Python GUI frontend
├── init.cpp              # C++ backend for VCS
├── myvcs.exe             # Compiled C++ executable
├── icons/                # GUI icons
│   ├── icons8-page-64.png
│   ├── icons8-voice-50.png
│   └── icons8-change.gif
└── README.md             # Project documentation
Features
Initialize a repository (init)

Add files to the repository (add)

Update file content (update)

Commit files with timestamped versions (commit)

Revert files to a previous version (revert)

Compare current file content with the latest committed version (diff)

Voice command support for common operations

Modern GUI interface with real-time suggestions

Improvements / Planned Features
Branching and merging support

Better diff visualization with syntax highlighting

Cross-platform support (Linux/macOS)

Undo/redo functionality in workspace

Save voice command history

Screenshots

Main GUI of the Version Control System showing workspace, files, and commit history.


