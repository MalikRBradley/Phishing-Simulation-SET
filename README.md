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
  ![Image](https://github.com/user-attachments/assets/dea5fb07-bef0-409b-afba-2662aa2b42bf)
  ![Image](https://github.com/user-attachments/assets/fd589022-a50f-44dc-a7c4-5bef6dca66f5)
- IP configurations for all VMs
  ![Image](https://github.com/user-attachments/assets/8822eadd-130d-49f4-9675-3decfe6d0994)
  ![Image](https://github.com/user-attachments/assets/2e2ff093-b51c-41e9-a93d-341294b73738)
- Victim interacting with the phishing page
  ![Image](https://github.com/user-attachments/assets/457e4523-c63f-4892-97c6-f9223967dbb9)
- Credential Harvest and exported report
  ![Image](https://github.com/user-attachments/assets/9ea33b56-8134-4fbc-a9a0-61b5d5eff24b)


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
<details>
<summary>📄 View Captured Credentials (XML Output)</summary>

```xml
<harvester>
  URL=http://testphp.vulnweb.com/login.php
  <url>
    <param>uname=testuser</param>
    <param>pass=password123</param>
  </url>
</harvester>
```

</details>
---

## ✅ Next Steps
This project is part of a broader series of adversary emulation and Blue Team defense simulations. Future work includes log correlation, alert generation, and hardened phishing defenses.

---

## 🙋‍♂️ Author
**Malik R. Bradley**  
Cybersecurity Enthusiast | Blue Team Projects  
[LinkedIn](https://www.linkedin.com/in/malik-bradley-a1273b28a)
