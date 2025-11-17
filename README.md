# Version Control System (VCS) with GUI

A lightweight **Version Control System** built with a **C++ backend** and a **Python GUI frontend** using `customtkinter`. This project enables users to **create repositories**, **add/update files**, **commit changes with timestamped versions**, and **revert files** to previous commits. It also provides a **diff feature** to compare the current file content with the latest committed version.

The Python GUI offers a modern interface with panels for **repositories**, **files**, **commit history**, and an **editable workspace**. Users receive **real-time suggestions** and can perform common VCS operations via **voice commands** (`init`, `add`, `update`, `commit`, `revert`).

This project demonstrates **core version control concepts**, **file management**, and integration of **GUI with backend logic**, making it ideal for beginners to explore **VCS functionality** and **interactive desktop applications**.

## 🚀 Features

- ✅ **Repository Management**: Initialize and manage multiple repositories
- ✅ **File Operations**: Add, update, and track files
- ✅ **Version Control**: Commit changes with timestamped versions
- ✅ **History Management**: Revert files to previous commits
- ✅ **Diff Visualization**: Compare current content with committed versions
- ✅ **Voice Commands**: Perform operations using voice recognition
- ✅ **Modern GUI**: Clean, intuitive interface with real-time suggestions

## 📋 Prerequisites

- Python 3.7+
- C++ Compiler (GCC, MinGW, or MSVC)
- Microphone (for voice commands)
  
## ⚡Usage
-Open or Create a Repository
Enter a repository name in the top input field and click Open/Create Repository.

-Add or Update Files
Enter the file name and click Add File or Update Content.

-Commit Changes
Edit content in the workspace and click Commit to save a version with a timestamp.

-Revert Files
Select a timestamp from the dropdown and click Revert.

-View File Differences
Click Show Diff to compare current content with the latest commit.

-Voice Commands
Click Voice Command and speak operations like init, add, update, commit, or revert.

## 💡Technical Details
Backend (C++)
Handles core VCS operations

File version management

Timestamp-based commit system

Diff calculation algorithms

Frontend (Python)
Modern GUI using CustomTkinter

Real-time file content editing

Voice recognition integration

Interactive diff visualization

## 🛠️ Installation

### 1. Clone the Repository
```bash
https://github.com/KamakshiPandey/Version-Control-System-VCS-.git
cd version-control-system
