# 🔍 Python Port Scanner
<div align="center">

A simple **TCP port scanner** written in Python using the `socket` library. This tool checks for open ports on a target host within a given port range.
# 🔍 Python Port Scanner  
A lightweight TCP port scanning tool built using Python's `socket` library  

![GitHub Stars](https://img.shields.io/github/stars/codraja06/port_scanner?style=for-the-badge)
![GitHub Forks](https://img.shields.io/github/forks/codraja06/port_scanner?style=for-the-badge&color=teal)
![GitHub License](https://img.shields.io/github/license/codraja06/port_scanner?style=for-the-badge&color=yellow)
![Python Version](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge)

<img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/0f380ca0-b264-4bfc-8c3a-3243a8aad45a" />


</div>

---

## 🚀 Features
- Scan a target by **IP address** or **hostname**
- Specify a **custom port range**
- Lists all **open TCP ports**
- Handles common errors (invalid host, connection issues, invalid port range)
- Lightweight, no external dependencies
## ✨ Features
✔ Scan targets using **IP address** or **Domain name**  
✔ Choose a **custom port range**  
✔ Detects **OPEN** ports  
✔ Error handling for invalid inputs  
✔ Super fast & no external libraries required  
✔ Works on **Windows, Linux & macOS**

---

## 📁 Project Structure
```
port_scanner/
│── port_scanner.py # Main tool
│── README.md # Documentation
│── .gitignore # Ignored files
```

---

## ⚙️ Installation

### Clone the Repository
```bash
git clone https://github.com/codraja06/port_scanner.git
cd port_scanner
```
```
(Optional for Linux/macOS)

chmod +x port_scanner.py

```
### 🖥️ Usage Instructions

###🔹 Run the Script (Windows / Linux / Mac)
```
python3 port_scanner.py
```
or
```
python port_scanner.py
```

### 🔹 Example Output
```bash
  _____           _           _____                                 
 |  __ \         | |         / ____|                                
 | |__) ___  _ __| |_       | (___   ___ __ _ _ __  _ __   ___ _ __ 
 |  ___/ _ \| '__| __|       \___ \ / __/ _` | '_ \| '_ \ / _ \ '__|
 | |  | (_) | |  | |_        ____) | (_| (_| | | | | | | |  __/ |   
 |_|   \___/ |_|   \__|      |_____/ \___\__,_|_| |_|_| |_|\___|_|  
======================================================================

                Created by 'codwolf'

Enter the Target IP (or) Hostname: google.com
Enter the port range (e.g., 1-500): 20-100

[+] Scanning google.com...
[+] Port 80 is OPEN

```
### 🧪 Tested on
---
| OS                  | Status |
| ------------------- | ------ |
| Windows 10/11       | ✅      |
| Ubuntu / Kali Linux | ✅      |
| macOS               | ✅      |

---

## ⚠️ Disclaimer

This project is only for ethical and educational use.  
Do not scan systems you don’t own or have permission to test.

---

## 🤝 Contribution

Contributions are welcome!  
Feel free to create issues, fork the repo & submit pull requests 🚀

---

## 📜 License

This project is licensed under the MIT License.

---

<div align="center">

⭐ If you found this helpful, please **Star the repo!** ⭐  
Made with ❤️ by **codwolf**

</div>
