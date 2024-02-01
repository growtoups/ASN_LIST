# 🚫 Datacenter ASN Blocking
This repository maintains a collection of Autonomous System Numbers (ASN) specifically for blocking datacenter ASNs, which can be instrumental in mitigating unwanted or non-human traffic to your service. Regularly updated, this list is compatible with Cloudflare's Web Application Firewall (WAF), allowing for efficient blocking of traffic from these datacenter sources.

# 🚀 How to Implement
To employ this list with Cloudflare's WAF, execute the following steps:

1. Clone or download this repository to your local machine.
2. Edit the `asn-(1-4).txt` files to append the ASNs you aim to block.
3. Sign in to your Cloudflare account and proceed to the firewall settings.
4. Click on "Firewall Rules", then "Create Firewall Rule".
5. Choose "ASN" as the trigger for your rule.
6. Copy and paste the contents from `ASN(1-4).txt` into the relevant fields.
7. Save and activate your firewall rules.

# 🤝 Contributing
Contributions are welcome! If you have datacenter ASNs to add, please submit a pull request. Your input is invaluable in refining this resource.

# ❗ Disclaimer
This list is provided 'as is' and is not a comprehensive solution for blocking all datacenter ASNs. It should be used as a foundational tool in conjunction with other security measures. Use at your own discretion.

# 🧑 Contributors
Special thanks to [NorthernSide](https://github.com/Northernside) and all contributors focused on enhancing datacenter ASN blocking.
