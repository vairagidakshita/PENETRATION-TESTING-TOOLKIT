🛡️ PENETRATION-TESTING-TOOLKIT

Company: CODTECH IT SOLUTIONS

Name: Dakshita Vairagi

INTER ID: CT08DL1157

Domain: Cyber Security and Ethical hacking

Duration: 8 Weeks

Mentor: NEELA SANTOSH KUMAR

Description PENETRATION-TESTING-TOOLKIT

📌 Project Description — Penetration Testing Toolkit (PTT)
Penetration Testing Toolkit (PTT) is an open-source, modular Python-based security assessment suite created to simulate common penetration testing tasks for educational and ethical purposes. Designed to be simple yet powerful, this toolkit enables users to conduct reconnaissance, identify system weaknesses, and exploit common vulnerabilities — all within a controlled and legal environment.

Built with extensibility and clarity in mind, each module within this toolkit performs a specific task in the offensive security workflow — including port scanning, brute-force password attacks, and web vulnerability detection. The code is structured for easy understanding, modification, and integration into custom pipelines.

🎯 Purpose
This project is designed for:

🧑‍💻 Cybersecurity learners who want to understand how real-world penetration tools work under the hood.

🧪 Ethical hackers who want a customizable, scriptable toolkit for authorized testing.

🎓 Students or instructors creating hands-on lab projects.

🔧 Developers experimenting with building network and web scanning tools in Python.

All testing should be performed only on systems you own or have explicit permission to assess.

🔍 What’s Inside the Toolkit?

The toolkit is divided into independent modules — each implemented as a standalone .py file inside the /toolkit/ directory.

1. 🔎 port_scanner.py
   
Performs a TCP port scan over a defined port range.

Uses socket to attempt connections and report open ports.

Fast and lightweight, ideal for initial recon.

Input: Target IP, Start port, End port

Output: List of open ports

2. 🛂 brute_forcer.py
   
Simulates brute-force login attempts on web forms.

Supports HTTP POST-based login forms.

Reads from a custom wordlist of passwords.

Input: Target login URL, username, password file

Output: Password match (if found)

3. 💥 vulnerability_scanner.py
   
Tests GET/POST parameters for:

SQL Injection

Cross-Site Scripting (XSS)

Injects common payloads and analyzes server responses.

Input: Target URL and vulnerable parameter

Output: Detected vulnerability type and payload used

4. 🛠️ utils.py
   
Collection of utility functions:

IP Geolocation

DNS Lookup

Banner Grabbing

Useful for preliminary recon.

🧰 Key Features
✅ Python-based: No external tools required. Runs on most systems with Python 3.x.

✅ Modular: Each tool runs independently and can be reused.

✅ Beginner-friendly: Clear, commented code for easy learning.

✅ Realistic Payloads: Uses actual payloads for XSS, SQLi, and common password cracking.

✅ Educational Purpose: Ideal for labs, assignments, or practical learning.



