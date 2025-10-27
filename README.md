# VAPT Lab Study on EternalBlue and Shellshock


## Project Overview

This project is an educational Vulnerability Assessment and Penetration Testing (VAPT) study conducted in a safe and isolated virtual environment.  
It focuses on two well-known remote code execution vulnerabilities:

| Vulnerability | CVE ID | Target System | Description |
|----------------|--------|----------------|--------------|
| EternalBlue | CVE-2017-0144 | Windows SMBv1 | A remote code execution vulnerability in the SMBv1 protocol that was exploited by the WannaCry and NotPetya attacks. |
| Shellshock | CVE-2014-6271 | GNU Bash (Linux) | A Bash vulnerability that allowed code execution through specially crafted environment variables. |

The analysis was performed ethically using **Metasploit Framework** only for module information and vulnerability verification.  
No exploit payloads were executed at any stage of the experiment.

---

## Objectives

- Understand the root cause and impact of the EternalBlue and Shellshock vulnerabilities.  
- Use Metasploit to analyze module details, references, and affected versions.  
- Perform safe vulnerability verification using network scans and service analysis.  
- Document the complete workflow, findings, and mitigations in a professional report format.

---

## Lab Environment

**Virtual Machines:**
- Kali Linux – used for reconnaissance, Metasploit module review, and network captures.  
- Windows 7 – target system used to demonstrate SMBv1 configuration and patch verification.  
- Ubuntu / Metasploitable2 – target system used to demonstrate the Shellshock environment behavior.

**Network Configuration:**  
All systems were connected through a host-only or internal network.  
No public or production systems were accessed or tested.

---

## Report Contents

The full report (`FinalReport.pdf`) includes:

1. Background and description of both vulnerabilities.  
2. Details of the isolated lab setup.  
3. Safe analysis steps and collected evidence (screenshots and logs).  
4. Verification of patched versus unpatched behavior.  
5. Detection, mitigation, and future recommendations.

---

## Files

| File | Description |
|------|-------------|
| FinalReport.pdf | Complete report with screenshots, analysis, and mitigation steps. |
| README.md | This file describing the purpose and scope of the report. |

---

## Disclaimer

This project was carried out strictly for **educational and research purposes**.  
All testing was done inside a **controlled virtual lab** owned by the author.  
No real-world systems or networks were targeted, affected, or accessed.  
The author does **not encourage or support any misuse** of the concepts discussed.  
Readers must ensure they have explicit authorization before conducting any form of penetration testing.

---

## Author

**Aazaf Ritha. J**  
Cybersecurity Undergraduate | Cybersecurity Enthusiast | Student Researcher
Sri Lanka Institute of Information Technology (SLIIT)  
Phone: +94 76 073 7173  
Email: jamahiraazafritha@gmail.com  
LinkedIn: [https://www.linkedin.com/in/aazafritha](https://www.linkedin.com/in/aazafritha)  
GitHub: [https://github.com/aazafritha](https://github.com/aazafritha)  
Medium: [https://medium.com/@jamahiraazafritha]([https://medium.com/@jamahiraazafritha]) 
