# NeuroArchiver Enterprise 🧠📦

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-yellow.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)
![Status](https://img.shields.io/badge/status-Active-brightgreen.svg)

**NeuroArchiver** is a next-generation, open-source file compression suite built with Python. Designed to rival WinRAR and 7-Zip, it combines military-grade encryption, intelligent compression algorithms, and a modern dark-mode GUI into a single powerful tool.

![App Screenshot](assets/screenshot_main.png)
*(Note: Replace this line with a screenshot of your app running)*

---

## ✨ Key Features

### 🚀 High-Performance Compression
*   **Multi-Core Engine:** Utilizes 100% of your CPU threads for blazing-fast compression.
*   **Format Support:** Create `.7z`, `.zip`, `.tar`, and `.wim` archives.
*   **Intelligent Analysis:** Scans files before compression to suggest the best algorithms (LZMA2, Deflate, Store).
*   **Solid Compression:** Packs files as a single block for maximum size reduction.

### 🔐 Military-Grade Security
*   **AES-256 Encryption:** Protect your data with the strongest encryption standard available.
*   **Header Encryption:** Hide filenames inside archives so prying eyes can't even see the table of contents.
*   **Secure Wipe:** Option to shred original files after successful archiving.

### 🛠️ Advanced Tools
*   **Volume Splitting:** Split large files into chunks (100MB, 700MB, 4GB) for email or FAT32 drives.
*   **Integrity Verification:** Built-in hash checking to detect corrupt archives.
*   **System Benchmark:** Test your PC's compression speed (MB/s) with the built-in stress test tool.
*   **SFX Stub:** Generate Self-Extracting Executables (`.exe`).

### 🎨 Modern Experience
*   **Beautiful UI:** Built with `CustomTkinter` for a sleek, dark-mode interface.
*   **Drag & Drop:** Fully supports dragging files from Windows Explorer.
*   **Context Menu:** Includes scripts to add "NeuroArchiver" to your Windows Right-Click menu.

---

## 📦 Installation

### Prerequisites
*   Python 3.8 or higher
*   PIP (Python Package Manager)

### 1. Clone the Repository
```bash
git clone https://github.com/siyamex/NeuroArchiver.git
cd NeuroArchiver
