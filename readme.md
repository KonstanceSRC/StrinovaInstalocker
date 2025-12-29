<div align="center">

# 👾 Strinova Instalocker
### Powered by Jynx.cc

![Status](https://img.shields.io/badge/Status-Operational-blueviolet?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.0.0-9cf?style=for-the-badge&color=8a2be2)
![Language](https://img.shields.io/badge/Made%20With-Python-blueviolet?style=for-the-badge)

**Secure your main. Dominate the match.**

</div>

---

## 🔮 Overview

Welcome to the **Strinova Instalocker**, a specialized tool powered by the **Jynx.cc** framework. This script is designed to instantly lock in your chosen character the moment the selection screen appears, ensuring you never miss out on playing your main.

> **⚠️ IMPORTANT NOTE:**
> The setup process for this tool is **a bit long and requires attention to detail**. You need to configure coordinate data specific to your screen resolution. However, once set up, it is **extremely useful** and works consistently!

## ⚡ Features

* **Instant Locking:** Millisecond reaction time to beat other players.
* **Jynx.cc Optimization:** Lightweight and efficient code structure.
* **Fully Customizable:** Works for any agent (with proper config).
* **Purple UI:** A clean, terminal-based aesthetic fitting the Jynx ecosystem.

## 🛠️ Prerequisites

Before you begin, ensure you have the following:

1.  **Python 3.10+** installed.
2.  **Strinova** installed and running in *Windowed Borderless* or *Windowed* mode (recommended for initial setup).
3.  A text editor (VS Code, Notepad++, etc.).

## ⚙️ Installation & Setup (The Long Part)

Follow these steps carefully to ensure the locker works on your specific monitor.

### 1. Clone the Repository

"git clone [https://github.com/yourusername/strinova-instalocker.git](https://github.com/yourusername/strinova-instalocker.git)
cd strinova-instalocker"



2. Install Dependencies
Bash

pip install -r requirements.txt

3. Configuration (Crucial Step)

You must map the screen coordinates for the agent you want to lock.

    Open the config.json file.

    Run the helper script get_coords.py included in this folder.

    Find Agent Location: Hover your mouse over the specific agent icon in the game lobby and press Enter in the terminal to log the X/Y coordinates.

    Find Lock Button: Hover over the "Lock In" button and log those coordinates.

    Paste these X and Y values into your config.json file under the corresponding agent name.

    Tip: Do not change your game resolution after setting this up, or you will have to redo the coordinates.

🚀 Usage

    Launch Strinova.

    Open your terminal and run:
    Bash

    python main.py

    Select your desired agent from the Jynx menu.

    Queue for a match.

    Sit back—the tool will handle the selection for you.

💜 Disclaimer

This software is for educational purposes. Use it responsibly. Jynx.cc is not affiliated with the developers of Strinova.

<div align="center">

Website • Discord • Support

Made with 💜 by Jynx.cc
