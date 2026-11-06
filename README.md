### Hi, I'm Bohdan 👋

**Junior Linux Infrastructure Engineer / Systems Administrator / SOC L1 Analyst**  
Master's Student in Cybersecurity & Software Engineering at Kharkiv National University of Radio Electronics (NURE).

Focused on Linux system administration, network diagnostics, container orchestration, host/network threat detection (SIEM/XDR + NIDS), and production infrastructure observability.

---

### 🛠 Technical Toolkit

#### Infrastructure & Linux Systems
[![Linux](https://img.shields.io/badge/Linux-Ubuntu%20%7C%20Debian-E95420?style=for-the-badge&logo=linux&logoColor=white)](https://ubuntu.com/)
[![Nginx](https://img.shields.io/badge/Nginx-Reverse_Proxy%20%7C%20Sockets-009639?style=for-the-badge&logo=nginx&logoColor=white)](https://nginx.org/)
[![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Bash](https://img.shields.io/badge/Bash-Shell%20Automation-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Systemd](https://img.shields.io/badge/Systemd-Services%20%26%20Timers-000000?style=for-the-badge)](https://systemd.io/)
[![VMware](https://img.shields.io/badge/VMware-Workstation-607078?style=for-the-badge&logo=vmware&logoColor=white)](https://www.vmware.com/)

#### Observability & Monitoring
[![Prometheus](https://img.shields.io/badge/Prometheus-Node_Exporter-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)](https://prometheus.io/)
[![Grafana](https://img.shields.io/badge/Grafana-Dashboards-F46800?style=for-the-badge&logo=grafana&logoColor=white)](https://grafana.com/)

#### Security Monitoring & Defense
[![Wazuh](https://img.shields.io/badge/Wazuh-SIEM%20%2F%20XDR%20%2F%20Active_Response-0052CC?style=for-the-badge&logo=wazuh&logoColor=white)](https://wazuh.com/)
[![Suricata](https://img.shields.io/badge/Suricata-NIDS_7.0%20DPI-C91A24?style=for-the-badge&logo=suricata&logoColor=white)](https://suricata.io/)
[![Netfilter](https://img.shields.io/badge/Firewall-iptables%20%7C%20UFW%20%7C%20Fail2ban-386641?style=for-the-badge)](https://netfilter.org/)
[![Wireshark](https://img.shields.io/badge/Wireshark-PCAP%20%26%20TLS%20Inspection-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)](https://www.wireshark.org/)
[![MITRE](https://img.shields.io/badge/MITRE_ATT%26CK-Enterprise_Matrix-black?style=for-the-badge)](https://attack.mitre.org/)

#### Programming & Databases
[![Python](https://img.shields.io/badge/Python-Automation%20%26%20APIs-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Go](https://img.shields.io/badge/Go-1.22-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://golang.org/)
[![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)

---

### 📌 Featured Engineering Projects

| Project | Domain | Architecture & Key Deliverables |
|---|---|---|
| **[wazuh-host-security-lab](https://github.com/hel7/wazuh-host-security-lab)** | Infrastructure Security & Observability | End-to-end monitoring stack combining **Wazuh SIEM/XDR**, **Suricata NIDS**, and **Prometheus + Grafana** behind an **Nginx Reverse Proxy**. Benchmarked incident response (**MTTD: 1.51s, MTTR: 0.107s** via automated `iptables` Active Response), eliminated False Positives on IPv6 MLD multicast, and benchmarked host resources during 10k HTTP DoS attacks. |
| **[E-RequestControl](https://github.com/hel7/E-RequestControl)** | Containerized Service Architecture | Multi-tier ticketing service deployed via Docker Compose. Features a Go Gin REST API backend, Vue.js single-page application frontend, MySQL relational persistence, and isolated bridge networking. |
| **[CyberSecurity](https://github.com/hel7/CyberSecurity)** | Wireless Defense & Traffic Analysis | Isolated Wi-Fi access point security testing (`hostapd`, `dnsmasq`, `iptables` NAT). Audited WPA2-PSK 4-way handshakes via dictionary attacks, and performed passive traffic analysis (Wireshark TLS SNI metadata and unencrypted HTTP interception). |

---

### 🔍 Diagnostic & Troubleshooting Focus
Hands-on experience identifying and fixing root causes under production-like scenarios:
- **Web & Proxy Routing:** Nginx reverse proxy configuration (`proxy_pass`, `Host`, `X-Real-IP`), resolving `403 Forbidden` directory permissions (`chmod 755`), and fixing port binding collisions via `ss -tulpn`.
- **Packet & Log Forensics:** Analyzing Linux `journalctl`, `/var/log/auth.log`, `access.log`, and Suricata `eve.json` / `fast.log` for multi-stage threat detection.
- **Network Defense:** Debugging stateful firewall rules (`iptables` chains, `UFW`), configuring automated IP dropping (`fail2ban`, Wazuh `firewall-drop`), and handling defense-in-depth race conditions.

---

### 📫 Connect With Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hel7ik-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hel7ik)
[![Telegram](https://img.shields.io/badge/Telegram-@wannabeinvisible-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/wannabeinvisible)
[![Email](https://img.shields.io/badge/Email-bohdan.maiboroda@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bohdan.maiboroda@gmail.com)
