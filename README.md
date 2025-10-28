# 📡 Telecommunications Infrastructure & Broadband Equity Analysis — Connecticut  
### Power BI · SQL · DAX · Data Cleaning (M Code) · Infrastructure Analytics

**Key Techniques:** Data Cleaning (Power Query M), DAX KPI Modeling, Fuzzy Matching, Geospatial Insights, Correlation Analysis, Data Storytelling, Dashboard Design  
**Industry:** Telecommunications | Broadband & Infrastructure Planning  
**Tools:** Power BI | Excel | SQL | Power Query | DAX | Python (Exploratory Stats)

<!-- Banner -->
<p align="center">
  <img src="Images/Banner for telecoms.jpg" alt="Connecticut Telecom Infrastructure Analysis Banner" width="100%">
</p>
---

## 🧭 Executive Summary  

As broadband access becomes a key driver of economic inclusion, Connecticut faces growing disparities in **telecommunication tower distribution** and **broadband speed access**.  
This project investigates **telecom infrastructure equity**, combining **tower deployment data**, **population demographics**, and **broadband speeds** to answer a simple but powerful question:  

> 🧩 *Are Connecticut’s telecom resources evenly distributed across towns, or are some communities underserved?*

Through rigorous data cleaning, transformation, and advanced DAX modeling, the analysis uncovers patterns of **infrastructure gaps**, **service inequality**, and **efficiency bottlenecks**.  
The final Power BI dashboard provides actionable insights for policymakers, telecom planners, and broadband strategists.

---

## 💼 Business Problem  

Despite Connecticut’s reputation for strong connectivity, **over 17% of towns report underserved or unserved broadband populations**, and **tower coverage** is highly uneven.  
Some towns, like **Greenwich and Stamford**, have over 150 towers and 5G access, while rural areas such as **Sherman and Winsted** struggle with just one provider and minimal coverage.

**Business Question:**  
How can infrastructure investment be optimized to ensure equitable telecom access and faster broadband speeds across Connecticut towns?

**Key Goals:**  
- Identify **underserved towns** based on population-to-tower ratios.  
- Evaluate the **relationship between broadband speed and provider density.**  
- Highlight **infrastructure inefficiencies** and recommend priority investment areas.  

---

## 🔬 Methodology  

| Step | Description | Key Skills / Tools |
|------|--------------|--------------------|
| **Data Cleaning & Standardization** | Merged tower registry, broadband provider, and population datasets. Cleaned over 500 inconsistent entries using Power Query M (fuzzy matching, regex-like cleaning, custom lists). | **Power Query (M Code)** |
| **Feature Engineering** | Computed ratios like *Population per Tower*, *Speed per Provider*, *Tower Gap Index*. | **Calculated Columns, DAX Measures** |
| **Statistical & Correlation Analysis** | Measured correlation between tower density and broadband speed. | **DAX, Correlation Analysis** |
| **Visualization & Storytelling** | Designed a three-page Power BI dashboard — Infrastructure, Population, and Broadband — with dynamic filters. | **Power BI, Data Storytelling** |

---

## 🧠 Skills Demonstrated  

- **Power Query (M Code):** Complex column standardization, fuzzy matching, multi-condition replacements, data cleansing at scale.  
- **DAX (Data Analysis Expressions):**  
  - Statistical modeling: `STDEVX.P`, `CALCULATE`, `TOPN`, `FILTER`, `VAR`.  
  - Business KPIs: Speed Equity Index, Tower Gap Index, Provider Density.  
- **SQL Concepts:** Data transformation logic (joins, grouping, CTE-like logic in Power Query).  
- **Data Visualization:** KPI storytelling, population vs. infrastructure mapping, correlation matrix, ratio-driven performance visuals.  
- **Geospatial Thinking:** Interpreted tower and broadband coverage distribution without relying on choropleth maps.  

---

## 📈 Results & Business Impact  

| KPI | Insight | Business Implication |
|-----|----------|----------------------|
| **Tower Gap Index** | The *state average ratio* is **1 tower per 3,756 people**, while the *best-served town* (Sherman) maintains **1 per 17 residents**. | Over **212,000 residents** remain under-covered — identifying a clear investment opportunity. |
| **Speed Equity Index** | The bottom 25% of towns experience **speeds 60% slower** than the top quartile. | Highlights digital divide — opportunity for broadband subsidy and tower colocation incentives. |
| **Provider Density vs Speed** | Moderate positive correlation (**r ≈ 0.64**) — towns with more providers show higher download speeds. | Encourages **competition-driven infrastructure expansion**. |
| **Underserved Towns** | Towns like **Sherman, Winsted, and Essex** have both high populations and only one provider. | Prioritize these for 5G and tower expansion. |
| **Backup Power & Resilience** | Only **56% of towers** have backup power and **50% are 5G-ready**. | Investment in **network resilience** needed for outage preparedness. |

---

## 🧩 Dashboard Overview  

### **1. Infrastructure Page**
- Tower count distribution and ownership (AT&T, Crown Castle, T-Mobile, Verizon).
- Tower height analysis (Monopole, Lattice, Rooftop types).
- Backup power and 5G compatibility insights.

### **2. Population Page**
- Population vs tower density per town.
- Tower Gap Index & underserved town ranking.
- Regional prioritization metrics (towns with high load per tower).

### **3. Broadband Page**
- Average download speeds by town.
- Provider overlap and coverage redundancy (18% shared providers).
- Unserved/underserved household estimation vs FCC standards.

---

## 📊 Dashboard Preview  

<p align="center">
  <img src="Images/Telecommunications in Conneticut.png" alt="Connecticut Telecommunications Dashboard Preview" width="85%">
</p>

<p align="center">
  <a href="Connecticut PowerBi.pdf">
    <img src="https://img.shields.io/badge/View%20Dashboard%20Report%20(PDF)-blue?style=for-the-badge&logo=adobeacrobatreader" alt="View Dashboard PDF">
  </a>
  &nbsp;
  <a href="Connecticut PowerBi.pbix">
    <img src="https://img.shields.io/badge/Download%20PowerBI%20File%20(PBIX)-gold?style=for-the-badge&logo=powerbi" alt="Download PBIX File">
  </a>
</p>

---

## 🚀 Recommendations  

- **1️⃣ Infrastructure Expansion:**  
  Prioritize **Sherman, Winsted, and Essex** for new tower installations.  

- **2️⃣ Encourage Multi-Provider Competition:**  
  Provider overlap correlates with faster speeds; diversify service options in low-density towns.  

- **3️⃣ Power & 5G Upgrade:**  
  Upgrade older lattice towers with modern monopoles and integrate backup systems to improve resilience.  

- **4️⃣ Broadband Equity Policy:**  
  Target investment where **population-to-tower ratio exceeds 3,000 residents per tower.**

---

## 🔭 Next Steps  
 
- Add **forecasting models** to predict tower capacity based on urbanization trends.  
- Expand to **regional comparative studies** (e.g., Massachusetts, Rhode Island).  
  

---

### ⚠️ Disclaimer
This project was conducted using a **sample dataset** that does **not represent the full official list of telecommunications towers in Connecticut** as maintained by the Connecticut Siting Council.  
All analyses, insights, and KPIs were developed based on this limited dataset for **educational and portfolio demonstration purposes**.  
While the findings highlight meaningful patterns and analytical techniques, they should not be interpreted as a definitive reflection of the state’s telecommunications infrastructure.

---

