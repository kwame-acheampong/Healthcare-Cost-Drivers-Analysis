# Healthcare-Cost-Drivers-Analysis

## Brief Description
A data analysis project investigating the primary drivers of healthcare billing amounts and the influence of patient demographics, medical conditions, and admission types on clinical test results.

##  Project Overview
This project analyzes a dataset of 30,000 hospital records to identify the key factors driving healthcare costs and influencing patient test results. With rising treatment expenses and inconsistent clinical outcomes, this study aims to provide actionable insights into how medical conditions, hospital choices, and admission types affect billing amounts and patient health.

##  Problem Statement
Healthcare facilities face rising treatment costs and inconsistent patient outcomes across various medical conditions and care settings. However, the specific cost drivers within treatment pathways and their direct impact on clinical outcomes remain unclear. This project performs an analysis of treatment decisions, resource use, and care settings to understand their influence on healthcare spending.

##  Objectives
1.  **Analyze Patient Billing:** Investigate the distribution of billing amounts across different medical conditions and hospitals.
2.  **Identify Cost Drivers:** Determine which factors (e.g., diagnosis, hospital, admission type) contribute most to high expenses.
3.  **Assess Outcomes:** Explore the relationship between patient variables (age, medication, stay duration) and test result categories.
4.  **Recommend Solutions:** Propose measures to reduce costs and improve care efficiency.

##  Dataset Description
The dataset contains **30,000 patient records** spanning from **Jan 2022 to Nov 2024**.

| Column Name | Description |
| :--- | :--- |
| `Patient_ID` | Unique identifier for each patient |
| `Name` | Patient's name |
| `Age` | Patient's age at time of admission |
| `Medical_Condition` | Primary diagnosis (e.g., Sepsis, Diabetes, Hypertension) |
| `Date_of_Admission` | Date and time of hospital admission |
| `Discharge_Date` | Date and time of discharge |
| `Length_of_Stay` | Duration of hospitalization in days |
| `Doctor` | Attending physician |
| `Hospital` | Name of the medical facility (e.g., City General, Regional Medical) |
| `Insurance` | Insurance provider or "No Insurance" |
| `Admission_Type` | Type of admission (Emergency, Urgent, Elective) |
| `Medication` | Primary medication prescribed |
| `Test_Result_Category` | Outcome classification (Normal, Abnormal, Critical) |
| `Test_Result_Description` | Detailed description of the test result |
| `Billing_Amount` | Total cost of treatment |
| `Patient_Responsibility` | Portion of the bill paid by the patient |

##  Key Findings
* **Most Expensive Condition:** **Sepsis** is the costliest condition to treat, with an average billing amount of approximately **$358,000**.
* **High-Cost Drivers:** Myocardial Infarction and Stroke follow Sepsis as the next most expensive conditions (~$189k and ~$152k respectively).
* **Facility Variance:** **City General** is the most expensive facility, charging nearly **69% more** for Sepsis cases compared to Regional Medical.
* **Admission Patterns:** About **50%** of high-volume cases are treated via **Emergency** admissions, suggesting gaps in primary care management.
* **Insurance Impact:** Patients without insurance coverage are paying the full cost of these  treatments out-of-pocket.

## Report
* **PowerPoint summary**: `report/health_cost_driver_analysis.pptx`
* **Jupyter notebook**: `notebook/Health_cost_drivers.ipynb`


##  Recommendations
* **Preventive Care Focus:** Targeted public health campaigns for middle-aged and elderly demographics to prevent high-cost chronic conditions.
* **Primary Care Management:** Improving access to primary care could reduce the high volume of preventable emergency admissions.
* **Standardization:** Investigate price variances between hospitals (e.g., City General vs. Regional Medical) to standardize costs for standard treatments.
* **Insurance Education:** Comprehensive guides for uninsured patients to navigate healthcare financing and coverage options.

##  Tools 
* **Python:** Primary programming language.
* **Pandas:** For data manipulation and aggregation.
* **Matplotlib / Seaborn:** For  data visualization.
* **Plotly:** For interactive charts and graphs.

##  Getting Started
1.  **Clone the repo:**
    ```bash
    git clone https://github.com/kwame-acheampong/Healthcare-Cost-Drivers-Analysis.git
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn plotly
    ```
3.  **Run the analysis:**
    Open `health_cost_driver_analysis.ipynb` in Jupyter Notebook or Google Colab to view the code and visualizations
