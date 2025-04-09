# DHT-PHISHER 🔥

Welcome to DHT-PHISHER, a powerful phishing tool designed for educational and ethical hacking purposes. This tool allows you to simulate phishing attacks on various social media platforms to understand how attackers use fake login pages to harvest credentials. Use this tool responsibly and only in ethical scenarios, such as penetration testing with explicit consent.

# Table of Contents 📑

Features

Installation

Usage

Supported Platforms

Disclaimer

Credits


# Features ⏩

Multi-platform support: Phishing pages for major platforms like Gmail, Facebook, Instagram, Twitter, Netflix, and more.

Realistic design: Each phishing page has a clean, modern design to closely resemble the official login forms.

Real-time credential logging: Captures username, password, and additional data (e.g., extra fields like Diamond Amount) in real-time.

Easy setup: The tool is easy to set up with minimal configuration. It runs on Flask and supports Cloudflare tunneling.

Educational: Great for learning about web security and phishing techniques.


# Installation ⛏️

Prerequisites:

Make sure you have the following installed on your machine:

Python 3.x (recommended version: 3.6 or higher)

pip (Python's package manager)


Install Required Dependencies

```
apt update && apt upgrade

apt install git python python3

pkg install cloudflared

pip install flask pyfiglet

git clone https://github.com/DHThackers-10/DHT-PHISHER

cd DHT-PHISHER
```

# Usage 🧾

1. Run the tool: Once the dependencies are installed, you can start the tool by running the Python script:
```
python DHT-PHISHER.py
```

2. Choose a platform: The tool will display a list of supported platforms. Choose one by entering the corresponding number.


3. Enter a port: You will be prompted to enter a port number. The default is port 5000, but you can choose a custom port.


4. Start the phishing page: Once the server starts, open a new terminal window and run the following Cloudflare tunneling command (replace <port> with your chosen port number):
```
cloudflared tunnel --url http://localhost:<port>

```
5. Wait for credentials: The tool will display any captured credentials (username, password, and additional information). Press CTRL+C to stop the tool.



# Supported Platforms 🖥️

Here are the platforms you can target with DHT-PHISHER:

Gmail

Free Fire - Diamonds

BGMI - Free UC

Netflix

Twitter

Facebook

Instagram

Discord

Snapchat

Pinterest


Each platform has a unique login page with appropriate logos and placeholders.

# Disclaimer ⚠️🚨

This tool is intended for educational purposes only. Do not use this tool for malicious purposes. Unauthorized phishing activities are illegal and unethical. Always ensure that you have explicit permission before testing any system.

By using this tool, you acknowledge that you are solely responsible for any actions taken with it. The creators of DHT-PHISHER are not responsible for any damage or misuse of this tool.

# Credits 💳

DHT-HACKERS Team: The development and maintenance of DHT-PHISHER.

YouTube Channel: For more tutorials, ethical hacking guides, and updates, visit our YouTube channel:
DHT-HACKERS YouTube Channel (https://www.youtube.com/@DHT-HACKERS_10)

Community: Join our community for discussions, tips, and resources on ethical hacking:
DHT-HACKERS Community (https://chat.whatsapp.com/G2hCkCzylra2OENEfhH8Os)

# Greetings 🤗 🤗 
Thank you to the open-source community and everyone who supports our work!
