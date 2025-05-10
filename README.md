# Phishing Simulation Using the Social-Engineer Toolkit (SET)

This project simulates a credential-harvesting phishing attack in a **controlled lab environment** using the Social-Engineer Toolkit (SET) on Kali Linux. It demonstrates how attackers clone legitimate-looking websites to capture credentials, providing insight into social engineering tactics for Blue Team awareness and defense.

---

## 🛠️ Tools & Technologies
- Kali Linux (SET v8.0.3)
- Windows 11 VM (victim)
- Ubuntu SOC VM (monitoring/logging)
- VirtualBox/VMware
- Internal test network (no real-world exposure)

---

## ⚙️ What Was Simulated
- Cloned login page of a deliberately vulnerable training site (`testphp.vulnweb.com/login.php`)
- Hosted the phishing page via SET on Kali Linux
- Used the Windows VM to access the phishing page and enter fake credentials
- Captured POST requests containing usernames and passwords
- Exported attack logs and generated an XML report for analysis

---

## 🔒 Legal & Ethical Notice
> ⚠️ This simulation was performed **in a local, isolated lab** using **legally safe test environments**. No real users or external systems were targeted.

---

## 📷 Screenshots
- Kali running SET

- IP configurations for all VMs
- Victim interacting with the phishing page
  ![Image](https://github.com/user-attachments/assets/457e4523-c63f-4892-97c6-f9223967dbb9)

## 🧠 Skills Demonstrated
- Ethical hacking methodology
- Phishing tactics & credential harvesting
- Host-based attack simulation
- Safe blue team adversary emulation
- Documenting and reporting cybersecurity simulations

---

## 📁 Project Folder Structure
---

## 🧾 Report Reference
XML report was generated at:  
`/root/.set/reports/2025-05-10-08:25:54.592784.xml`

---

## ✅ Next Steps
This project is part of a broader series of adversary emulation and Blue Team defense simulations. Future work includes log correlation, alert generation, and hardened phishing defenses.

---

## 🙋‍♂️ Author
**Malik R. Bradley**  
Cybersecurity Enthusiast | Blue Team Projects  
[LinkedIn](https://www.linkedin.com/in/malik-bradley-a1273b28a)
