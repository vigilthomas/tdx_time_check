# TdxTimeCheck ⏱️

![PyPI](https://img.shields.io/pypi/v/tdxtimecheck?color=blue) ![Python](https://img.shields.io/badge/python-3.6%2B-blue) ![License](https://img.shields.io/badge/license-MIT-green)

**TdxTimeCheck** is a simple and lightweight Python CLI tool to **track your worked hours and calculate remaining time** until your target.  
It’s fast, flexible, and perfect for anyone who wants a quick way to manage their work hours from the terminal.  

---

## Why TdxTimeCheck? 🤔

- ✅ **Easy to Use** – Just run it in your terminal, no setup hassle.  
- ⏱️ **Flexible Input** – Supports `HH`, `HH:MM`, and `HH:MM:SS` formats.  
- 📢 **Instant Feedback** – See worked time, remaining time, and estimated finish time.  
- 🔗 **Portable** – Installable via `pip`, works anywhere.  
- 🛠️ **Open Source** – Free to use, extend, and contribute.  

---

## Features ⭐

- Enter your worked hours and set a target in hours.  
- Automatically calculates how much more time you need to work.  
- Displays the current time and estimated finish time.  

---

## Installation 💻

First, make sure `pip` is installed:

```bash
sudo apt install python3-pip
```

##Example Run 🖥️
```text
$tdxtimecheck
 
Enter worked time so far (HH, HH:MM, HH:MM:SS): 05:10  
Enter target hours :8

Target hours is 8.0 hours

Worked Hours: 5:10:00
You need to work for: 2:50:00

Current Time: 16-09-2025, 12:09 PM
Finish Time: 16-09-2025, 03:00 PM
```
