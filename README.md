Multiblox Client
The Next-Generation Infrastructure for Roblox Fleet Management.
Multiblox is a high-performance process manager designed to bypass the standard limitations of the Roblox client. Built by Bebeluck Labs, it replaces the standard launcher with a robust fleet management system, enabling massive concurrency, advanced session isolation, and persistent automation.

Unlike basic "multi-instance" scripts, Multiblox acts as a Supervisor, monitoring every active window for crashes, disconnects, or authentication failures and automatically recovering them without user intervention.

<img width="2560" height="1392" alt="Screenshot 2025-12-24 151257" src="https://github.com/user-attachments/assets/5a73acc3-c485-40b8-84ef-2b1b53004da0" />
<img width="2560" height="1392" alt="Screenshot 2025-12-24 151244" src="https://github.com/user-attachments/assets/1aea2c1b-97d7-4d79-92fd-64086a1a46cc" />
<img width="2560" height="1392" alt="Screenshot 2025-12-24 151350" src="https://github.com/user-attachments/assets/3381f3e7-0361-4dfe-8de6-135a9e9e6fd1" />

🚀 Key Features
⚡ Massive Concurrency: Launch and manage 35+ instances simultaneously on a single machine (hardware dependent).

🚌 "Bus Driver" Protocol: Automated join orchestration. Bots intelligently resolve a Leader's User ID and follow them into specific Private Servers or Public hubs automatically.

🛡️ Session Isolation: Proprietary "Cookie Locking" and "Tracker ID" hashing prevent cross-session contamination, allowing distinct accounts to coexist without logging each other out.

❤️ Watchdog & Recovery: A background process monitor scans fleet health every 3 seconds. If an instance crashes or closes, Multiblox automatically relaunches it.

🔔 Remote Monitoring: Integrated Discord Webhooks send real-time status alerts (Crashes, Relaunches, and Deployment Success) directly to your phone.

🎨 Deep Space UI: A professional, low-strain dark theme designed for long-term monitoring.

⚙️ Requirements
OS: Windows 10/11 (64-bit)

Runtime: .NET 8.0 (Included in the single-file executable, no install required).

Hardware (Recommended for 30+ instances):

CPU: Ryzen 7 5800X / 9800X3D or equivalent.

RAM: 32GB+ DDR4/DDR5.

GPU: Dedicated GPU recommended (Drivers must be configured to cap FPS at 30).

📥 Installation
Download the latest Multiblox.exe from the Releases page.

Place the executable in a dedicated folder (e.g., C:\Multiblox).

Run Multiblox.exe.

Note: You may need to whitelist the application in your antivirus due to its nature as an unsigned automation tool (False Positive).

⚠️ Disclaimer
Multiblox Client is an automation tool developed for educational and research purposes.

This software is not affiliated with, endorsed by, or connected to Roblox Corporation.

Use of this software to gain an unfair advantage or disrupt services may violate the Terms of Service of the target platform.

Bebeluck Labs accepts no responsibility for bans, account suspensions, or data loss resulting from the use of this tool. Use responsibly.

Copyright © 2025 Bebeluck Labs.
