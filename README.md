# SSL/TLS Inspection and Network Traffic Analysis Lab

## Project Overview

This project demonstrates the implementation, configuration, and analysis of SSL/TLS inspection within a controlled enterprise network environment using FortiGate Firewall, Wireshark, and virtualized infrastructure.

The objective of this lab was to understand how encrypted HTTPS traffic can be securely intercepted, decrypted, inspected, and re-encrypted by a security appliance while maintaining trust through certificate management.

---

## Objectives

* Configure SSL/TLS inspection on a FortiGate firewall
* Implement SSL decryption using firewall-generated certificates
* Analyze encrypted and decrypted network traffic
* Demonstrate HTTPS interception techniques
* Evaluate network visibility improvements through SSL inspection
* Assess security, privacy, and compliance implications

---

## Lab Environment

| Component       | Technology                   |
| --------------- | ---------------------------- |
| Firewall        | FortiGate Firewall           |
| Client          | Windows 11                   |
| Packet Analysis | Wireshark                    |
| Virtualization  | VMware / Cisco Modeling Labs |
| Network         | TCP/IP, HTTPS, TLS           |

---

## Network Topology

The environment consisted of:

* Windows Client VM
* FortiGate Firewall
* External HTTPS Services
* Wireshark Packet Analyzer

Traffic flowed through the firewall where SSL/TLS interception and inspection were performed.

---

## Project Activities

### Network Configuration

* Configured IP addressing
* Configured DNS and default gateways
* Verified client connectivity

### SSL/TLS Inspection

* Enabled deep SSL inspection policies
* Configured SSL certificate authorities
* Implemented HTTPS interception

### Certificate Management

* Exported firewall root certificate
* Installed certificate into Windows Trusted Root Store
* Verified browser trust relationships

### Traffic Analysis

* Captured encrypted TLS traffic
* Analyzed TLS handshakes
* Decrypted HTTPS payloads
* Inspected application-layer traffic

### Security Assessment

* Evaluated SSL interception mechanisms
* Investigated certificate pinning limitations
* Assessed encrypted SNI challenges
* Reviewed firewall performance impacts

---

## Skills Demonstrated

* SSL/TLS Inspection
* Network Security
* FortiGate Administration
* Packet Analysis
* Wireshark
* Certificate Management
* Public Key Infrastructure (PKI)
* HTTPS Security
* Firewall Policy Configuration
* Security Monitoring
* Threat Detection
* Traffic Analysis
* Network Troubleshooting
* Security Documentation

---

## Security and Compliance Considerations

This project evaluated legal and privacy implications related to SSL inspection, including:

* GDPR
* HIPAA
* PIPEDA
* User Privacy
* Data Protection
* Security Governance

---

## Technologies Used

* FortiGate Firewall
* Wireshark
* Windows 11
* VMware
* Cisco Modeling Labs (CML)
* SSL/TLS
* PKI
* HTTPS
* TCP/IP

---

## Disclaimer

All activities were conducted within a controlled and authorized educational cybersecurity laboratory environment and were performed in accordance with ethical cybersecurity practices.

---

## Author

**Obed Okeukwu**

Cybersecurity Graduate | Security Analyst | Network Security Enthusiast
