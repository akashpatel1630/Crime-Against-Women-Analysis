1. Crimes Against Women Tracker: India 2001-2021 Analysis Dashboard:
An interactive Power BI visualization analyzing the alarming rise in crimes against women across India, highlighting trends, state-wise hotspots, and domestic violence prevalence over two decades.

2. Purpose
This dashboard tracks crimes against women in India from 2001-2021 using NCRB data, showing a 151% growth surge and identifying Uttar Pradesh as the leading state. It reveals domestic violence as the most common crime (35% of cases), aiding policymakers, activists, and researchers in addressing gender-based violence trends.

3. Tech Stack
The dashboard leverages Power BI tools for comprehensive crime data analysis:

📊 Power BI Desktop – Core platform for interactive visualizations and dashboards.

📈 Power Query – Data cleaning, transformation, and year-wise aggregation from raw NCRB datasets.

🧮 DAX Measures – Custom calculations for YoY growth (151%), crime percentages, and state rankings.

🔗 Data Model – Star schema linking years, states, and crime types for slicer-driven filtering.

📁 Formats – .pbit for sharing and .jpg for static previews.

Example: The dashboard was built using the following tools and technologies:
• 📊 Power BI Desktop – Main data visualization platform used for report creation.
• 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.
• 🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.
• 📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.
• 📁 File Format – .pbix for development and .png for dashboard previews.

4. Data Source
Source: National Crime Records Bureau (NCRB) reports via data.gov.in, covering 2001-2021.
​Structured as time-series data with ~5M total cases, including breakdowns by crime heads (rape, kidnapping, domestic violence under IPC 498A) across states/UTs, female population metrics, and rates per lakh women

5. Features / Highlights
Problem
Crimes against women reached 445,256 cases in recent years (51/hour), with a 15% YoY surge and Uttar Pradesh reporting the highest volume (65,743+ cases). Key challenges include underreporting, regional disparities, and domestic violence dominance (31-35%), hindering targeted interventions.
​
Goal of the Dashboard
Provide an interactive tool for visualizing temporal trends (2001-2021), state comparisons, and crime-type breakdowns to support advocacy, policy formulation, and awareness campaigns on women's safety.​

Key Visuals Walkthrough
Trend Line Chart: Shows total crimes rising from ~200K to 5M+ with 151% YoY growth peak in 2021.​
Pie Chart: Domestic violence leads at 35%, followed by assault (18.7%) and kidnapping (19.2%).​
State Bar Chart: Uttar Pradesh tops, followed by Maharashtra, West Bengal—enabling geographic filtering.​
Slicers: Year (2001-2021), state, and crime type selectors for dynamic exploration.​

Impact & Insights
Policy Focus: Highlights UP/MP/WB as intervention priorities, where rates exceed national 66.4/lakh.​
Awareness: Reveals domestic violence hotspots, informing NGO campaigns and helplines.
Research Value: Enables trend forecasting for SDG 5.2, showing sustained 4%+ annual rises.

6. Demo:
This how the dashboard looks like: https://github.com/akashpatel1630/Crime-Against-Women-Analysis/blob/main/Snapshot%20of%20Dashboard.png
