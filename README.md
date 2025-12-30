🚀 Bash Login Banner

A simple and customizable Bash-based Linux login banner that displays useful system information automatically when a terminal session starts.
This project is created to practice Linux shell scripting, automation, and API integration using curl.

📌 Project Overview

This Bash script enhances the Linux terminal experience by showing system and network-related information in a clean and readable format every time a terminal session begins.

It focuses on learning-by-doing, helping beginners understand how Bash scripts interact with system commands, environment variables, and public APIs.

✨ Features

Personalized welcome message

Logged-in user name and current working directory

Current date and time

Private IP address (local network)

Public IP address (internet-facing)

Automatic city detection

Live weather information with ASCII-style output

Lightweight, fast, and easy to customize

📸 Sample Output
You're looking good today sriman!!
You are currently logged in as sriman and you are in the directory /home/sriman

Today is: Mon Dec 30 18:45:12 IST 2025

Private IP Address: 192.168.1.5
Public IP Address: xxx.xxx.xxx.xxx

City: Kolkata

Weather:
Kolkata: ☀️ +31°C


(Output may vary based on location, network, and time)

🎯 Learning Objectives

This project helps in understanding:

Bash scripting fundamentals

Linux startup configuration (.bashrc)

Command-line automation

Fetching external data using curl

Safe handling of system information

🔐 Security Disclaimer

This project is strictly for educational and learning purposes.

It does not perform hacking, exploitation, or unauthorized tracking.

Public IP and weather data are retrieved using publicly available APIs.

Avoid running this script on production or shared systems without permission.

When sharing screenshots, it is recommended to mask public IP addresses.

📂 File Structure
bash-login-banner/
│
├── bash-login-banner.sh
└── README.md

👤 Author

Sriman Kundu
Cybersecurity & Linux Enthusiast
GitHub: https://github.com/sriman-git09

⚙️ Installation & Usage (How to Run on Linux)
1️⃣ Clone the Repository
git clone https://github.com/sriman-git09/bash-login-banner.git
cd bash-login-banner

2️⃣ Install Required Tools
sudo apt update
sudo apt install curl -y


(Optional – for enhanced visuals)

sudo apt install figlet -y

3️⃣ Make the Script Executable
chmod +x bash-login-banner.sh

4️⃣ Run the Script Manually
./bash-login-banner.sh

5️⃣ Run Automatically on Terminal Startup (Optional)
nano ~/.bashrc


Add this line at the end:

~/bash-login-banner/bash-login-banner.sh


Save and apply changes:

source ~/.bashrc
