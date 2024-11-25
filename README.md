# Aviation Safety Analysis 🛩️

## Overview ✈️
This project focuses on analyzing aviation accident data to uncover trends, identify safety risks, and propose actionable improvements for enhancing aviation safety. By examining key factors such as injury severity, weather conditions, and state-wise distributions, this analysis aims to help stakeholders implement targeted interventions to reduce aviation incidents.

---

## Objectives 🎯
- **Identify Trends:** Analyze how aviation incidents have evolved over time.
- **Geographic Focus:** Highlight regions with higher occurrences of incidents.
- **Severity Assessment:** Examine the severity of injuries and damage.
- **Contributing Factors:** Investigate roles of weather, flight phases, and other elements.
- **Actionable Insights:** Provide recommendations for safety improvements.

---

## Dataset 📂
### Sources:
- **AviationData.csv:** Contains detailed records of aviation incidents, including dates, locations, severity, and contributing factors.
- **USState_Codes.csv:** Maps state names to their abbreviations.

### Key Features:
- Event details (Date, Location, Severity).
- Aircraft specifications (Make, Model, Damage).
- Weather conditions and flight phase.

### Data Statistics:
- **Total Rows:** 88,889
- **Columns:** 31
- Missing data handled through cleaning and imputation where necessary.

---

## Data Preparation 🛠️
- **Cleaning:** Removed rows with missing critical fields like location and severity.
- **Feature Engineering:**
  - Extracted state codes for geographic analysis.
  - Added derived fields for fatalities and total casualties.
  - Converted date fields to extract time-based trends.
- **Merging:** Integrated datasets using state abbreviations for enhanced analysis.

---

## Analysis & Insights 📊

### 1. **Yearly Trends**
- **Key Finding:** Incident counts fluctuate annually, reflecting potential impacts of safety interventions and traffic changes.
- **Visualization:** Line plot shows peaks and declines in incidents over decades.

### 2. **State-Wise Distribution**
- **Key Finding:** States like California and Florida show higher incident counts, likely due to high air traffic.
- **Visualization:** Bar chart highlights incident density per state.

### 3. **Injury Severity**
- **Key Finding:** Severity ranges widely, with "Non-Fatal" and "Serious" categories dominating the dataset.
- **Visualization:** Bar chart of injury severity distribution.

### 4. **Weather Impacts**
- **Key Finding:** Visual Meteorological Conditions (VMC) account for the majority, but Instrument Meteorological Conditions (IMC) incidents are proportionally riskier.
- **Recommendation:** Improved training and tools for IMC scenarios.

### 5. **Flight Phases**
- **Key Finding:** Takeoff, landing, and approach phases see the most incidents.
- **Recommendation:** Enhanced training for these critical phases.

---

## Recommendations 🛡️
- **State-Specific Measures:** Focused audits and safety investments in high-risk states.
- **Weather Readiness:** Advanced radar and stricter operational protocols during adverse conditions.
- **Pilot Training:** Emphasize takeoff and landing procedures in simulations.
- **Aircraft Design:** Incorporate materials and designs that mitigate damage.

---

## Tools & Libraries 🧰
- **Languages:** Python
- **Libraries:** `pandas`, `matplotlib`, `seaborn`
- **Visualization Tools:** Tableau for interactive dashboards.

---

## Visualizations 🖼️
1. **Yearly Trends of Incidents**
2. **State-Wise Incident Map**
3. **Accident Severity Distribution**
4. **Phase of Flight Analysis**

---

## Deployment 🚀
The cleaned dataset (`Cleaned_AviationData.csv`) and visual insights are made available for stakeholders. These insights can guide interventions, policy-making, and operational improvements.

---

## Next Steps 🔍
1. **Automated Dashboards:** Develop real-time dashboards for incident monitoring.
2. **Predictive Modeling:** Build machine learning models to forecast risk areas.
3. **Collaboration:** Share insights with regulatory bodies and industry leaders.

---

### Contact 📧
For questions or contributions, please reach out at:  
**Email:** [maureen.maina@students.moringaschool.com]  
**GitHub:** (https://github.com/Maureen-Maina03/Phase1-Project)

---

*Let's make aviation safer, together!* 🌟
