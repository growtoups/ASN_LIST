# 🚫 Blocking Hosts by ASN and IP Ranges
This repository contains a list of Autonomous System Numbers (ASN) and IP address ranges that can be used to block malicious hosts to prevent DDoS attacks on your service. The list is updated regularly and can be used with Cloudflare's Web Application Firewall (WAF) to block traffic from these sources.

# 🚀 Getting Started
To use this list with Cloudflare's WAF, follow these steps:

Clone or download this repository to your local machine.
Edit the ```asn-(1-4).txt```files to include the ASNs that you want to block.
Log in to your Cloudflare account and navigate to your firewall settings.
Click on "Firewall Rules" and then "Create Firewall Rule".
Choose the appropriate trigger(s) for your rule (e.g., "ASN").
Paste the contents of ```ASN(1-4).txt```into the appropriate field(s).
Save and deploy your firewall rules.
# 🤝 Contributing
If you have ASNs that you would like to contribute to this repository, please open a pull request. All contributions are welcome and greatly appreciated.

# ❗ Disclaimer
This list is provided as-is and is not guaranteed to block all malicious hosts. It is intended as a starting point for building your own blocklist and should be used in conjunction with other security measures to protect your service. Use at your own risk.

# 🧑 Contributors
[NorthernSide](https://github.com/Northernside)
