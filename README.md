#  Global Antibiotic Resistance Analysis
### *(WHO GLASS Data | 2017–2020)*

This project presents an **exploratory data analysis (EDA)** of global antibiotic resistance using **real-world WHO GLASS data**, performed entirely in **Microsoft Excel**. The analysis focuses on identifying **time-based, regional, and bacteria-specific resistance patterns** and demonstrates practical data analysis and visualization skills.

---

##  Project Objectives

- Analyze global antibiotic resistance trends over time  
- Compare resistance patterns across WHO regions  
- Identify high-risk and low-risk antibiotics  
- Examine bacteria–antibiotic resistance relationships  
- Demonstrate Excel-based data cleaning, validation, and analysis skills  

---

##  Repository Structure

global-antibiotic-resistance-analysis/
│
├── README.md
├── LICENSE
│
├── data/
│ └── WHO_GLASS_Antibiotic_Resistance.xlsx
│
├── reports/
│ └── Global_Antibiotic_Resistance_Analysis.pdf
│
├── visuals/
│ └── charts_and_heatmaps.png

---

##  Data Source

- **Organization:** World Health Organization (WHO)  
- **System:** GLASS (Global Antimicrobial Resistance and Use Surveillance System)  
- **Time Period:** 2017–2020  

The data used in this project was sourced from the WHO GLASS program and processed into an Excel format for analysis.  
The Excel file in this repository contains the cleaned, validated, and analysis-ready version of the data.

🔗 Official reference: https://www.who.int/initiatives/glass

---

##  Data Preparation & Validation

The dataset was cleaned and validated prior to analysis:

- Renamed columns to industry-standard, meaningful names  
- Verified data types across all fields  
- Removed blank and invalid records  
- Ensured logical consistency (`Resistant_Count ≤ Total_Tested`)  
- Validated resistance percentages to remain within 0–100%  
- Applied Excel-based logical checks to flag inconsistent data  

---

##  Analysis & Visualizations

The following analyses were performed using **Pivot Tables and Excel Charts**:

- Year-wise trend analysis of average antibiotic resistance  
- WHO region–wise comparison of resistance patterns  
- Line charts to visualize resistance trends over time  
- Bacteria vs antibiotic heatmap using conditional formatting  
- Top 5 most resistant antibiotics (high-risk)  
- Top 5 least resistant antibiotics (low-risk / effective)  

---

##  Key Insights

- Older and commonly prescribed antibiotics show significantly higher resistance  
- Restricted and last-resort antibiotics maintain lower resistance levels  
- Resistance varies widely across bacteria–antibiotic combinations  
- No single antibiotic is universally effective  
- Observed patterns align with global antimicrobial resistance findings  

---

##  Key Takeaway

Antibiotic resistance is driven by usage patterns rather than random occurrence.  
The analysis highlights the importance of **antibiotic stewardship** and **bacteria-specific treatment selection** to preserve antibiotic effectiveness and support safer long-term healthcare outcomes.

---

##  Tools Used

- Microsoft Excel  
- Pivot Tables  
- Conditional Formatting (Heatmaps)  
- Line Charts & Column Charts  

---

##  Project Files

- 📊 **Excel Analysis File:**  
  [`data/Final_Report_WHO_GLASS_Antibiotic_Resistance.xlsx`](data/Final_Report_WHO_GLASS_Antibiotic_Resistance.xlsx)

- 📑 **Project Report (PDF):**  
  [`reports/Global_Antibiotic_Resistance_Analysis.pdf`](reports/Global_Antibiotic_Resistance_Analysis.pdf)

---

## 👤 Author

**Umesh Zampadiya**  
Data Analyst | Excel | Data Visualization  

---

## 📜 License

This project is licensed under the **MIT License**.  
See the [`LICENSE`](LICENSE) file for details.

---

⭐ *This project demonstrates the ability to convert real-world healthcare data into meaningful insights using Excel-based analytical techniques.*
