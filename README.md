<div align="center">

# ⚡ PN VPS

**Premium Hosting Panel — Deploy & run Python, Node.js, Shell scripts on a real VPS.**

A single-file Flask control panel with a smooth, modern UI. Upload scripts, install modules, stream live logs, and manage users with time-bound or lifetime accounts.

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-3.x-000000?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![License](https://img.shields.io/badge/License-MIT-7c3aed?style=flat-square)](LICENSE)
[![Deploy](https://img.shields.io/badge/Deploy-Railway-db2777?style=flat-square&logo=railway&logoColor=white)](https://railway.app)

</div>

---

## 📖 Table of Contents

- [Features](#-features)
- [Screenshots](#-screenshots)
- [Quick Start](#-quick-start)
- [Project Structure](#-project-structure)
- [Configuration](#-configuration)
- [Usage Guide](#-usage-guide)
- [Deployment](#-deployment)
- [Security Notes](#-security-notes)
- [Tech Stack](#-tech-stack)
- [License](#-license)

---

## ✨ Features

| Feature | Description |
|---|---|
| 🚀 **Instant Deploy** | Upload `.py`, `.js`, `.sh`, `.mjs` files and run them on real Railway servers |
| 📦 **Module Install** | Run `pip install` or `npm install` directly from the dashboard |
| 📜 **Live Logs** | Real-time stdout/stderr streaming with auto-scroll |
| 🔐 **Owner Console** | Create, extend, and delete user accounts from a single dashboard |
| ⏳ **Time-bound + Lifetime Accounts** | Set expiry in days, or `0 days` for a permanent lifetime account |
| 🔗 **Auto-login Links** | Share one-tap login links with users — no password needed |
| 💰 **Pricing Editor** | Edit plans, prices, currency, and contact info from the owner panel |
| 🛒 **Telegram Purchase Flow** | "Buy Now" buttons redirect straight to your Telegram bot |
| 🎨 **Premium Light UI** | El Messiri font, smooth glass surfaces, soft gradients, dark terminal |
| 📱 **Fully Responsive** | Works perfectly on desktop, tablet, and mobile |

---

## 📸 Screenshots

> Landing page, pricing grid, owner console, and user dashboard — all with the same smooth premium look.

**Landing** · **Pricing** · **Owner Console** · **User Dashboard**

*(Add your screenshots here after first deploy)*

---

## 🚀 Quick Start

### Prerequisites

- Python **3.8+**
- `pip`
- Node.js *(optional — only needed to run `.js` scripts)*

### Installation

```bash
# 1. Clone the repo
git clone https://github.com/your-username/pn-vps.git
cd pn-vps

# 2. (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate       # Linux / macOS
venv\Scripts\activate          # Windows

# 3. Install dependencies
pip install flask

# 4. Run the app
python app.py
