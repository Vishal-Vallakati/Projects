## **IDS Monitoring with botsv2 Dataset**

This project focuses on monitoring Intrusion Detection System (IDS) alerts from the **botsv2 data log set**, providing insights into potential security threats and attack patterns. Below are the key scenarios analyzed:
![IDS Monitoring](https://github.com/Vishal-Vallakati/Projects/blob/IDS-Monitoring/IDS%20Monitoring.png)

### **1. Allowed Intrusion Attempts**
- Identifies intrusion attempts that were allowed to pass through the IDS.
- Useful for detecting potential misconfigurations or overlooked security vulnerabilities that allowed unauthorized access.

### **2. Blocked Intrusion Attempts**
- Identifies intrusion attempts that were blocked by the IDS.
- Helps in monitoring attacks that were detected and successfully blocked by the system.

### **3. Medium Severity Alerts**
- Retrieves alerts with medium severity, indicating potential threats that might not be immediately dangerous but still warrant investigation.
- Provides a focus on moderate-level threats, which can often be overlooked.

### **4. Intrusion Alerts by Signature**
- Aggregates intrusion alerts based on their signature, helping to identify the most common attack patterns detected by the IDS.
- Useful for recognizing recurring threats or patterns of attacks targeting specific vulnerabilities.

### **5. Intrusion Alerts by Signature and Severity**
- Combines both the intrusion signature and severity to provide a more granular view of the IDS alerts.
- Helps in understanding the risk level associated with specific signatures and patterns of attacks.

---

Each query is written and optimized for the **botsv2 data log set** for the date range **August 10, 2016 to August 11, 2016** to extract actionable insights into IDS activity. The dashboards and saved searches make it easier to monitor intrusion attempts, track alerts by severity, and detect any abnormal security events.

