# Folder Analyzer

A Python program that scans a chosen folder and provides key statistics such as:
- Total number of files
- Combined file size in megabytes (MB)
- Five most common file extensions

The script uses a simple graphical folder selection window powered by `tkinter`.

---

## 🧩 Features
- Select any folder on your computer using a GUI dialog.
- Automatically ignores hidden files (those starting with `.`).
- Displays total file count, folder size, and most frequent file types.
- Provides a clean, easy-to-read summary in the console.

---

## 🛠️ Requirements
- Python 3.10 or newer
- Standard Python libraries (`tkinter`, `os`, `collections`, `dataclasses`)  
  — no extra installation needed.

---

## ▶️ How to Run

1. Save the script as `folder_analyzer.py`.
2. Open your terminal or command prompt.
3. Navigate to the folder where the script is located.
4. Run:
   ```bash
   python folder_analyzer.py
