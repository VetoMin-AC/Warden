# 🛡️ Warden — Network Guardian

> **Warden is a lightweight but powerful network monitoring tool that gives you real-time visibility into your system's internet connections. It helps you detect suspicious activity and block threats instantly.**

---

## 📸 Screenshots

> 🖼️ *Screenshots will be added soon*

---

## 🚀 Features

| Feature | Description |
|---------|-------------|
| 🔍 **Real-time Monitoring** | Displays all active TCP connections with process details |
| 🌍 **GeoIP Lookup** | Shows the country and city of every remote IP address |
| ⚠️ **Danger Highlighting** | Automatically marks processes running from risky folders (Temp, Downloads, AppData) |
| ❌ **Kill Process** | Terminates any selected process with one click |
| ⛓️ **Firewall Block** | Instantly blocks a process from accessing the internet via Windows Firewall |
| ✅ **Whitelist** | Mark trusted processes to ignore them in future scans |
| 🔍 **Process Details** | Displays path, memory usage, CPU load, creation time, and parent process |
| 🚫 **Lockdown Mode** | Blocks all new outbound connections on the fly |
| 🧨 **Deep Scan** | Scans system folders (Temp, AppData, Downloads, ProgramData) for suspicious files |
| 🌍 **Threat Map** | Shows all active connections grouped by country |
| 📄 **Action Log** | Keeps a detailed log of every action you perform |
| ☠️ **Parasite Killer** (optional) | **Destroys malware from the inside** — overwrites its binary code and breaks its logic |

---

## 📦 Installation & Running

### For end-users (no Python required)
1. Download the latest `WARDEN.exe` from the [Releases](https://github.com/VetoMin-AC/warden/releases) page
2. Run the `.exe` file
3. Done! Warden will start monitoring your connections immediately

### For developers (with Python)
1. Clone the repository:
   ```bash
   git clone https://github.com/VetoMin-AC/warden.git
   cd warden
## 🔒 Safety & Trust

> **Warden interacts with system processes and network connections.**  
> Some antivirus software may temporarily flag it (this is common for network monitoring tools).

### ✅ Verified & Transparent

- The source code is **fully open** and available for review.
- The compiled `.exe` file can be scanned using **[VirusTotal](https://www.virustotal.com)** — a free online service that checks files against 60+ antivirus engines.
- If you're unsure about the file, we **encourage you to scan it yourself** before running it.

### 🧪 How to verify the `.exe` file

1. Download the latest `WARDEN.exe` from the [Releases](https://github.com/VetoMin-AC/warden/releases) page.
2. Go to **[VirusTotal](https://www.virustotal.com)**.
3. Click **"Choose File"** and select the downloaded `WARDEN.exe`.
4. Wait for the scan to complete (usually takes 1–2 minutes).
5. Review the results — if it's clean, you're safe to run it.

### 🔐 Why trust this project?

- The code is publicly available — no hidden or obfuscated logic.
- No encrypted payloads, no remote connections, no data collection.
- It only does what it says: monitors and manages network connections.

If you still have doubts, feel free to open an issue or contact the author directly.

> ⚠️ **False positives are common** for tools like Warden because they access system memory and processes. This is normal behavior and does **not** mean the file is malicious.
