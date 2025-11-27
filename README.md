FDA Food Safety Enforcement Analysis

Project Overview:  
Goal: To audit 20,000+ FDA food recall records and identify the most critical breakdown points in food safety protocols. Tools Used: Python, Pandas (Data Analysis), Seaborn (Visualization), NLP (Text Cleaning).

Key Findings (The "Research" Part)
My analysis of the FDA Enforcement data (2008–2022) revealed:

Labeling is the #1 Failure: "Undeclared Allergens" are the most frequent cause of recalls (~6,400 incidents), surpassing biological pathogens. This indicates a systemic failure in labeling verification (CCP) rather than just sanitation.

Biological Hazards: Listeria monocytogenes (~6,000 incidents) is the dominant pathogen, highlighting the need for stricter Environmental Monitoring Programs (EMP).

Process Failures: Significant recalls were linked to "GMP Failures," showing gaps in basic sanitation and process controls.

## 📊 Strategic Analysis & Visualizations

### 1. The "What": Risk Categorization
**Finding:** Labeling errors (Undeclared Allergens) are the leading cause of recalls, outpacing biological pathogens.
![Risk Categories](fda_recall_graph.png)

---

### 2. The "When": Trend Analysis (2012-2022)
**Finding:** Food recalls remained stable until 2020. A significant drop occurred during the height of the COVID-19 pandemic (2020-2021), likely due to reduced on-site facility inspections by regulatory bodies, rather than an improvement in safety standards.
![Time Trend](recall_trend_line.png)

---

### 3. The "Where": Geographic Hotspots
**Finding:** California (CA) is the primary hub for recall events, accounting for nearly double the incidents of the next highest state (Texas). Notably, the dataset includes Canadian provinces (Ontario, Quebec), indicating active FDA enforcement on imported supply chains.
![Geographic Map](geo_analysis_states.png)
How to Run This Project:  
Clone the repository.
Install requirements: pip install pandas, seaborn
Run FDA_Food_Safety_Audit.ipynb.
