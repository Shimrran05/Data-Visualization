##Introduction:
Global economies are experiencing rapid shifts due to artificial intelligence (AI), which has an impact on how governments construct education systems, invest in research, and create laws. Countries have implemented AI-specific policies to improve workforce preparedness, digital infrastructure, and ethical AI governance given that they recognize the technology's revolutionary potential. Simultaneously, educational systems are evolving to better prepare students for a future led by AI, especially by expanding access to technology, STEM education, and digital literacy.
The OECD AI Policy Observatory and UN Sustainable Development Goals (SDG) Indicators datasets are made freely available for this project. The SDG dataset sheds light on educational variables like gender parity, ICT proficiency, literacy rates, and school enrollment levels, whereas the OECD dataset documents national AI initiatives and policy areas across nations. Through the integration and analysis of these statistics, the initiative seeks to identify trends and connections between the implementation of AI policies and educational results.
Methodology:
With the objective to examine the correlation between AI policy and educational performance across numerous nations, this study combines two reliable datasets. Data extraction, cleaning, transformation, and visualization using Power BI are all part of the technique.
1. Data Sources
a. OECD.AI Policy Observatory
•	This dataset includes detailed records of national AI policies from multiple countries, categorized by deployment year, policy area (e.g., education, workforce, ethics), and implementation status.
•	Data was collected from the OECD AI Policy Database:
🔗 https://oecd.ai/en/dashboards/policy-database 
b. UN Sustainable Development Goals (SDG) – Education Indicators
•	The SDG dataset focuses on global education metrics, including literacy rates, enrollment, ICT skills, and gender-specific completion rates at different education levels.
•	Data sourced from the UN SDG Global Database:
🔗 https://unstats.un.org/sdgs/indicators/database/

2.  Importing Data
Using the Power Query Editor, CSV files from the SDG and OECD sources were imported into Power BI.

Data Cleaning
Duplicate or null records were eliminated. Standardized Country names to guarantee uniform merging. Filtered pertinent columns, including gender, indicator labels, deployment year, and policy kind.

Transformation of Data
Generated columns for gender-based breakdowns of education metrics, "AI Policy Count per Country," and "Distinct Policy Areas." Combined datasets with shared dimensions (e.g., Year, Country).

Enrichment of Data
To facilitate geographic analysis, custom columns such as Region were added (via SDG_REGION.csv). Created derivative fields for diversity, policy volume, and metrics measuring educational performance.
