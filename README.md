# BlackHook 🪝

**Real-time Anti-Phishing Browser Extension**

---

## 🔍 Overview

Phishing attacks are becoming increasingly sophisticated. Modern attackers use techniques such as fullscreen manipulation, lookalike domains, and fake login pages to steal user credentials without being detected.

**BlackHook** is a browser extension designed to detect and prevent these attacks in real time — running silently in the background to protect users without requiring technical knowledge.

---

## 🚀 Features

* 🛑 **Fullscreen Attack Detection**
  Warns users before a website enters fullscreen mode to hide the browser UI.

* 🌐 **Lookalike Domain Detection**
  Identifies typosquatting and suspicious domains using similarity algorithms.

* 🔐 **Unencrypted Form Detection**
  Alerts users when sensitive data is entered on non-HTTPS (HTTP) pages.

* 📋 **Clipboard Protection**
  Detects and warns about suspicious clipboard modifications.

* 🧠 **Malicious Domain Scanning**
  Integrates with VirusTotal API to check URLs against 70+ security engines.

---

## 🛠️ Tech Stack

* JavaScript (Browser Extension APIs)
* HTML / CSS
* VirusTotal API
* DOM Monitoring & Event Listeners

---

## ⚙️ Installation

```bash
git clone https://github.com/chouaib-sec/BlackHook.git
cd blackhook
```

1. Open your browser (Chrome recommended)
2. Go to: `chrome://extensions/`
3. Enable **Developer Mode**
4. Click **Load unpacked**
5. Select the project folder

---

## ⚙️ How It Works

BlackHook continuously monitors:

* DOM changes
* Fullscreen API calls
* Clipboard events
* URL patterns

It applies detection logic and triggers alerts when suspicious behavior is identified.

---

## 🎯 Project Goal

Make web security accessible to everyone — even non-technical users.
**Security shouldn’t be a luxury.**

---

## 📸 Demo

### 🚨 Phishing Detection Example

BlackHook detects a suspicious lookalike domain and immediately warns the user before any credentials are entered.

* Identifies domain similarity (typosquatting)
* Flags potential phishing behavior
* Prevents user interaction with the malicious page

<img width="1920" height="980" alt="image" src="https://github.com/user-attachments/assets/96514611-e621-4763-894c-3fd984cf58e5" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/98f6b27e-880f-4803-8c12-96e3a8b0ebb3" />

---

### ✅ Legitimate Website Example

BlackHook correctly allows access to a trusted website without triggering any alerts.

* No false positives on legitimate domains
* Seamless browsing experience
* Runs silently in the background

<img width="1896" height="982" alt="image" src="https://github.com/user-attachments/assets/07bbf69d-9c17-4318-ba83-892a412116b7" />


---


