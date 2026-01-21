# LastLook v2 — "Gold Mine" (v1.0.0)

**The high-performance Personal Relationship Manager for DITs and Content Creators.**

LastLook v2 is a professional data management tool designed to bridge the gap between high-speed transfers and human-readable verification. Built with a **Rust-powered Tauri backend** and a **React frontend**, it offers a "Gold Mine" of features for users who cannot afford to lose a single frame of data.

---

## 🚀 Key Features

* **Hybrid Performance:** Leveraging Rust for heavy-duty I/O and React for a modern, snappy interface.
* **xxHash-64 Integrity:** Every file is verified with real-time checksums during transfer to ensure 100% data parity.
* **DIT Workflow Tools:** Recursive folder stats, "Select All Missing" logic, and automated transfer logs.
* **Smart Media Engine:** Built-in FFmpeg sidecar for lightning-fast video thumbnails and metadata inspection (Codec, FPS, Resolution).
* **The "Red Zone" Safety:** Intelligent guardrails prevent accidental data loss with "Destructive Cancellation" and verified-only delete permissions.

---

## 📦 Installation

1.  Navigate to the [**Releases**](https://github.com/valiantCreator/LastLook-v2-Distribution/releases) section of this repository.
2.  Download the latest `.msi` (Windows Installer) or `.exe` (NSIS) for version **v1.0.0**.
3.  Run the installer and follow the on-screen prompts.
4.  *Note: All necessary binaries (FFmpeg/FFprobe) are bundled within the installer; no additional setup is required.*

---

## 🛠 Tech Stack

* **Backend:** Tauri (Rust)
* **Frontend:** React (TypeScript) + Tailwind CSS v4.0
* **State:** Zustand
* **Media Engine:** FFmpeg Sidecar Pattern

---

## 📝 Reporting Issues

This repository is for **distribution and feedback only**. If you encounter bugs or have feature requests:
1.  Check the [Issues](https://github.com/valiantCreator/LastLook-v2-Distribution/issues) tab.
2.  Open a new issue with your OS version and steps to reproduce the bug.
3.  Attach any relevant transfer logs (found in your destination folder as `Log_YYYY-MM-DD.txt`).

---

## ⚖️ Safety & Permissions

LastLook v2 requests granular OS permissions to perform its core functions safely:
* **File System:** To read source files and write verified copies/manifests.
* **Shell:** To execute the bundled FFmpeg sidecar for media previews.
* **Window Attention:** To flash the taskbar/dock upon successful batch completion.

---
*Created by [valiantCreator](https://github.com/valiantCreator). SOMEBODY CHECK THEIR HARD DRIVE*
