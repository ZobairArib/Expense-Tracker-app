<h1 align="center">ExpenseTracker Pro</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/GUI-CustomTkinter-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data-OpenPyXL-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows" />
</p>

<p align="center">
  <strong>A streamlined desktop application for local expense management and automated Excel reporting.</strong>
</p>

---

---

## 📌 Project Overview

ExpenseTracker is a lightweight Python application designed to simplify personal financial logging. By leveraging a modern graphical interface, it allows users to record transactions and automatically generate structured Excel reports for long-term data analysis.

<p align="center">
  <br>
  <img src="screenshots/dashboard.png" alt="ExpenseTracker Pro Dashboard", width="700"> 
  <br>
  <em>The sleek Dark Mode interface of ExpenseTracker Pro</em>
</p>
---

## 🚀 Key Features

* **Modern UI/UX:** Developed with `CustomTkinter` for a native, high-DPI desktop experience.
* **Persistent Storage:** Automatically initializes and updates a local database in `.xlsx` format.
* **Automated Calculations:** Features real-time sum updates and Excel-native formula integration.
* **Secure Pathing:** Utilizes `AppData/Roaming` protocols to ensure write permissions and data persistence across sessions.
* **Theme Synchronization:** Supports both Light and Dark modes for optimized visibility.

---

## 🛠️ System Architecture



The application follows a modular structure to separate UI logic from file I/O operations:
* **Frontend:** CustomTkinter & Tkinter for responsive event handling.
* **Data Layer:** OpenPyXL manages the workbook lifecycle (Load/Edit/Save).
* **Path Management:** Uses `os` and `sys` to handle absolute paths for both script execution and PyInstaller-frozen binaries.

---

## 📂 Data Access

To comply with Windows security standards, the application stores the expense ledger in the user's protected application data folder.

**To access the Excel file manually:**
1. Press `Win + R`.
2. Enter the following command:
   ```bash
   %appdata%\ExpenseTracker
## 📦 Dependency Management

To ensure the application functions correctly, the following core libraries must be installed. You can set up your environment manually via the terminal:

1. **Open a terminal or command prompt.**
2. **Execute the following command:**
   ```bash
   pip install customtkinter openpyxl Pillow

## 🛠️ Tech Stack

| Tool | Purpose |
| :--- | :--- |
| **Python** | The Brains 🧠 |
| **CustomTkinter** | The Beauty ✨ |
| **Openpyxl** | The Excel Engine 📑 |
| **Pillow** | Icon Magic 🎨 |

---

<p align="center">
  <i>Created with ❤️ for the financial glow-up era.</i>
</p>
