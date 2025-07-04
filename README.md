# 🛠 Botnix Cloud Combo Scraper

A powerful multi-site combo scraper written in Python. Automatically extracts and saves combo lists from popular cracking and leak forums.

---

### 🔥 Features

- Scrapes combos from sites like:
  - heypass.net
  - nohide.space
  - crackingx.com
  - nulled.to
  - hellofhackers.com
  - leaks.ro
  - and more...
- Auto-formats and filters combos
- Saves output in `combos/botnix-cloud-N.txt`
- Multi-threaded scraping
- Supports file hosts: Mega.nz, MediaFire, Gofile, Sendspace, etc.
- Works in Termux, Windows CMD, and Linux terminals

---

### 🐍 Python Installation

> 📦 Requires: Python 3.11 or higher

[![Download Python 3.11](https://img.shields.io/badge/Python-Download%203.11-blue?logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3110/)

---

### ⚙️ Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/botbix-cloud-scraper.git
   cd botbix-cloud-scraper
   pip install requests beautifulsoup4 colorama pathvalidate
