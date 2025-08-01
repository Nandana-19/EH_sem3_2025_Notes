# EH_sem3_2025_Notes
# 📡 1st Assignment – DNS and IP Discovery

## 🎯 Objective
The purpose of this assignment was to perform DNS and IP discovery on a target system (`zero.webappsecurity.com`) using various cybersecurity tools and methods. The goal was to understand how domain names resolve to IP addresses, trace network paths, scan ports, and analyze exposure using online intelligence platforms.



##  Tools Used
- **nslookup** – Domain to IP resolution
- **tracert** – Route tracing to the server
- **nmap** – Network scanning and port discovery
- **Shodan** – Public internet exposure check
- **VirusTotal** – Malware and security reputation analysis
- **Bash (Kali Linux)** – Script automation for recon tasks

---

##  Folder Structure
1st Assignment/
├── evidence/ # Screenshots of all tool outputs
│ ├── nslookup.png
│ ├── tracert.png
│ ├── nmap.png
│ ├── shodan.png
│ └── virustotal.png
├── report/ # Final report in PDF format
│ └── dns_ip_report.pdf
├── scripts/ # Recon automation script
│ └── dns_discovery.sh
└── README.md # Assignment summary and structure

yaml
Copy
Edit

---

## 📄 Summary of Tasks

### 🔍 DNS Resolution
Used `nslookup` to resolve the IP of the domain.  
**Result:** `54.82.22.214`

### 🚚 Traceroute
Mapped the path from local system to the server using `tracert`. Some hops timed out, which is normal for secure/cloud-hosted environments.

### 🔎 Nmap Scan
Performed basic port scanning with `nmap`.  
**Open ports found:** 80 (HTTP), 443 (HTTPS)

### 🌐 Shodan Search
Searched the IP on [Shodan.io](https://www.shodan.io). Found limited info — confirmed it's hosted on AWS with no critical exposures.

### 🔐 VirusTotal Analysis
Checked the domain on [VirusTotal](https://www.virustotal.com). Result showed 0/93 engines flagged it — marked clean.

---

## 💡 Automation Script
A custom Bash script (`dns_discovery.sh`) was created and run in Kali Linux to automate:
- DNS resolution
- Traceroute
- Nmap scanning

This demonstrated the ability to script and automate basic reconnaissance steps.

---

## ✅ Completion Checklist

- [x] GitHub repo created with correct name
- [x] `1st Assignment/` structure set up
- [x] Screenshots collected
- [x] PDF report written
- [x] Bash script uploaded
- [x] README file added
- [x] Ready for final submission



## Notes
- All tools were used for educational purposes only
- Only authorized targets were tested
- All screenshots and evidence are included


