🕵️‍♂️ TASK 5 — Capture & Analyze Network Traffic Using Wireshark 🖥️🌐

🚀 OVERVIEW

This task involves capturing and analyzing network traffic using Wireshark on Parrot Security OS 🦜💻.
We explored multiple protocols, filtered traffic, and saved the results in a .pcap file for further analysis.

🛠️ STEPS FOLLOWED

1️⃣ INSTALL WIRESHARK 🐬

sudo apt install wireshark

2️⃣ START CAPTURING ON ACTIVE NETWORK INTERFACE 📡

Open Wireshark

Select your active interface (e.g., eth0 or wlan0)
Hit Start Capture ▶️

3️⃣ GENERATE TRAFFIC 🌍📶

Browsed a few websites 🖥️🌐
Used ping to connect to external servers 📡

4️⃣ STOP CAPTURE ⏹️

After ~1 minute, stopped the capture.

5️⃣ APPLY FILTERS BY PROTOCOL 🔍

HTTP: http 🌐

DNS: dns 📛

TCP: tcp 📦

6️⃣ IDENTIFY 3 DIFFERENT PROTOCOLS 📜

✔ HTTP — Website browsing data

✔ DNS — Domain name lookups

✔ TCP — Transmission Control Protocol packets

7️⃣ EXPORT CAPTURE AS .pcap 📂

Saved file as: task5_capture.pcap

8️⃣ SUMMARIZE FINDINGS 📊

HTTP packets revealed GET and POST requests.

DNS packets showed domain resolution queries and responses.

TCP packets displayed connection establishment (SYN), acknowledgments (ACK), and data transfer.

📷 SCREENSHOTS

(Optional — you can add screenshots of Wireshark filters, packet details, etc.)

📦 FILES IN THIS REPO

task5_capture.pcap — The captured network traffic file.

💡 TOOLS USED

🦜 Parrot Security OS

🐬 Wireshark

📌 CONCLUSION

This exercise helped in understanding how network protocols work in real-time and how packet analysis can be used for troubleshooting, monitoring, and cybersecurity investigations 🔐🛡️.





