# 🚘 GLOBAL ROAD ACCIDENT ANALYSIS & NIGERIA VALIDATION REPORT

> **Collaborative Data Analytics Project — Team 7**

---

##  Interactive Dashboard Overview

![Global Road Accident Analytics Dashboard](Screenshot%20of%20the%20Primary%20Data%20Dashboard%20(1).jpg)

---

##  Story of the Data
Road traffic accidents remain one of the leading causes of preventable deaths and injuries worldwide. Despite continuous advancements in transportation systems and safety campaigns, accident rates continue to rise due to human behavior, poor infrastructure, inadequate enforcement, and environmental factors. 

This project analyzes global road accident patterns using a **Secondary Global Dataset** and validates the findings using a **Primary Nigeria Road Crash Dataset**. The goal is to determine whether global behavioral patterns (such as speeding, driver fatigue, and impaired driving) hold true within localized road safety ecosystems.

---

##  Project Details & Scope

* **Industry Context:** Transportation, Urban Planning, & Public Safety Industry
* **Key Stakeholders:** Traffic Safety Agencies, Ministry of Transportation, Law Enforcement (FRSC/Police), Public Health Institutions, Insurance Companies, Policy Analysts, and Commuters
* **Definition of Success:** Success is defined by establishing data-driven evidence to make roads safer through:
  * Identifying primary behavioral causes of fatal and non-fatal crashes.
  * Reducing casualties, injuries, and property damage over time.
  * Validating global trends against local state-level datasets for tailored policy interventions.
  * Optimizing emergency response and trauma care deployment.

---

##  Dataset Variables & Features

### Independent Variables
* **Geographic Attributes:** Country, State
* **Temporal Attributes:** Quarters, Year, Time of Day, Day Classification (Weekday vs. Weekend)
* **Driver & Behavioral Attributes:** Driver Age Group, Overspeeding/Speed Violations, Alcohol & Drug Influence, Reckless Driving/Negligence
* **Environmental & Road Factors:** Poor Weather, Road Surface Conditions, Other Secondary Factors

### Dependent Variables
* **Accident Scale & Outcomes:** Total Crashes / Accident Frequency, Total Vehicles Involved
* **Severity Measures:** Total Fatalities (Number Killed), Number Injured, Total Casualties (Killed + Injured)
* **Economic Measures:** Property Damage Costs ($)

---

##  Data Splitting & Preprocessing

The dataset was split into dependent outcome variables and independent predictor variables to evaluate crash severity. Extensive data cleaning and transformation was executed using **Microsoft Power BI (Power Query)**:

1. **Duplicate Removal:** Identified and dropped duplicate incident records.
2. **Missing Value Handling:** Replaced null values with aggregated estimates, standardized missing categorical entries, and dropped highly incomplete rows.
3. **Data Standardization:** Corrected inconsistent state/country naming conventions and formatted date and time fields.
4. **Transformations & Feature Engineering:**
   * Grouped accidents into **Weekday vs. Weekend** categories.
   * Segmented incidents into **Time-of-Day** buckets (Morning, Peak Rush-Hour, Evening, Night).
   * Categorized drivers into standardized **Age Groups**.
   * Calculated yearly aggregated totals for property damage trends, injuries, and fatalities.

---

##  Key Analytical Questions
1. How are road accidents distributed globally across countries and locally across Nigerian states?
2. How do accident frequency and severity differ between weekdays and weekends?
3. Which time-of-day segments and hourly periods record the highest crash volume and fatality rates?
4. What is the impact of speeding/overspeeding on crash severity and total casualties?
5. How significantly do alcohol and drug impairment contribute to road crashes across states?
6. Which driver age groups show the highest risk exposure and accident involvement?
7. What are the economic consequences of accidents as measured by yearly property damage trends?
8. Do localized road crash patterns in Nigeria validate or contradict global accident findings?

---

##  Comparative Validation: Global vs. Nigeria Dataset

To verify if global conclusions apply locally, the findings from the **Global Dataset** were validated against the **Nigeria Road Crash Dataset**:

| Metric / Behavioral Factor | Global Dataset Findings | Nigeria Validation Dataset Findings | Correlation / Validation Status |
| :--- | :--- | :--- | :--- |
| **Leading Crash Cause** | Overspeeding & Reckless Driving | Speed Violations rank as top factor | ✅ **Strongly Validated** |
| **Impaired Driving Impact** | High fatalities linked to alcohol/drugs | Significant drug/alcohol crashes across states | ✅ **Strongly Validated** |
| **Geographic Distribution** | Disproportionate concentration in certain nations | Heavy crash concentration in specific states (e.g., Ogun, Oyo, Ondo) | ✅ **Strongly Validated** |
| **Time & Fatigue Severity** | Nighttime crashes produce higher severity | Peak period & night travel show highest severe injuries | ✅ **Strongly Validated** |
| **Behavior vs. Environment** | Human error outpaces weather/mechanical issues | Human behavior accounts for the vast majority of incidents | ✅ **Strongly Validated** |

---

##  Key Dashboard Insights & Post-Analysis Observations

* **Human Behavior Dominates Causation:** Overspeeding, reckless driving, and substance impairment consistently account for the vast majority of crashes across both datasets.
* **Day vs. Night Severity Paradox:** Daytime and rush hours record higher overall crash *frequencies* due to traffic volume, but nighttime crashes produce significantly higher *fatality rates* due to reduced visibility, driver fatigue, higher speeds, and lower law enforcement presence.
* **High Economic Toll:** Line chart trends reveal a steady increase in yearly property damage costs, highlighting severe economic and productivity losses.
* **Younger Driver Vulnerability:** Demographic charts show that younger and middle-aged driver groups exhibit higher crash involvement, driven by aggressive driving habits and lower risk aversion.
* **Geographic Hotspots:** Ogun, Oyo, and Ondo states recorded the highest accident severity, casualties, and speed violations in the primary dataset.

---

##  Post-Analysis Recommendations & Actionable Steps

### 1. Strengthen Speed Limit Enforcement
* Install automated speed enforcement cameras along high-risk highways and expressways.
* Deploy patrol units with radar guns and impose stricter penalties for speed violations.

### 2. Targeted Resource Allocation for High-Risk Regions
* Prioritize traffic management resources, highway safety corps units, and patrol teams in high-density corridors (such as Ogun, Oyo, and Ondo).

### 3. Expand Emergency Trauma Response Infrastructure
* Establish highway trauma response centers and deploy strategically positioned ambulances to reduce injury mortality rates.

### 4. Impaired Driving & Fatigue Management Regulations
* Conduct routine, random breathalyzer and sobriety checkpoints, especially during weekend and late-night periods.
* Enforce mandatory rest periods for long-distance commercial vehicle drivers.

### 5. Infrastructure Upgrades & Digital Data Collection
* Upgrade road lighting, repair critical potholes, and install clear warning signage at accident blackspots.
* Transition to real-time digital accident recording tools to improve future analytical accuracy.

---

##  Tools & Technologies Used
* **Power BI Desktop:** Dashboard visualization, KPI creation, and interactive reporting
* **Power Query Editor:** Data cleaning, transformation, and feature engineering
* **DAX (Data Analysis Expressions):** Data aggregation and custom calculations
* **GitHub:** Documentation and repository hosting
