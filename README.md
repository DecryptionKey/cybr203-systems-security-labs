# CYBR203: Systems & Security Labs

Hands-on labs from **CYBR203 Intro to Systems & Security** at the University at Albany (Spring 2026). The course covers hardware, operating systems, virtualization, cloud, and endpoint protection from a security perspective. Each lab folder has my write-up, the commands I ran, screenshots, findings, and what I took away from it.

Labs were done as team exercises; these write-ups and screenshots are my own documentation of the work.

## Labs

| # | Lab | Focus | Platform |
|---|-----|-------|----------|
| 01 | [Environment Setup & Baseline Assessment](labs/01-environment-setup-baseline/) | VM build, attack surface inventory | Ubuntu (UTM) |
| 02 | [Hardware & Platform Security](labs/02-hardware-platform-security/) | UEFI, Secure Boot, TPM | Ubuntu (UTM) |
| 03 | [OS Architecture & Process Isolation](labs/03-os-architecture-process-isolation/) | Processes, privilege separation | Ubuntu |
| 04 | [Account Management & Authentication](labs/04-account-management-authentication/) | Least privilege, PAM password policy | Ubuntu |
| 05 | [File Systems, Storage & Backup](labs/05-file-systems-storage-backup/) | Permissions, LUKS, backup/restore | Ubuntu |
| 06 | [Patch Management & Hardening](labs/06-patch-management-hardening/) | Patching, CIS Benchmark controls | Ubuntu |
| 07 | [Virtualization & Container Security](labs/07-virtualization-container-security/) | Full-disk encryption, non-root Docker | Ubuntu, Docker |
| 08 | [Cloud IAM & Access Control](labs/08-cloud-iam-access-control/) | MFA, IAM roles, least privilege | AWS |
| 09 | [Cloud Storage Security & Logging](labs/09-cloud-storage-logging/) | S3 Block Public Access, access logs | AWS |
| 10 | [Endpoint Protection & Log Analysis](labs/10-endpoint-protection-log-analysis/) | Firewalls, ClamAV, auth logs | AWS EC2 |
| 11 | [Incident Response Simulation](labs/11-incident-response-simulation/) | NIST SP 800-61, CloudTrail, containment | AWS |

## Tools used
Ubuntu 24.04 LTS, UTM, Bash, Docker, LUKS, PAM, UFW, ClamAV, auditd, AWS (IAM, EC2, S3, CloudTrail, CloudWatch Logs Insights), AWS CLI, CIS Benchmarks, NIST SP 800-61, MITRE ATT&CK

## Notes
- AWS account IDs, ARNs, and public IPs are redacted in the screenshots.
- All "sensitive" data in the cloud labs is dummy data.
- Course handouts and the CIS Benchmark PDF aren't included; only my own work is.

## License
Write-ups and screenshots are licensed under [CC BY 4.0](LICENSE).
