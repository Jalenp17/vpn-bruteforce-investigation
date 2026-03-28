# vpn-bruteforce-investigation
SOC investigation of brute force attack on VPN using SIEM log analysis and playbook methodology.
# 🚨 VPN Brute Force Attack Investigation | SOC Analysis

## 📌 Overview

This project documents a brute force attack detected on a VPN service. The investigation followed a SOC playbook to determine the legitimacy, impact, and necessary response actions.

---

## 🎯 Objectives

* Identify source of attack (internal vs external)
* Analyze login activity and authentication attempts
* Determine if compromise occurred
* Assess impact and recommend response actions

---

## 🛠️ Tools Used

* Lets Defend (SIEM)
* Log Management System
* Threat Intelligence (IP reputation lookup)
* SOC Playbook Methodology
* VirusTotal
* AbuselPDB
---

## 🔍 Investigation Summary

### Step 1: Source IP Analysis

* Determined attacker IP was **external**

---

### Step 2: IP Reputation Check

* No known malicious reputation at time of analysis

---

### Step 3: Internal Activity Check

* No evidence of red team or authorized testing

---

### Step 4: Traffic & Log Analysis

* Multiple login attempts observed on VPN service
* Repeated failed login attempts detected
* Attacker attempted multiple usernames

---

### Step 5: Successful Compromise

🚨 One login attempt was **successful**

---

### Step 6: Impact Assessment

* Unauthorized access confirmed
* System compromise likely

---

### Step 7: Response Action

* Device requires **isolation**
* Incident escalated

---

## 🧠 Conclusion

* Alert classified as **True Positive**
* Brute force attack resulted in successful compromise

---

## 📊 Skills Demonstrated

* Log Analysis
* Brute Force Detection
* Incident Investigation
* Threat Validation
* SOC Playbook Execution

---

## 📸 Screenshots
<img width="807" height="317" alt="Screenshot 2026-03-25 205307" src="https://github.com/user-attachments/assets/de1dde8e-7d9a-40e6-8f6e-e6e0498f00a1" />
Playbook 1
<img width="807" height="496" alt="Screenshot 2026-03-25 205810" src="https://github.com/user-attachments/assets/bceb2418-c141-4d24-8153-375cfafc3fdb" />
Playbook 2
<img width="794" height="477" alt="Screenshot 2026-03-25 205956" src="https://github.com/user-attachments/assets/22417b34-f4b2-4d69-ab8e-15bab605b626" />
IP check 1
<img width="926" height="201" alt="Screenshot 2026-03-27 191827" src="https://github.com/user-attachments/assets/042a9898-5544-4494-87ac-186632dc4dbd" />
IP check 2
<img width="817" height="355" alt="Screenshot 2026-03-25 210805" src="https://github.com/user-attachments/assets/c805f871-04bb-4074-ab86-0b8c4274589b" />
Playbook 3
<img width="920" height="286" alt="Screenshot 2026-03-25 210922" src="https://github.com/user-attachments/assets/92ae442a-b137-4bc5-96c8-526f20bdbcef" />
Traffic analysis
<img width="774" height="362" alt="Screenshot 2026-03-25 211119" src="https://github.com/user-attachments/assets/26505a40-9e0e-4db3-871f-217aae1bb52b" />
Playbook 4
<img width="609" height="321" alt="Screenshot 2026-03-25 211158" src="https://github.com/user-attachments/assets/270ac911-a6eb-4b91-88a5-4eae0702de94" />
Successful login
<img width="935" height="251" alt="Screenshot 2026-03-25 211556" src="https://github.com/user-attachments/assets/11c6b8cd-8063-49b8-841b-4851ef82561d" />
Analysis answers
