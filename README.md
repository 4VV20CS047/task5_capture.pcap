🕵️‍♂️ Task 5 — Capture & Analyze Network Traffic Using Wireshark 🖥️🌐
🚀 Overview
This task involves capturing and analyzing network traffic using Wireshark on Parrot Security OS 🦜💻.
We explored multiple protocols, filtered traffic, and saved the results in a .pcap file for further analysis.

🛠️ Steps Followed

1️⃣ Install Wireshark 🐬
sudo apt install wireshark

2️⃣ Start Capturing on Active Network Interface 📡
Open Wireshark
Select your active interface (e.g., eth0 or wlan0)
Hit Start Capture ▶️

3️⃣ Generate Traffic 🌍📶
Browsed a few websites 🖥️🌐
Used ping to connect to external servers 📡

4️⃣ Stop Capture ⏹️
After ~1 minute, stopped the capture.

5️⃣ Apply Filters by Protocol 🔍
HTTP: http 🌐
DNS: dns 📛
TCP: tcp 📦

6️⃣ Identify 3 Different Protocols 📜
✔ HTTP — Website browsing data
✔ DNS — Domain name lookups
✔ TCP — Transmission Control Protocol packets

7️⃣ Export Capture as .pcap 📂
Saved file as: task5_capture.pcap

8️⃣ Summarize Findings 📊
HTTP packets revealed GET and POST requests.
DNS packets showed domain resolution queries and responses.
TCP packets displayed connection establishment (SYN), acknowledgments (ACK), and data transfer.

📷 Screenshots
(Optional — you can add screenshots of Wireshark filters, packet details, etc.)

📦 Files in This Repo
task5_capture.pcap — The captured network traffic file.

💡 Tools Used
🦜 Parrot Security OS
🐬 Wireshark

📌 Conclusion
This exercise helped in understanding how network protocols work in real-time and how packet analysis can be used for troubleshooting, monitoring, and cybersecurity investigations 🔐🛡️.




