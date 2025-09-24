# 🩺 Chronic Conditions in Canada: An Exploratory Data Analysis

This project performs an in-depth exploratory data analysis (EDA) of the Canadian Community Health Survey (CCHS) dataset. The goal is to uncover key patterns and insights into the prevalence of major chronic health conditions across Canada, with a special focus on Ontario.

---

## 🎯 Project Objectives

* To analyze and visualize the prevalence of various chronic conditions (physical and mental) at a national level.
* To identify key demographic drivers such as **age, sex, and income**.
* To conduct a comparative analysis of **Ontario's** health profile against the national average.
* To synthesize findings into actionable public health insights.

---

## 📈 Key Findings

### **National-Level Insights**
* **Dual Health Challenge:** Canada faces a dual burden of chronic disease: age-related physical conditions (like hypertension and diabetes) are most prevalent in older populations, while mental health disorders (anxiety, mood disorders) are most common among younger Canadians.
* **Socioeconomic Impact:** There is a strong and consistent correlation between lower income and a higher prevalence of nearly every chronic condition.
* **Gender Disparities:** Women report higher rates of anxiety, mood disorders, and musculoskeletal conditions, while men report higher rates of cardiovascular conditions and diabetes.

### **Ontario vs. National Comparison**
* **Physical Health:** Ontario's prevalence rates for most major physical conditions are **at or slightly below** the Canadian average.
* **Mental Health:** Ontario shows a **notably higher** prevalence of Anxiety and Mood Disorders compared to the rest of the country, highlighting a key provincial health challenge.

---

## 🛠️ Tools and Libraries

* **Python:** The core programming language used for the analysis.
* **Pandas:** For data manipulation and cleaning.
* **Matplotlib & Seaborn:** For data visualization.
* **Jupyter Notebook:** As the interactive development environment.

---

## 🗂️ Repository Structure

```
CCHS-Chronic-Conditions-Analysis/
│
├── Chronic_Conditions_Prevalence_EDA.ipynb   # Main Jupyter Notebook with all analysis
├── README.md                                 # You are here!
├── requirements.txt                          # Required Python libraries
├── .gitignore                                # Files for Git to ignore
│
└── plots/                                    # Visual outputs
    ├── National_Level/
    ├── Ontario_Level/
    └── Ontario_vs_National/
```

---

## 📊 Dataset

The dataset used in this project is the **Canadian Community Health Survey (CCHS) 2019-20 microdata**, downloaded from [Statistics Canada](https://www.statcan.gc.ca/).  
Due to licensing restrictions, the raw dataset is **not included** in this repository. Users are encouraged to obtain the dataset directly from Statistics Canada.

---

## 🚀 How to Run

1. Clone this repository to your local machine.
2. Install the necessary packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook and open the `Chronic_Conditions_Prevalence_EDA.ipynb` file:
   ```bash
   jupyter notebook
   ```

---

## 👤 Author

**Arun Acharya**
