# security-projects

A curated collection of cybersecurity analysis projects demonstrating hands-on experience in malware analysis, memory forensics, and network traffic investigation. All projects contain de-identified academic data and are designed to showcase practical SOC-oriented analytical skills.

---

## 📁 Projects Included

### **1. Malware Analysis – Behavioral & Static/Dynamic Examination**
Comprehensive analysis of a malicious Windows executable, including:
- Static analysis (PE structure, imports, resources)
- Dynamic behavior observation in a controlled sandbox
- IOC extraction: file modifications, registry keys, and network indicators
- Documentation of persistence mechanisms and malicious patterns

➡️ *File:* `malware-analysis.md`

---

### **2. Memory Forensics – Incident Reconstruction Using Volatility**
Deep-dive analysis of a Windows memory image using Volatility:
- Identifying malicious PIDs and parent-child chains  
- Network artifact extraction (C2 communications)  
- DLL injection detection  
- Timeline reconstruction from memory objects  
- Techniques used: `pslist`, `pstree`, `dlllist`, `netscan`, `cmdline`, `handles`

➡️ *File:* `memory-forensics.md`

---

### **3. Network Traffic Analysis – PCAP Investigation**
Structured analysis of malicious network activity:
- HTTP/S traffic inspection  
- Malicious domain/IP identification  
- Beaconing and C2 pattern detection  
- Extracting actionable IOCs for SOC reporting  
- Techniques: Wireshark filtering, flow analysis, protocol investigation  

➡️ *File:* `network-traffic-analysis.md`

---

## 🎯 Purpose
These projects highlight practical, real-world cybersecurity skills applicable to SOC Analyst roles, including:
- Threat detection  
- Incident investigation  
- IOC extraction  
- Technical reporting  
- Tool proficiency (Wireshark, Volatility, Any.Run, Sandbox tools)

---

## 🔒 Note
All datasets are academic and sanitized. No sensitive organizational data is included.

