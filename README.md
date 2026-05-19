# Weekly Matter Report Dashboard
A re-creation of my customized dashboard I use to track the status, age, and outstanding items of legal matters

## Introduction
I currently work in Big Law as a conflict/new business intake analyst assisting in the IP, Employee Benefits, and Private Client practice Groups. In a Big Law setting, the influx of matters is substantial compared to other legal sectors. Some weeks, we receive up to 50 and a many require complex waiver processes or even need expediting to close a deal. 

However, there is no standardized tracking system for matters. Team members develop their own way of keeping track of their matters, but a significant portion rely entirely on manual data entry. With plenty of information needed to keep track of, data entry can take up to 30 minutes a day, which also creates human error.

Leveraging, my prior experience working with retail sales data, training from Google Data Analytics Specialization, and earning my bachelor's in business from San Jose State University, I created an ETL pipeline and dashboard to keep track of my matters and showcase personal metrics during weekly meetings.

<p align="center">
<img width="735" height="632" alt="Weekly Dashboard" src="https://github.com/user-attachments/assets/9c56469a-8778-4da7-bfb5-6efa309a2d0d" />
</p>

This dashboard visualizes essential tracking information, focusing on what items are outstanding for in-progress matters before they can be opened, and exactly how long those matters have been pending. It also features a third chart tracking matter distribution by practice group. This metric became critical following a recent lateral partner arrival, which triggered a massive influx of new work within the Employee Benefits group.


## Dataset
The following dataset is generated from Random funcions and can be found in the repository file [Work Dashboard - Queue.csv](Work%20Dashboard%20-%20Queue.csv).

### Transformation & Cleaning Steps
1. **Data Generation & Privacy Compliance:** Because Big Law firm data is privileged and confidential, I engineered a fully synthesized dataset. Using a variation ofrandomization functions, I generated random client and attorney names.
2. **Data Extraction:** Since the conflicts database allows me to export my queue into Excel, I created an export sheet to paste new matters into. The main "Queue" spreadsheet then extracts necessary information from that raw export, while keeping track of outstanding items and real-time status updates using custom dropdown selectors.
---

## Business Impact & Core Metrics
* **Eliminated Administrative Drain:** Automated data entry, mitigating administrative overhead through an automated ETL pipeline.
* **Data-Driven Performance:** Established metrics-based reporting to streamline weekly manager meetings, optimizing discussion time by visually presenting my personal queue rather than reviewing each individual matter.

## Conclusion
This project demonstrated how data analyis can be used to modernize traditional corporate workflows. By engineering this automated pipeline and dashboard, I eliminated repetitive manual data entry, established clear performance tracking, and optimized the efficiency of weekly. This experience helped me understand the value of data-driven workflows in a legal compliance setting, proving that data analysis can transform daily administrative bottlenecks into clean, accurate, and reliable matter tracking.

