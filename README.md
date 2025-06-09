## The Impact of AI Policies and Education For Future Market

## Introduction
Global economies are experiencing rapid shifts due to artificial intelligence (AI), which has an impact on how governments construct education systems, invest in research, and create laws. Countries have implemented AI-specific policies to improve workforce preparedness, digital infrastructure, and ethical AI governance, given that they recognize the technology's revolutionary potential. Simultaneously, educational systems are evolving to better prepare students for a future led by AI, especially by expanding access to technology, STEM education, and digital literacy.

The OECD AI Policy Observatory and UN Sustainable Development Goals (SDG) Indicators datasets are made freely available for this project. The SDG dataset sheds light on educational variables like gender parity, ICT proficiency, literacy rates, and school enrollment levels, whereas the OECD dataset documents national AI initiatives and policy areas across nations. Through the integration and analysis of these statistics, the initiative seeks to identify trends and connections between the implementation of AI policies and educational outcomes.

## Methodology
To examine the correlation between AI policy and educational performance across numerous nations, this study combines two reliable datasets. Data extraction, cleaning, transformation, and visualization were performed using Power BI.

### 1. Data Sources

#### a. OECD.AI Policy Observatory
- Includes detailed records of national AI policies from multiple countries
- Categorized by deployment year, policy area (e.g., education, workforce, ethics), and implementation status
- Data Source: [OECD AI Policy Database](https://oecd.ai/en/dashboards/policy-database)

#### b. UN Sustainable Development Goals (SDG) – Education Indicators
- Focuses on global education metrics including literacy rates, enrollment, ICT skills, and gender-specific completion rates at various education levels
- Data Source: [UN SDG Global Database](https://unstats.un.org/sdgs/indicators/database/)

### 2. Importing Data
CSV files from both SDG and OECD sources were imported into Power BI using the Power Query Editor.

### 3. Data Cleaning
- Removed duplicate and null records
- Standardized country names for consistent merging
- Filtered columns based on relevance: gender, indicator labels, deployment year, and policy type

### 4. Data Transformation
- Created derived fields such as gender-based educational metrics
- Generated "AI Policy Count per Country" and "Distinct Policy Areas"
- Merged datasets using shared dimensions (e.g., Year, Country)

### 5. Data Enrichment
- Added geographic context with custom fields (e.g., Region from `SDG_REGION.csv`)
- Created new metrics to evaluate policy diversity, policy volume, and educational performance indicators

This integrated approach provides meaningful insights into how AI policy initiatives correlate with educational development, paving the way for data-driven policymaking and education reform strategies.
