# SIEM Assignment – Elastic & Splunk

This repository contains my SIEM (Security Information & Event Management) assignment using **Elastic Cloud (Serverless Security)** and **Splunk Cloud**, including log ingestion, visualization, dashboards, and security event analysis.

---

## 📁 Repository Structure


SIEM-Assignment/
│
|__README.md
|
├── Elastic/
│ ├── screenshots/ # Contains all Elastic screenshots
│ 
└── Splunk/
|  ├── screenshots/ # Contains all Splunk screenshots
|
|__Report/
   |__CS02


---

# 🟦 Part 1 – Elastic Cloud (Serverless Security)

## ✔️ Tasks Completed

### **1. Elastic Cloud Setup**
- Created an Elastic Cloud **Serverless Security Project**
- Viewed the Elastic Deployment dashboard

### **2. Elastic Agent Installation**
- Installed Elastic Agent on local Windows  
- Successfully enrolled the agent into Elastic Fleet  
- Verified that the Agent status is **Healthy**

### **3. Log Ingestion – Custom Filestream Logs**
- Created a **Custom Logs (Filestream)** integration  
- Added integration to Agent Policy  
- Confirmed logs flowing in Discover

### **4. Discover – Filter & View Logs**
Filtered custom logs using:

data_stream.dataset : "filestream.generic"

Verified logs with fields such as:
- user  
- ip  
- action  
- threat  
- @timestamp  

### **5. Visualizations Created**
- **Bar Chart** – Events over time  
- **Pie Chart** – Events by user  
- **Data Table** – Event details (user, IP, action, threat)

### **6. Elastic Dashboard**
- Combined visualizations into a single dashboard  
- Saved dashboard for final submission

---

## 📸 Elastic Screenshots
All Elastic screenshots can be found here:  
📂 `/Elastic/screenshots/`

Included screenshots:
- Elastic Deployment  
- Healthy Elastic Agent in Fleet  
- Discover view showing `filestream.generic` logs  
- Visualizations (Pie, Bar, Table)  
- Final Dashboard  


---


# 🟧 Part 2 – Splunk Cloud

## ✔️ Tasks Completed

### **1. Splunk Cloud Setup**
- Created Splunk Cloud Free Trial  
- Added log files using “Upload Data”

### **2. Search & Reporting**
Used SPL queries such as:

index=* | stats count by user
index=* | timechart count
index=* | table _time user ip action threat


### **3. Splunk Visualizations Created**
- **Timechart** – Event count over time  
- **Pie Chart** – Events by user  
- **Table** – Detailed event summary  

### **4. Splunk Dashboard**
- Created dashboard with 2–3 visualizations  
- Saved dashboard for final submission  

---

## 📸 Splunk Screenshots
All Splunk screenshots can be found here:  
📂 `/Splunk/screenshots/`

Included screenshots:
- Splunk Home  
- Add Data  
- Search & Reporting  
- SPL queries  
- Dashboard visualizations
  
---

# 🟦 Part 3 – REPORT
## 📄 Full detailed report:  
📌 `/CS02.pdf`

---

# 🎯 Conclusion
This assignment demonstrates:
- Ability to use **Elastic & Splunk** as SIEM tools  
- Ingesting and analyzing security logs  
- Writing **KQL** and **SPL** queries  
- Building dashboards for threat detection  
- Understanding event relationships (user, IP, threat, action)

Both platforms were successfully configured and used to generate insights from custom log data.

---

# 🚀 How to View
No execution needed.  
Simply open the PDFs or browse the screenshots.

---

# 📧 Contact
For any clarifications or to request raw log files, feel free to connect.

---

**End of README.md**
