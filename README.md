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

## 📌 Project Overview

**ExpenseTracker Pro** is a lightweight Python-based solution engineered to simplify personal financial logging. Utilizing a modern graphical interface, the application enables users to record transactions seamlessly while automatically generating structured Excel reports for comprehensive data analysis.

<p align="center">
  <br>
  <img src="screenshots/Screenshot 2026-02-13 121607.png" width="31%" style="border-radius: 8px;" />
  <img src="screenshots/Screenshot 2026-02-13 121617.png" width="31%" style="border-radius: 8px;" />
  <img src="screenshots/Screenshot 2026-02-13 121647.png" width="31%" style="border-radius: 8px;" />
  <br>
  <sub><i>Interface Overview: Dashboard, Data Entry, and Generated Excel Reports</i></sub>
</p>

---

## 🚀 Key Features

* **Modern UI/UX:** Built with `CustomTkinter` to provide a high-DPI, responsive desktop experience.
* **Persistent Storage:** Automates the initialization and maintenance of a local `.xlsx` database.
* **Automated Analytics:** Features real-time calculation updates and native Excel formula integration.
* **Secure Pathing:** Implements `AppData/Roaming` protocols to ensure data persistence and system-wide write permissions.
* **Adaptive Theming:** Native support for Light and Dark modes to optimize user visibility.

---

## 🛠️ System Architecture

The application utilizes a modular architecture to decouple UI logic from file I/O operations:

* **Frontend Layer:** Employs `CustomTkinter` and `Tkinter` for event-driven interaction.
* **Data Layer:** Leverages `OpenPyXL` to manage the workbook lifecycle (Load/Edit/Save).
* **Path Management:** Utilizes `os` and `sys` modules to resolve absolute paths for both source execution and PyInstaller-frozen binaries.

---

## 📂 Data Access

In alignment with Windows security standards, the application stores the expense ledger within the user's protected application data directory.

**To access the Excel file manually:**
1. Press `Win + R`.
2. Execute the following command:
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

| **Python** | The Brains 🧠 |

| **CustomTkinter** | The Beauty ✨ |

| **Openpyxl** | The Excel Engine 📑 |

| **Pillow** | Icon Magic 🎨 |



---



<p align="center">

  <i>Created with ❤️ for the financial glow-up era.</i>

</p>
