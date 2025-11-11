# 📊 Tableau Project — Telecom Performance & Voice Revenue Analysis  
![Performance_Analysis](images/Performance_Analysis.png)

![Voicie_Revenue_Analysis](images/Voicie_Revenue_Analysis.png)


## 🧠 Overview
This project presents a detailed **Tableau analysis of telecom performance and voice revenue trends**.  
It consists of **two main analytical parts**, each visualized through interactive dashboards built in Tableau Desktop:  

1. **Performance Analysis** — focused on tariff-based performance metrics and revenue trends.  
2. **Voice Revenue Analysis** — focused on identifying patterns behind declining voice duration.

The project demonstrates my ability to apply Tableau concepts such as **calculated fields**, **parameters**, **filters**, **dynamic KPIs**, and **dashboard actions** to create **insightful and visually clean business dashboards**.

---

## 📁 Project Structure

---

## 🟦 Part 1: Performance Analysis

### 🎯 Objective
To analyze telecom tariff performance on a **daily and weekly basis**, evaluate key performance indicators (KPIs), and present insights through dynamic dashboards.

### 💡 What I Did
- Combined and cleaned multiple Excel sheets containing revenue and subscriber data.  
- Created **calculated fields** for average revenue metrics (voice, data, on-net, off-net).  
- Designed **two interactive dashboards** — *Weekly KPI Performance* and *Daily Revenue Analysis*.  
- Applied **parameters** to dynamically switch between KPIs.  
- Added **filters** and **color indicators** for easy comparison across tariffs.  
- Incorporated **custom tooltips**, **conditional text messages**, and **growth rate calculations**.  

### 🧮 Key Calculations
```text
Average Revenue Per Subscriber = Total Revenue / Number of Subscribers
Average Voice Revenue Per Subscriber = Total Voice Revenue / Number of Voice Subscribers
Average Data Revenue Per Subscriber = Total Data Revenue / Number of Data Subscribers
Average On-net Revenue Per Subscriber = Total On-net Revenue / Number of On-net Subscribers
Average Off-net Revenue Per Subscriber = Total Off-net Revenue / Number of Off-net Subscribers

📊 Dashboard 1: Weekly KPI Performance

Purpose: Track weekly changes in Total Revenue, Usage, and other KPIs with the ability to switch metrics using parameters.

Features:

Parameter to toggle between KPIs (Revenue, Usage, MB, On-net/Off-net usage).

Weekly trend line for each KPI.

Top 5 tariffs ranked by KPI value and growth percentage.

Conditional messages:

“✅ Good news!!! KPI increased % last week.”

“⚠️ ALARM!!! KPI decreased % last week.”

Growth comparison and trend indicators.

Tools & Techniques Used:

Parameters and dynamic text fields

IF / ELSE logic for growth messages

Week-over-week % change calculation

Custom formatting and tooltips

📊 Dashboard 2: Daily Revenue Performance

Purpose: Provide an in-depth daily view of total revenue and revenue breakdown by tariff and category.

Features:

Daily total revenue trend line.

Revenue proportion of each tariff using stacked bar charts.

Daily comparison across:

Average total revenue per subscriber

Average voice/data/on-net/off-net revenues per subscriber

Cluster visualization showing the relationship between voice and data revenue.

Tooltip-based micro-trends for each tariff (daily breakdown).

Data revenue portion in total revenue (% visualization).

Design Techniques:

Clean white background, compact layout

Aligned charts with consistent labeling

Color-coded tariff groups

Intuitive filters for date range and tariff selection

📷 Performance Dashboards Preview

🟧 Part 2: Voice Revenue Analysis
🎯 Objective

To investigate and visualize the decline in voice duration among subscribers, and identify potential influencing factors such as data usage and revenue patterns.

💡 What I Did

Imported and joined 4 months of subscriber usage data.

Created custom bins for MB usage and revenue levels.

Calculated voice duration change and percentage decline per subscriber.

Designed dashboards that reveal relationships between voice decline and other usage metrics.

Built interactive charts comparing tariff performance and customer usage profiles.

📊 Dashboard 1: Subscriber Profile & Voice Decline

Purpose: Understand which customer groups experienced the highest decline in voice duration.

Features:

Analysis by MB usage group, revenue group, and total usage.

Bar and box plots comparing % change in duration.

Drill-down filters by tariff, usage range, and decline percentage.

Highlights the most affected tariffs (e.g., Tariff 6 with largest decline).

Interactive tooltip with subscriber metrics and voice trend.

Techniques Used:

Table calculations for % decline

Custom bins for MB usage

Interactive filters

Conditional color formatting to show negative trends

📊 Dashboard 2: Voice Usage Distribution

Purpose: Show distribution of subscribers and total duration across usage and revenue segments.

Features:

Distribution of MB usage (1–100, 101–500, 501–1000, etc.)

Revenue distribution across customers.

Comparison of average duration per group.

Voice duration change per tariff (highlighting steepest declines).

Visual storytelling through clean layout and KPI highlights.

📷 Voice Revenue Dashboards Preview

🧰 Tableau Features & Skills Demonstrated

Parameters and dynamic KPI switching

Calculated fields and table calculations

Dashboard actions and filters

Conditional text and color formatting

Dual-axis and combination charts

Tooltip customization with embedded trends

Cluster analysis visualization

Design principles (spacing, contrast, alignment)

🧠 Key Insights

Certain tariffs show steady weekly growth, while others experience revenue drops.

Off-net usage increased by ~3%, signaling higher external network activity.

Tariff 4 achieved the strongest growth rate week-over-week.

Voice duration declined most for high-MB users, indicating possible shift to data-based communication.

Tariff 6 showed the sharpest voice usage decline over the 4-month period.

🧑‍💻 Tools Used

Tableau Desktop — dashboard creation and analysis

Microsoft Excel — data cleaning and preparation

PowerPoint / Photoshop (optional) — image exports and layout adjustments

🪄 Project Highlights

Fully interactive dashboards designed for business presentation.

Clean, professional visual layout and intuitive navigation.

Actionable insights from telecom data using analytical storytelling.

Application of advanced Tableau techniques for interactivity and automation.

📂 Files Included
File	Description
Telecom_Project.twb	Tableau workbook file containing all dashboards
Performance_Analysis.png	Screenshot of performance dashboards
Voicie_Revenue_Analysis.png	Screenshot of voice analysis dashboards
dataset.xlsx	Data used for analysis (revenues, subscribers, usage)
README.md	This documentation file
🏁 Summary

This Tableau project showcases end-to-end data visualization and analysis for a telecom dataset, covering both business performance and behavioral usage insights.
It reflects a full application of Tableau techniques, analytical reasoning, and clean visual storytelling for executive-level decision support.


