📊 Psychology Clinic Management Dashboard (Excel & BI)

📌 Project Overview

This project was developed to solve a common operational challenge for small psychology clinics: unstructured data and lack of clear management indicators.

The goal was to transform a messy, manually updated spreadsheet into an automated, interactive decision-making dashboard within Microsoft Excel—the client's preferred tool—without introducing unnecessary complexity.

🎯 Problem Statement (SPIN Methodology Context)

Situation: The clinic logged patient appointments, attendance, revenue, and schedules across disorganized Excel sheets.

Problem: Data was fragmented, leading to frequent manual errors, unknown schedule occupation rates, and unclear financial visibility.

Implication: The owner spent hours at the end of each month manually organizing tables instead of focusing on strategic decisions, risking revenue leaks from unmonitored cancellation rates and idle hours.

Need-Payoff: A clean, automated Excel solution using familiar interfaces that presents critical KPIs instantly upon data entry.

🛠️ Tech Stack & Methodology

Power Query: Used for ETL (Extract, Transform, Load) processes to clean messy raw data, remove duplicates, format dates, and automate schema standardization.

Power Pivot & Data Modeling: Modeled relationships between patient logs, financial tables, and calendars. Created DAX measures for core KPIs.

Data Storytelling & UX Design: Designed a clean, intuitive layout focusing on usability, visual hierarchy, and fast reading.

📈 Key Indicators & Features

Schedule Occupation Rate: Track active vs. idle consultation slots.

Patient Retention & Attendance: Monitor show-up rates, cancellations, and drop-outs.

Financial Overview: Revenue per period, average revenue per patient, and outstanding payments.

Interactive Slicers: Filter data seamlessly by month, service type, or practitioner.

📂 Repository Structure

├── data/
│   └── raw_sample_data.xlsx      # Anonymized sample data format
├── docs/
│   └── dashboard_preview.png     # Dashboard screenshot/gif
├── Psychology_Clinic_Dashboard.xlsx # Final Excel workbook (Power Query + Power Pivot)
└── README.md                     # Project documentation


🚀 How to Use

Clone or download this repository:

git clone https://github.com/your-username/psychology-clinic-dashboard.git


Open Psychology_Clinic_Dashboard.xlsx in Microsoft Excel (2016 or newer recommended).

Add new operational rows to the data table and hit Data > Refresh All to automatically update the dashboard.

💬 Author & Contact

Developed by [Marcelo Rodrigues] — BI & Data Analytics Specialist.

💼 LinkedIn:https://www.linkedin.com/in/marcelordasilva/

✉️ Email ma23cgl@gmail.com

