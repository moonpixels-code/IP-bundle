# 🌍 IP Location Tool

A lightweight Python-based IP geolocation tool that retrieves public IP information such as location estimates, ISP details, and coordinates.

Built for learning Python, networking, APIs, and OSINT concepts.

## ✨ Features

- 🌐 IP address lookup
- 📍 Approximate location information
- 🏢 ISP / organization detection
- 🗺️ Google Maps coordinate link
- 🎨 Colored terminal output
- 🖥️ ASCII banner
- 📄 JSON report export
- 🔎 Supports multiple IP addresses

## 📸 Example


██╗██████╗ ██╗ ██████╗ ██████╗
██║██╔══██╗ ██║ ██╔═══██╗██╔════╝
██║██████╔╝ ██║ ██║ ██║██║
██║██╔═══╝ ██║ ██║ ██║██║
██║██║ ███████╗╚██████╔╝╚██████╗
╚═╝╚═╝ ╚══════╝ ╚═════╝ ╚═════╝

    IP LOCATION TOOL v1.0

Example:


Enter IP address(es) separated by commas:

8.8.8.8,1.1.1.1


Output:


=== IP Information ===

IP: 8.8.8.8
City: Mountain View
Country: US
ISP: Google LLC
Coordinates: xx.x,xx.x

Map:
https://www.google.com/maps?q=xx.x,xx.x

[+] Report saved as report.json


## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/IP-Location-Tool.git

Go into the directory:

cd IP-Location-Tool

Install requirements:

pip3 install colorama
🚀 Usage

Run:

python3 mytool.py

Enter a public IP:

8.8.8.8

or multiple IPs:

8.8.8.8,1.1.1.1

The tool will generate:

report.json

containing the lookup results.

📄 JSON Report Example
[
    {
        "IP": "8.8.8.8",
        "Hostname": "dns.google",
        "City": "Mountain View",
        "Region": "California",
        "Country": "US",
        "ISP": "Google LLC",
        "Coordinates": "37.4056,-122.0775"
    }
]
📁 Project Structure
IP-Location-Tool/
│
├── mytool.py
├── report.json
├── README.md
└── LICENSE
🛠️ Requirements
Python 3.x
colorama
Internet connection
⚠️ Disclaimer

This tool provides approximate IP geolocation information.

IP addresses do not reveal exact home addresses. Results may be inaccurate due to:

VPNs
Proxies
Mobile networks
ISP routing

Use this tool only on IP addresses you own or have permission to analyze.

📜 License

This project is licensed under the MIT License.

See the LICENSE file for details.


# 🌐 DNS Lookup Tool

A simple Python-based DNS lookup tool that retrieves IP address information from domains.

Built for learning Python, networking, and basic OSINT concepts.

## ✨ Features

- 🌐 Domain to IP lookup
- 🎨 Colored terminal output
- 🖥️ ASCII banner
- 📄 JSON report generation
- 🔍 Supports multiple domains
- ⚡ Lightweight and fast

## 📸 Example

██████╗ ███╗ ██╗███████╗
██╔══██╗████╗ ██║██╔════╝
██║ ██║████╗ ██║███████╗
██║ ██║██║╚██╗██║╚════██║
██████╔╝██║ ╚████║███████║

    DNS LOOKUP TOOL v1.0
    
    Example usage:


Enter domains separated by commas:
google.com,github.com


Output:


=== DNS Information ===

Domain: google.com
IP: 142.xxx.xxx.xxx

[+] Saved dns_report.json


## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/DNS-Lookup-Tool.git

Go into the folder:

cd DNS-Lookup-Tool

Install requirements:

pip3 install colorama

🚀 Usage

Run:

python3 dns_tool.py

Enter domains:

example.com,google.com

The tool will create:

dns_report.json

📄 Report Example:

[
    {
        "Domain": "google.com",
        "IP Address": "142.xxx.xxx.xxx",
        "Checked": "2026-06-26"
    }
]
containing the lookup results.

📁 Project Structure
DNS-Lookup-Tool/
│
├── dns_tool.py
├── dns_report.json
├── README.md
└── LICENSE
⚠️ Disclaimer

This tool is created for educational purposes and authorized testing only.

Do not use this tool against domains or systems you do not own or do not have permission to test.

📜 License

This project is licensed under the MIT License.

See the LICENSE file for details.

Made with 🐍 Python and ☕ curiosity.

