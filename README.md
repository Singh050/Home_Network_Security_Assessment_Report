# 🛡️ Home Network Security Assessment Report

**Author:** Barjinder Singh  
**Date:** May 3, 2025  
**Contact:** barjindersingh1104@gmail.com

This repository provides a comprehensive vulnerability assessment of a typical home network. The assessment follows structured methodologies referencing **NIST SP 800-53**, **CVSS v3.1**, and **OWASP** best practices.

---

## 📋 Summary

This assessment identifies common security risks across devices typically found in residential networks:

- 🛠️ **Router** – Gateway and DHCP services
- 📺 **Smart TV** – IoT streaming device
- 🖨️ **Printer** – Wireless peripheral with open services
- 💻 **Laptop** – Primary work device
- 📡 **Guest Wi-Fi** – Misconfigured and unsegmented

Key outcomes of this assessment include:

- 🧾 Device inventory and IP mapping
- 🚨 Risk findings with CVSS scoring
- ✅ Remediation strategies mapped to NIST controls
- 🧰 Tools and frameworks used

---

## 🛠️ Tools Used

| Tool           | Function                                      |
|----------------|-----------------------------------------------|
| Nmap           | Port scanning and service detection           |
| Shodan         | Public exposure and footprint discovery       |
| Wireshark      | DNS and packet-level traffic inspection       |
| Router Interface | Manual audit of device configuration        |
| CVE Lookup     | Firmware vulnerability identification         |
| Dradis Template| Structured reporting format                   |

---

## 📚 Frameworks Referenced

- **NIST SP 800-53** – Security and privacy controls
- **OWASP Top 10 & Risk Rating** – Best practices for risk evaluation
- **CVSS v3.1** – Severity scoring of identified vulnerabilities

---

## 📄 Report Files
<p>  <a href="https://docs.google.com/viewer?url=https://github.com/Singh050/Home_Network_Security_Assessment_Report/raw/main/Home_Network_%20Security_Assessment_Report.pdf" target="_blank">
    <img src="https://img.shields.io/badge/View%20PDF-Open%20Report-blue?style=for-the-badge&logo=google-chrome" alt="View PDF">
  </a></p>

---

## 🔐 Key Takeaways

- Secure your router: change default credentials, disable UPnP, apply firmware updates
- Encrypt Wi-Fi using WPA2/WPA3 only
- Isolate guest devices via VLAN or AP isolation
- Enable DNS over HTTPS (DoH) to prevent DNS snooping
- Monitor your home traffic with tools like Pi-hole

---

**© 2025 Barjinder Singh – All rights reserved.**
