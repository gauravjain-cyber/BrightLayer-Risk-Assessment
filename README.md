# BrightLayer Stores – Cybersecurity Risk Assessment

**Assessment Type:** Basic Cybersecurity Risk Assessment  
**Organization:** BrightLayer Stores (Simulated)  
**Company Size:** 8 Employees  

---

## 1. FIVE IMPORTANT ASSETS

### 1. Employee Email Accounts
Employees use email for business communication and may receive sensitive company information. If an account is compromised, attackers could access confidential messages or use the account for fraudulent activities.

### 2. Cloud Storage with Invoices
The cloud storage contains business invoices and potentially customer or financial information. Protecting this data is important for privacy and normal business operations.

### 3. Company Website
The company website represents BrightLayer Stores online and may provide information or services to customers. A compromise could affect the company's reputation and business operations.

### 4. User Passwords
Passwords protect employee email accounts, cloud storage, website administration, and other systems. Weak or stolen passwords could allow attackers to gain unauthorized access.

### 5. Shared Computers
Employees use shared computers to access company resources. These computers may contain saved passwords, active browser sessions, or business files.

---

## 2. THREE POTENTIAL THREATS

### 1. Phishing Attacker
A cybercriminal could send fake emails containing malicious links or attachments to trick employees into providing their credentials or downloading malware.

### 2. Website Attacker
An external attacker could attempt to exploit weaknesses in the company website to modify the website, steal information, or make it unavailable.

### 3. Unauthorized Wi-Fi Attacker
A person near the business could attempt to connect to or attack the public Wi-Fi network. If the public network is not properly separated from the company network, the attacker may attempt to reach internal devices.

---

## 3. THREE VULNERABILITIES

### 1. Weak or Reused Passwords
Employees may use simple passwords or reuse the same password across multiple company services.

### 2. Insecure Shared Computers
Shared computers may remain logged in, allow users to save passwords, or lack proper individual user accounts and access controls.

### 3. Poorly Segmented Wi-Fi Network
The public Wi-Fi may be connected to the same network as company computers. This could allow unauthorized users to potentially reach internal systems.

---

## 4. ASSOCIATED RISKS

### Risk 1 – Account Compromise
**Threat:** Phishing attacker  
**Vulnerability:** Weak or reused passwords  

An attacker could trick an employee into revealing their password. The attacker could then access email or cloud storage containing business information and invoices.

**Potential Impact:** Data theft, financial fraud, exposure of customer information, and loss of business trust.

### Risk 2 – Website Compromise
**Threat:** Website attacker  
**Vulnerability:** Weak website security  

An attacker could exploit a weakness in the company website to modify content, steal information, or make the website unavailable.

**Potential Impact:** Reputational damage, loss of customer trust, and lost business.

### Risk 3 – Unauthorized Internal Access
**Threat:** Unauthorized Wi-Fi attacker  
**Vulnerability:** Poorly segmented Wi-Fi network  

If public Wi-Fi and company devices share the same network, an unauthorized user could potentially access internal computers or resources.

**Potential Impact:** Malware infection, unauthorized access, and data theft.

### Risk 4 – Credential or Session Theft
**Threat:** Phishing attacker  
**Vulnerability:** Insecure shared computers  

If a malicious link is opened on a shared computer, saved credentials or active browser sessions could potentially be exposed.

**Potential Impact:** Unauthorized access to employee accounts and company information.

---

## 5. SECURITY RECOMMENDATIONS

### 1. Enable Multi-Factor Authentication (MFA)
Enable MFA for employee email accounts and cloud storage.

**Risk addressed:** Account compromise.

### 2. Use Strong and Unique Passwords
Employees should use strong, unique passwords for important accounts. A password manager can be used to securely manage passwords.

**Risk addressed:** Account compromise.

### 3. Separate Public Wi-Fi from the Company Network
Create a separate guest Wi-Fi network or use VLAN/network isolation so public users cannot directly access company computers.

**Risk addressed:** Unauthorized internal access.

### 4. Secure Shared Computers
Give employees individual accounts, enable automatic screen locking, remove unnecessary saved passwords, and keep operating systems and security software updated.

**Risk addressed:** Credential or session theft.

### 5. Provide Phishing Awareness Training
Train employees to identify suspicious emails, links, attachments, and requests for passwords or sensitive information.

**Risk addressed:** Account compromise and credential theft.

### 6. Regularly Update and Secure the Company Website
Keep website software, plugins, and administrator accounts updated and protected with strong authentication.

**Risk addressed:** Website compromise.

### 7. Maintain Regular Backups
Regularly back up important business documents, including invoices, so information can be recovered after accidental deletion, malware, or a cyberattack.

**Risk addressed:** Data loss and business disruption.

---

## Conclusion

The main security risks for BrightLayer Stores are account compromise, website attacks, unauthorized network access, and credential theft. Basic controls such as MFA, strong passwords, network segmentation, secure shared computers, employee training, website updates, and regular backups can significantly reduce these risks.

This assessment follows the standard cybersecurity risk flow:

**Asset → Threat → Vulnerability → Risk → Recommendation**


# Day 02 – Networking Fundamentals

**Student:** Gaurav Jain  
**Topic:** Networking Fundamentals  
**Task:** Basic Networking Theory and Network Troubleshooting

## Overview

This task covers the fundamentals of computer networking and their importance in cybersecurity.

### Topics Covered

- Computer Networks
- Client and Server
- LAN and WAN
- Switches and Routers
- Firewalls
- IP Addresses
- MAC Addresses
- Default Gateway
- DNS
- Networking and Cybersecurity

## Practical Work

The following Windows networking commands were practiced:

```text
ipconfig
ping
tracert
