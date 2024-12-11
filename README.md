# DNS Top Scenarios Log Analysis
This project focuses on analyzing DNS logs from the **botsv1 data log set**, with dashboards and queries designed to provide insights into DNS behavior. Below are the key scenarios analyzed:
![Top Scenarios](Projects/DNS%20Top%20Scenarios.png)

### **1. Top 10 IPs with NXDOMAIN Response Code**
- Identifies the IPs generating the most queries resulting in the NXDOMAIN response.
- Useful for detecting misconfigured systems or potential reconnaissance activity.
### **2. Top 10 IPs with REFUSED Reply Code**
- Lists the IPs responsible for queries resulting in the REFUSED response code.
- Highlights unauthorized DNS usage or access restrictions in effect.

### **3. Top NXDOMAIN Reply Code**
- Analyzes the occurrence of NXDOMAIN response codes across the dataset.
- Helps understand patterns in failed DNS resolutions.

### **4. Top Query Type Reply Codes**
- Aggregates the response codes by query type (e.g., A, AAAA, MX).
- Useful for understanding how different query types are resolved or fail.

### **5. Top Query Types**
- Displays the most common DNS query types observed in the log set (e.g., A, AAAA, MX, PTR).
- Provides insights into DNS usage trends and the nature of network activity.

---

Each query is written and optimized for the **botsv1 data log set** to extract actionable insights and visualize patterns effectively. The dashboards and saved searches make it easier to identify anomalies and improve DNS operations.
