# 🧪 DNS Anomaly Detection

📂 [Download PCAP](../pcaps/dns-anomaly.pcap)  

---

## 🎯 Objective
Analyze suspicious DNS traffic to identify potential signs of malware communication.

---

## 🔍 Analysis
- Observed multiple DNS queries to random subdomains (`a9d83k.example.com`, `b7k21p.example.com`).  
- Query frequency was much higher than normal browsing activity.  
- Traffic pattern consistent with a Domain Generation Algorithm (DGA).  

---

## 📸 Screenshots
![DNS Query Screenshot](../images/dns-anomaly-query.png)

---

## 📝 Conclusion
The traffic strongly indicates automated DNS queries consistent with malware beaconing behavior.  
Likely attempting to contact a Command & Control server using DGA.
