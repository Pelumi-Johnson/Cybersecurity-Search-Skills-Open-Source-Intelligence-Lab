# 🕵️‍♂️ Cybersecurity Search Skills & Open-Source Intelligence Lab
📄 **Full Lab Report (Google Doc):**  
👉 [Click here to open the complete lab report]()

This project documents my hands-on learning experience from the TryHackMe "Search Skills" room. The goal of this lab was to build strong cybersecurity search techniques, develop OSINT awareness, and learn how to evaluate information sources, analyze data breaches, investigate files, and use specialized cybersecurity tools.

---

## 📌 Project Overview

Throughout this lab, I learned how to effectively search, evaluate, and investigate digital information using cybersecurity-focused tools.  
The lessons included:

- Evaluating credibility of online sources  
- Using Google Advanced Search operators  
- Investigating exposed systems with Shodan & Censys  
- Scanning suspicious files with VirusTotal  
- Checking breach exposure via HaveIBeenPwned  
- Understanding CVEs & researching vulnerabilities  
- Reading Linux and Windows official documentation  
- Performing basic OSINT reconnaissance using social media  

---

## 🛠️ Tools Used

- Google Advanced Search Operators  
- Shodan  
- Censys  
- VirusTotal  
- Have I Been Pwned  
- MITRE CVE Database  
- Exploit-DB  
- Linux man pages  
- Microsoft Docs  

---

## 🔍 1. Searching & Evaluating Sources

Learned how to analyze:
- Source credibility  
- Evidence and reasoning  
- Bias or agenda  
- Consistency across multiple reputable sources  

Understanding this helps avoid misleading or low-quality information.

---

## 🔎 2. Google Advanced Search Operators

Practiced using operators such as:

- "exact phrase"  
- site:  
- filetype:  
- - (exclude words)  
- OR logic  

Example query:
filetype:pdf "cyber warfare report"

This returned only PDF documents related to the topic.

---

## 🌐 3. Shodan & Censys Investigation

### Shodan
- Searched for "lighttpd"  
- Found over 2.4 million exposed servers  
- Viewed banners, locations, and metadata  

### Censys
- Queried Apache version 2.4.1  
- Compared host details, certificates, and exposed services  

Both tools showed how attackers identify outdated, vulnerable systems.

---

## 🧪 4. VirusTotal File Analysis

- Submitted a file hash for analysis  
- VirusTotal scanned using 57 antivirus engines  
- Some vendors flagged it as malicious  
- Compared detections between AV engines  

---

## 🔐 5. Data Breach Lookup (HaveIBeenPwned)

- Entered an email into HIBP  
- Checked which breaches it appeared in  
- Learned how attackers use leaked information to compromise accounts  

---

## 📁 6. Vulnerabilities, CVEs & Exploit-DB

### CVE Research
- Reviewed CVE-2014-0160 (Heartbleed)  
- Reviewed CVE-2024-3094 (xz utility)  
- Learned how CVEs standardize vulnerability identification  

### Exploit-DB
- Viewed Heartbleed exploit code used for testing  
- Understood the purpose of verified public exploits  

---

## 📖 7. Linux & Windows Documentation Skills

### Linux – "man ip"
- Used manual pages to examine the ip command  
- Learned parameters, structure, and usage  

### Windows – "netstat -b"
- Learned that "-b" shows which executable (.exe) created each network connection  
- Useful for identifying suspicious or unauthorized processes  

---

## 🕵️ 8. OSINT & Social Media Reconnaissance

Learned how attackers use information posted online:

- LinkedIn → job roles, skills, technologies  
- Facebook → personal history, childhood schools, relationships  

Understanding this helps both offense (recon) and defense (privacy protection).

---

## 📚 Lessons Learned

1. Be mindful of personal information posted online attackers use overshared details during recon.  
2. Avoid posting sensitive information such as childhood schools or family details.  
3. Use alternate emails to explore platforms safely without exposing your real accounts.  
4. Cybersecurity learners should explore platforms, not avoid them—you learn by engaging.  
5. Social media is a powerful OSINT tool; understand how attackers gather information.

---

## 🏁 Final Thoughts

This project strengthened my foundation in:

- Cybersecurity research  
- Search engine mastery  
- OSINT techniques  
- Vulnerability investigation  
- Malware analysis  
- Network documentation review  
- Understanding attacker reconnaissance  

This lab grew both my investigative mindset and defensive awareness—core skills for a future cybersecurity analyst.

