# File Organizer 

## Overview
**File Organizer Pro** is a Python script designed to automatically organize files in a specified directory into categorized subfolders based on their file extensions. This tool is perfect for cleaning up cluttered directories, such as your "Downloads" folder, by sorting files into categories like Images, Music, Videos, Documents, Code, and Other.

---

## Features
- **Automatic File Sorting**: Automatically moves files into predefined folders based on their extensions.
- **Customizable Categories**: Easily add or modify file extensions and folder names to suit your needs.
- **Directory Creation**: Creates subdirectories if they don't already exist.
- **User-Friendly Logs**: Prints logs to the console to keep track of file movements.

---

## Supported File Types
The script currently supports the following file types:
- **Images**: `.jpg`, `.jpeg`, `.png`, `.gif`
- **Music**: `.mp3`, `.wav`, `.aiff`
- **Videos**: `.mp4`
- **Documents**: `.txt`, `.pdf`, `.docx`, `.doc`
- **Code**: `.py`, `.html`, `.css`, `.js`, `.md`
- **Other**: Any file type not listed above will be moved to the "Other" folder.
---
## How It Works
1. The script checks for the existence of subdirectories (e.g., Images, Music, Videos, etc.) in the specified directory.
2. If the subdirectories don't exist, it creates them.
3. It iterates through all files in the directory, identifies their extensions, and moves them to the appropriate subfolder.
4. Files with unsupported extensions are moved to the "Other" folder.

---
