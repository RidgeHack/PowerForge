# MDE & MDI Testing Tools

A collection of testing tools for Microsoft Defender for Endpoint (MDE) and Microsoft Defender for Identity (MDI).

## Overview

This repository contains tools and scripts designed to test and validate the detection capabilities of Microsoft Defender for Endpoint and Microsoft Defender for Identity in controlled environments.

## Tools Included

### MDE Testing Tools
- **Endpoint behavior simulation**
- **Process injection techniques**
- **Malware simulation utilities**
- **Living-off-the-land binary (LOLBin) testing**
- **Detection validation scripts**

### MDI Testing Tools
- **Active Directory attack simulation**
- **Kerberos attack testing**
- **LDAP query testing**
- **Pass-the-hash simulation**
- **Lateral movement detection tests**

## Installation

### Prerequisites
- Windows environment for MDE testing
- Active Directory environment for MDI testing
- PowerShell 5.1 or higher
- Administrator privileges

### Setup

```powershell
# Clone the repository
git clone https://github.com/RidgeHack/PowerForge.git
```


## Directory Structure

```
PowerForge/
├── mde-tests/          # MDE testing scripts
├── mdi-tests/          # MDI testing scripts
```

## Legal & Ethical Use

⚠️ **IMPORTANT DISCLAIMER**

These tools are for **authorized testing of Microsoft Defender solutions only**.

- Use only in controlled test environments
- Obtain proper authorization before testing
- Do not use in production environments without approval
- Follow your organization's security testing policies

## Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch
3. Test thoroughly in isolated environment
4. Submit a pull request

## Resources

- [Microsoft Defender for Endpoint Documentation](https://docs.microsoft.com/en-us/microsoft-365/security/defender-endpoint/)
- [Microsoft Defender for Identity Documentation](https://docs.microsoft.com/en-us/defender-for-identity/)
- [MITRE ATT&CK Framework](https://attack.mitre.org/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Use responsibly in authorized test environments only.**
