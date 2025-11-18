# Shark-Attack-Data-Analysis
Shark Attack Dashboard Insights & Recommendations
Insights:
Analysis of global shark attack data reveals several key patterns:
.Temporal Trends: Shark attacks have fluctuated over time, with certain decades showing higher occurrences, though overall, attacks remain rare.
. Geographical Hotspots: Attacks are concentrated in specific countries, coastal areas, and particular beaches, identifying “high-risk” locations.
. Injury Patterns: The most commonly injured body parts are limbs, particularly arms and legs, reflecting typical shark behavior.
. Day and Time Patterns: Most attacks occur during daylight hours, especially morning and afternoon, when water activity is highest. Weekend trends may also contribute to higher frequencies.

📌 Overview
This project explores global shark attack incidents using Power BI.
It covers data cleaning, transformation, DAX calculations, and an interactive dashboard that reveals trends, patterns, and insights from a very dirty, unstructured dataset.

🧹 Data Cleaning & Preparation
The raw dataset contained major issues such as:
Inconsistent date formats (e.g., reported 07-june-2017)
Missing values and empty cells
“null” values mixed inside text fields
Duplicates
Mixed data types
Unstandardized categories (Provoked/Unprovoked, gender entries, etc.)

Cleaning Steps Performed
Removed “reported” and standardized all dates
Replaced embedded null text with blank or “Unknown”
Fixed inconsistent text casing
Removed duplicates
Created new measures (Total Cases, Total Male, Total Female, etc.)
Formatted columns for analysis


📊 Dashboard Features

The dashboard includes:

1️⃣ Total Cases Overview

Total shark attack incidents

Gender distribution (Male vs Female)

Type of attacks (Provoked vs Unprovoked)


2️⃣ Geographic Insight

Map visual showing countries/locations affected

Highest-risk regions


3️⃣ Trend Analysis

Cases by year

Cases by month or season (optional)


4️⃣ Additional Insights

Activity at time of attack

Fatal vs Non-fatal cases

Victim age patterns (if available)

🛠 Tools Used

Power BI Desktop

Power Query (M) for data transformation

DAX for measures & calculations

🧠 Key Learnings

This project strengthened my skills in:

Data cleaning & handling dirty datasets

Building clear data models

Writing effective DAX measures

Designing interactive and visually balanced dashboards

Communicating insights clearly


🚀 Conclusion

This project demonstrates my ability to take a messy, inconsistent dataset and transform it into a clean, insightful dashboard that supports data-driven storytelling.Exploratory data analysis and dashboard on shark attack records with insights on gender,location,and incident type.
