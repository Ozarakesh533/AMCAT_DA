# 📊 AMCAT Data Analysis

This repository contains an exploratory data analysis (EDA) and statistical insights on the **AMCAT dataset**, which provides information on graduates’ academic records, job roles, salaries, and assessments.

---

## 📂 Project Structure
- **`AMCAT_Data_Analysis.ipynb`** → Jupyter Notebook containing the complete data analysis, cleaning, visualization, and statistical tests.  
- **`AMCAT_Report_Rakesh.pdf`** → Final summarized project report with findings and conclusions.  
- **`data.xlsx - Sheet1.csv`** → Dataset used for the analysis (not included here due to size/sensitivity).  

---

## 🔧 Technologies & Libraries Used
- **Python** (Pandas, NumPy, SciPy) → Data wrangling, statistical analysis  
- **Matplotlib, Seaborn, Plotly** → Data visualization (static + interactive)  
- **Jupyter Notebook** → Interactive coding & documentation  

---

## 📝 Steps in Analysis
1. **Data Import & Cleaning**  
   - Removed unnecessary columns (`Unnamed:0`).  
   - Standardized categorical values (e.g., job cities: Bangalore, Hyderabad, Pune).  
   - Handled missing and incorrect entries.  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots of numerical columns (Salary, GPA, 10th/12th scores).  
   - Count plots for categorical columns (JobCity, Degree, CollegeTier).  
   - Pair plots for relationships between numerical features.  

3. **Feature Insights**  
   - Salary distribution across **Degrees, College Tiers, Job Roles**.  
   - Gender distribution across **Specializations**.  
   - Statistical tests (Chi-Square) for association between categorical variables.  

4. **Key Findings**  
   - **Salary Trends**: Average salary for freshers matched industry claims.  
   - **Specialization Impact**: CS/IT graduates commanded higher salaries.  
   - **College Tier**: Tier-1 colleges linked to higher packages.  
   - **Gender Bias**: Uneven representation in technical roles.  
   - **Skill Relevance**: Higher programming/quantitative scores correlated with salary.  

---

## 📑 Report
The detailed findings and statistical conclusions are documented in the **[Report PDF](./AMCAT_Report_Rakesh.pdf)**.  

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/Ozarakesh533/AMCAT_DA.git
   cd AMCAT_DA
2. Install dependencies
   ```bash
   pip install -r requirements.txt

4. Open the Jupyter Notebook
    ```bash
   jupyter notebook AMCAT_Data_Analysis.ipynb

📦 Requirements (requirements.txt)
```bash
pandas
numpy
matplotlib
seaborn
plotly
scipy
jupyter
```
## 👨‍💻 Developer

**Rakesh Oza**  
*AI & Machine Learning Engineer*
- 📧 **Contact**: ozarakesh533@gmail.com
- 💼 **LinkedIn**:[Linkedin](https://www.linkedin.com/in/rakeshoza/)
- 🐙 **GitHub**: [Github](https://github.com/Ozarakesh533)
