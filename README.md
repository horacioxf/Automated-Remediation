# Automated Vulnerability Remediation

## Remediations Table

| Tenable PluginID | Severity        | Description                   | Language   | Link                                                     |
|------------------|------------|-------------------------------|------------|----------------------------------------------------------|
| 206467            | Critical | Mozilla Firefox < 130.0 (multiple vulnerabilities) | PowerShell | [View Remediation](https://github.com/horacioxf/Automated-Remediation/blob/main/scripts/remediation-FireFox-uninstall.ps1) |
| 97086            | High | Server Message Block (SMB) Protocol Version 1 Enabled | PowerShell       | [View Remediation](https://github.com/horacioxf/Automated-Remediation/blob/main/scripts/remediation-SMBv1.ps1) |
| 104743            | Medium | TLS Version 1.0 Protocol Detection | PowerShell | [View Remediation](https://github.com/horacioxf/Automated-Remediation/blob/main/scripts/toggle-protocols.ps1) |
| 11255            | Critical | Default Password (root) for 'root' Account | BASH | [View Remediation](https://github.com/horacioxf/Automated-Remediation/blob/main/scripts/remediation-root-password.sh) |
| 160477           | Critical | OpenSSL 1.1.1 < 1.1.1o Vulnerability | BASH | [View Remediation](https://github.com/horacioxf/Automated-Remediation/blob/main/scripts/remediation-openssl-3.0.5-install.sh) |
| 42263            | Medium | Unencrypted Telnet Server Detected | BASH | [View Remediation](https://github.com/horacioxf/Automated-Remediation/blob/main/scripts/remediation-Telnet-removal.sh) |
