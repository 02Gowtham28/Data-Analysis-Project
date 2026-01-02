# 📊 Data Analysis of Conflict-Related Sexual Violence (2020–2024)

This project presents a comprehensive **Data Analytics and Exploratory Data Analysis (EDA)** of conflict-related sexual violence incidents reported globally between **2020 and 2024**.

The primary focus of this project is to transform **raw, unstructured, and unanalysis-ready data** into an **analysis-ready format**, followed by extracting meaningful insights through **statistical aggregation and visual analytics**.

---

## 🎯 Project Objectives

The key objectives of this analysis are to:

- Analyze **country-wise distribution** of reported victims and deaths  
- Understand trends across **victim age groups**  
- Examine the **gender-wise impact** of sexual violence  
- Study **weapon usage patterns** and their outcomes  
- Compare **reported victims, deaths, and estimated survivors**  
- Present findings through **clear, interpretable, and visually appealing charts**

---

## 🧾 Dataset Information

- **Source:** Conflict-related sexual violence incident dataset  
- **Time Period:** 2020 – 2024  
- **File Format:** CSV  
- **Data Nature:** Real-world, uncleaned, multi-valued categorical data  

> ⚠️ The raw dataset contains inconsistent column naming, missing values, multi-label categorical fields, and unstructured text, making direct analysis impractical without preprocessing.

---

## 🧹 Data Cleaning & Preprocessing

Before performing any analysis, the dataset was cleaned and standardized to ensure analytical accuracy and consistency.

### Key Cleaning Steps:
- Standardized column names to **lowercase snake_case**
- Removed extra spaces, unwanted characters, and formatting issues
- Converted text-based numeric columns into proper numeric data types
- Replaced `"None"` values with `NaN` and filled valid defaults where appropriate
- Ensured consistent categorical labels across columns

This step ensured the dataset was transformed from **unanalysis-ready** to **analysis-ready** form.

---

## 🧠 Feature Engineering & Data Transformation

Several transformations were applied to enhance analytical depth:

### 🔹 Gender Normalization
- Standardized inconsistent gender labels into:
  - `Female`
  - `Male`
  - `Unknown`
- Exploded multi-valued gender entries into individual records

### 🔹 Age Group Classification
Victims were categorized into:
- Adult  
- Minor  
- Adult & Minor  
- Unspecified  

This enables meaningful demographic comparisons.

### 🔹 Sexual Violence Type Processing
- Split and exploded records containing multiple types of sexual violence
- Standardized SV type labels for aggregation and visualization

### 🔹 Weapon Normalization
Raw weapon descriptions were normalized into analytical categories:
- Firearm
- Knife
- Blunt Object
- Chemical
- Arson
- Unarmed
- No Direct Violence
- Unknown
- Other

### 🔹 Derived Feature
**Estimated Survivors** were calculated using the formula:

> **Estimated Survivors = Reported Victims − Reported Deaths**

This derived metric enables outcome-based comparisons.

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were conducted:

### 📈 Sexual Violence Type Analysis
- Frequency and distribution of incidents by type of sexual violence
- Line and bar chart visualizations to highlight dominant SV categories

### 👥 Age Group Analysis
- Comparison of victims, deaths, and survivors across age groups
- Grouped horizontal bar charts with data labels
- Pie charts to show proportional distributions

### 🌍 Country-wise Analysis
- Interactive choropleth maps showing:
  - Country-wise reported victims
  - Country-wise reported deaths

### ⚧ Gender-based Analysis
- Gender composition of reported victims
- Gender composition of reported deaths
- Comparative pie chart visualizations

### ⚔ Weapon-wise Analysis
- Weapon-wise aggregation of victims and deaths
- Side-by-side horizontal bar charts for better comparison

---

## 📉 Visualization Techniques Used

- Horizontal & grouped bar charts  
- Dual-axis bar charts  
- Pie charts  
- Line plots  
- Log-scale bar charts  
- Interactive choropleth maps (Plotly)  

All chart types were selected based on:
- Data distribution
- Label readability
- Comparative clarity

---

## 🖼 Visualization Outputs

All outcome visualizations (charts and maps) are generated within the Jupyter Notebook.

📌 **Screenshots of key outcome plots can be found in the repository (uploaded separately)** to provide quick visual reference without executing the notebook.
<img width="1350" height="667" alt="image" src="https://github.com/user-attachments/assets/84a48a6f-c350-47e2-a51f-e2c89e97f54e" />

<img width="1248" height="707" alt="image" src="https://github.com/user-attachments/assets/4b868cfb-a41d-4ff7-9d82-c22195515b01" />
<img width="1367" height="426" alt="image" src="https://github.com/user-attachments/assets/d98a02a9-1886-4288-9182-3cf72dd4af61" />

<img width="1283" height="621" alt="image" src="https://github.com/user-attachments/assets/6282bc96-5774-4ac2-a169-b54948533c6e" />
<img width="1261" height="646" alt="image" src="https://github.com/user-attachments/assets/9a8cfceb-b81f-446a-8fb6-6eec626fc156" />

<img width="796" height="727" alt="image" src="https://github.com/user-attachments/assets/3ff6bb22-7eea-417e-8a44-8b3155b28387" />

<img width="1341" height="511" alt="image" src="https://github.com/user-attachments/assets/b04be88d-64ff-490e-a65c-531f66c04d7a" />

<img width="1372" height="664" alt="image" src="https://github.com/user-attachments/assets/72ae6e3d-5a18-4618-b47d-d1bf47d43661" />

<img width="1356" height="572" alt="image" src="https://github.com/user-attachments/assets/4a1c79f2-db80-4a30-9a3d-9af46755f857" />

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas** – Data manipulation and aggregation  
- **NumPy** – Numerical operations  
- **Matplotlib** – Static visualizations  
- **Plotly Express** – Interactive geographic maps  
- **Jupyter Notebook** – Analysis and documentation  

---

## 📌 Key Insights (High-Level)

- Certain types of sexual violence are significantly more prevalent than others
- Adults constitute the largest victim group, followed by minors
- Firearms and blunt objects are associated with higher reported deaths
- Some countries show disproportionately high victim and death counts
- Gender-based disparities exist in both victimization and mortality

*(Detailed insights are explained alongside each visualization in the notebook.)*

---

## ⚠ Limitations & Assumptions

- Some records contain missing or unspecified information
- Weapon categories were normalized using keyword-based rules
- Estimated survivors are derived values, not directly reported figures
- Underreporting may exist due to the sensitive nature of the subject

---

## 📁 Project Structure

- **data/** – Contains the raw dataset used for analysis  
- **notebooks/** – Jupyter Notebook with data cleaning, EDA, and visualizations  
- **images/** – Uploaded screenshots of important charts and maps  
- **README.md** – Project documentation and explanation

---

## 🚀 Conclusion

This project demonstrates a complete **end-to-end Data Analytics workflow**, covering:

- Data cleaning and preprocessing  
- Feature engineering  
- Exploratory data analysis  
- Visualization and storytelling  
- Insight generation  

It reflects **real-world data challenges** and showcases analytical thinking, making it well-suited for **Data Analyst and Analytics-focused roles**.

---

## 👤 Author

**Gowtham R**  
Bachelor of Engineering – Computer Science & Engineering (Data Science)  
Aspiring Data Analyst | Data Visualization | Python | SQL  

---

⭐ *If you find this project useful, feel free to star the repository!* ⭐


