# Automated Network Scanner with HTML Reporting

A Python-based network auditing tool that leverages Nmap to discover active hosts on a subnet, scans for core open enterprise ports, and automatically generates a clean, interactive HTML visual report for network administrators.

## 🚀 Features
- **Host Discovery:** Scans entire subnets smoothly using `python-nmap`.
- **Targeted Port Auditing:** Targets common administration and web ports (22, 80, 443, 445, 3389).
- **Dynamic HTML Reporting:** Uses `Jinja2` templating engine to construct a clean visual dashboard.
- **Automation Friendly:** Ready to be set up as a scheduled cron job for periodic auditing.

## 🛠️ Prerequisites & Installation
Ensure you have Nmap installed on your system path, then install dependencies:

```bash
pip install -r requirements.txt
