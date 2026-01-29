# ESP8266 Evil Twin Captive Portal (Educational)

⚠️ **For educational and authorized security research only**

This project demonstrates how an **Evil Twin Wi-Fi access point** combined with a **captive portal** works, using an **ESP8266**.  
It is intended to help students and security researchers understand **real-world Wi-Fi attack vectors** in order to **defend against them**.

> ❌ Do NOT use this on networks you do not own or have written permission to test.

---

## 🚀 Features

- Wi-Fi network scanning (SSID, BSSID, channel)
- Evil Twin access point cloning the target SSID
- Captive portal with DNS redirection
- Password verification attempt against the real AP
- Web-based admin panel
- Multilingual phishing page (Arabic UI)
- Serial debug logging
- Automatic network rescanning

---

## 🧠 How It Works (High-Level)

1. ESP8266 scans nearby Wi-Fi networks  
2. Operator selects a target network from the admin panel  
3. Device creates an **open AP with the same SSID** (Evil Twin)  
4. All DNS requests are redirected to the captive portal  
5. Victim is shown a fake router update page  
6. Entered password is tested against the real network  

> This mimics a **real attack technique** to help defenders recognize and mitigate it.

---

## 🛠️ Technologies Used

- ESP8266 Arduino Core
- C++ (Arduino)
- DNS Spoofing (DNSServer)
- HTTP Web Server
- Captive Portal Logic
- Wi-Fi STA + AP mode

---

## 🧩 Skill Badges

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-black?style=for-the-badge&logo=espressif)
![Networking](https://img.shields.io/badge/Networking-0078D4?style=for-the-badge&logo=cloudflare&logoColor=white)
![Cyber Security](https://img.shields.io/badge/Cyber%20Security-darkred?style=for-the-badge&logo=hackthebox&logoColor=white)
![Red Team](https://img.shields.io/badge/Red%20Team-black?style=for-the-badge&logo=kalilinux&logoColor=white)

---

## 📚 Educational Use Cases

- Wi-Fi security awareness training
- Captive portal behavior analysis
- Evil Twin detection research
- Red Team / Blue Team labs
- Embedded networking experiments

---

## 🔒 Legal Disclaimer

This project is provided **for educational purposes only**.

The author is **not responsible** for any misuse, damage, or illegal activity caused by this software.  
Use only on **networks you own** or have **explicit written authorization** to test.

---

## 📜 License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.
