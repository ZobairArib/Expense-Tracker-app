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

ExpenseTracker is a lightweight Python application designed to simplify personal financial logging. By leveraging a modern graphical interface, it allows users to record transactions and automatically generate structured Excel reports for long-term data analysis.



---

## 🚀 Key Features

* **Modern UI/UX:** Developed with `CustomTkinter` for a native, high-DPI desktop experience.
* **Persistent Storage:** Automatically initializes and updates a local database in `.xlsx` format.
* **Automated Calculations:** Features real-time sum updates and Excel-native formula integration.
* **Secure Pathing:** Utilizes `AppData/Roaming` protocols to ensure write permissions and data integrity.
* **Theme Synchronization:** Supports both Light and Dark modes for optimized visibility.

---

## 📦 Dependency Management

To ensure the application functions correctly, the following core libraries must be installed. You can set up your environment manually via the terminal:

1. **Open a terminal or command prompt.**
2. **Execute the following command:**
   ```bash
   pip install customtkinter openpyxl Pillow
