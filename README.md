## 🛡️ VULCAN-X: VAULT-KEEPER (GHOST-PROTOCOL)

### **Advanced Industrial-Grade Cryptographic Data Shield**

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python)
![Encryption](https://img.shields.io/badge/Encryption-AES--256--CBC-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Stable%20Release-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**VULCAN-X VAULT-KEEPER** is a high-security cryptographic framework engineered for absolute data privacy. Developed by **Karndeep Baror**, this suite implements military-grade AES-256 encryption with a unique **Hardware-Binding** logic, ensuring that sensitive data remains inaccessible even if stolen, unless accessed from the original authorised machine.


## 🚀 Key Technical Features

- **Standard-Grade AES-256**: Implements Fernet (AES-128/256) symmetric encryption for high-speed, uncrackable data sealing.
- **Hardware-Machine Binding (SYS-ID)**: Generates a unique SHA-256 hardware fingerprint. Data encrypted on one machine **cannot** be decrypted on another, providing a physical layer of security.
- **Anti-Forensic Data Shredding**: Before deleting original files, the tool overwrites the disk sectors with random binary noise to prevent recovery via forensic tools.
- **HMAC Integrity Shield**: Every encrypted "blob" is signed with an HMAC-SHA256 signature to detect and block bit-level tampering.
- **Brute-Force Lockdown**: Intelligent delay mechanism that triggers a 60-second system lockout after 3 failed attempts.


## 🏗️ Technical Architecture


The encryption flow follows a strict security pipeline:
1. **Key Derivation**: Password + Hardware ID + Salt → PBKDF2 (300,000 Iterations).
2. **Encryption**: Raw Data → AES-256 Ciphertext.
3. **Authentication**: Ciphertext → HMAC Signature.
4. **Final Packaging**: Signature + Ciphertext → `.vcore` file.


## 🛠️ Installation & Setup

### **Prerequisites**
- Python 3.9 or higher
- Pip (Python Package Index)

### **Step 1: Clone the Repository**

```
git clone [https://github.com/karndeepbaror/VulnCanX.git
cd VulnCanX
pip3 install -rf requirements.txt
python vulncanx.py
```

## 🖥️ User Interface Preview

```
    VULCAN-X: VAULT-KEEPER | CORE ARCHITECT: Karndeep Baror
    ------------------------------------------------------
    [1] SEAL DATA (Deep Cryptography)
    [2] UNSEAL VAULT (Hardware-Match)
    [3] SECURITY STATUS
    [0] KILL SESSION
 ```
 
## 🛡️ Security Best Practices

`Master Key`: Do not lose your master key; there is no "Password Reset" in zero-trust architecture.

`Machine Dependency`: If you plan to move data to another PC, decrypt it first.
Audit Logs: Regularly monitor .vault_audit.bin for unauthorized access attempts.

---

## ⚡ ARCHITECT & LEAD DEVELOPER

<div align="center">

| 👤 **Developer** | **Karndeep Baror** |
| :--- | :--- |
| 🛡️ **Role** | Cyber Security Researcher & Ethical Hacker |
| 💻 **Stack** | Python | Cryptography | Network Intelligence |
| 🚀 **Project** | VULCAN-X Intelligence Suite |
| 🌐 **Status** | Active Security Researcher |


## 🔗 CONNECT WITH ME

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/karndeepbaror)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karndeepbaror)
[![Community](https://img.shields.io/badge/Community-FF5722?style=for-the-badge&logo=react&logoColor=white)](https://whatsapp.com/channel/0029Vb6plDSBKfi3qGz2fq0f)

**"In the world of zero-days, I build zero-trust."**

</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/render?type=soft&color=red&height=100&section=footer&text=DESIGNED%20BY%20BAROR&fontSize=25" />
</p>

## 🤝 Contribution & Licensing

This project is part of the `VULCAN-X` Intelligence Suite. For custom integrations or security audits, contact the developer.
    
    
