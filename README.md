# Diabetes Analysis: A Healthcare Data Analytics Project

**Tools:** Microsoft Excel | Tableau  
**Project Type:** Healthcare Data Analysis | Exploratory Data Analysis (EDA) | Data Visualisation  
**Domain:** Public Health / Healthcare Analytics

## 1. Project Overview

Diabetes is a major non-communicable disease and an important public health concern. Understanding the clinical characteristics and patterns associated with diabetes can support better health monitoring, awareness, and evidence-based healthcare decisions.

This project involved analysing a diabetes dataset to explore the distribution of diabetes cases and examine differences in selected clinical indicators between patients classified as diabetic and non-diabetic.

I used **Microsoft Excel** for data preparation, cleaning, and preliminary analysis, followed by **Tableau** for data visualisation and dashboard development.

The project demonstrates my ability to transform raw healthcare data into meaningful insights through data cleaning, exploratory analysis, KPI development, and visual storytelling.

## 2. Project Objectives

The main objectives were to:

- Determine the number of patients classified as diabetic and non-diabetic.
- Calculate the proportion of patients classified as diabetic.
- Compare selected clinical indicators between both groups.
- Explore the distribution of diabetes cases across different age groups.
- Examine the relationship between glucose levels and BMI.
- Present the findings through an interactive and informative healthcare dashboard.

## 3. Dataset Description

The dataset contains anonymised patient records and clinical measurements relating to diabetes.

It contains the following variables:

| Variable | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Skin fold thickness |
| Insulin | Serum insulin level |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Patient age |
| Outcome | Diabetes classification (1 = Diabetes, 0 = No Diabetes) |

**Dataset size:**
- Initial records: 800
- Records retained after cleaning: 768
- Variables: 9

*Note: The dataset was described as containing anonymised records associated with University of Ilorin Teaching Hospital and General Hospital Offa. Its original provenance should be independently verified before presenting it as an official hospital dataset.*

## 4. Data Preparation and Cleaning – Microsoft Excel

I used Microsoft Excel to prepare the dataset for analysis.

The following steps were performed:

**Step 1: Importing and organising the dataset**
- Opened the dataset in Microsoft Excel.
- Saved the working copy as an Excel workbook.
- Renamed the workbook appropriately.
- Converted the dataset into an Excel Table to make data management and referencing easier.

**Step 2: Data inspection**
- Reviewed the dataset structure and column headings.
- Examined the variables and their data types.
- Checked for missing values and inconsistencies.

**Step 3: Duplicate checks**
- Checked the dataset for duplicate records.
- Reviewed the records to ensure that duplicate entries would not distort the analysis.

**Step 4: Handling invalid and zero values**
- Identified zero values in clinical measurement columns where zero was not a physiologically meaningful measurement.
- Reviewed affected variables, including blood pressure and other clinical measurements.
- Prepared cleaned versions of relevant variables for analysis rather than treating invalid readings as genuine clinical measurements.

**Step 5: Data transformation**
- Created a categorical diabetes status variable using the original Outcome field.
- Classified Outcome = 1 as "Diabetes".
- Classified Outcome = 0 as "No Diabetes".
- Retained the original Outcome variable for numerical analysis.

**Step 6: Final data preparation**
- Reviewed the cleaned dataset.
- Retained 768 records for the subsequent analysis.
- Saved the cleaned dataset for import into Tableau.

## 5. Exploratory Data Analysis – Key Questions

The analysis was guided by five major questions.

### Question 1: How many patients in the dataset have diabetes?

I examined the Outcome variable to determine the number of patients classified as diabetic and non-diabetic.

**Finding:**
- Diabetes cases: 268
- Non-diabetes cases: 500
- Total patients: 768

This showed that the dataset contained more non-diabetic than diabetic records.

### Question 2: What proportion of the patients are classified as diabetic?

The percentage of diabetes cases was calculated using:

`(Diabetes Cases / Total Patients) × 100`

Calculation:

`(268 / 768) × 100 = 34.90%`

**Finding:** Approximately 34.90% of the records were classified as diabetic, while 65.10% were classified as non-diabetic.

This represents the proportion within the analysed dataset, not the prevalence of diabetes in the general population.

### Question 3: How do glucose levels differ between diabetic and non-diabetic patients?

I compared the average glucose levels across both groups.

**Finding:**
- Diabetes: 141
- No Diabetes: 110

The diabetic group had a higher average glucose level than the non-diabetic group.

This highlights glucose as an important clinical indicator to examine when assessing diabetes-related patterns.

### Question 4: How do other clinical indicators differ between the two groups?

I compared average insulin, BMI, and diastolic blood pressure between patients classified as diabetic and non-diabetic.

**Findings:**

| Clinical indicator | Diabetes | No Diabetes |
|---|---:|---:|
| Average insulin | 206.85 | 130.29 |
| Average BMI | 35.407 | 30.860 |
| Average diastolic blood pressure | 75 | 71 |

The diabetic group had higher average values across all three indicators.

The difference in average insulin was particularly noticeable and became one of the key observations from the analysis.

### Question 5: How are diabetes classifications distributed across age groups, and what relationship exists between glucose and BMI?

I grouped patients into age categories and compared the distribution of diabetes classifications across those categories.

I also explored glucose levels against BMI to examine their relationship.

The age-group visualisation showed how patient records were distributed across the different age categories.

The glucose and BMI analysis was intended to explore whether higher glucose measurements occurred alongside higher BMI values.

These patterns can provide useful exploratory insights, although they do not independently establish causation or predict an individual's diabetes status.

## 6. Key Performance Indicators (KPIs)

I developed four KPI cards in Tableau to provide a quick overview of the dataset.

| KPI | Result | Explanation |
|---|---:|---|
| Total Patients | 768 | Total number of patient records analysed |
| Diabetes Cases | 268 | Number of records classified as diabetic |
| Non-Diabetes Cases | 500 | Number of records classified as non-diabetic |
| Diabetes Percentage | 34.90% | Percentage of analysed records classified as diabetic |

These indicators provide an immediate summary of the diabetes classification distribution and serve as the starting point for further investigation.

## 7. Tableau Visualisation and Dashboard Development

After completing the data preparation and preliminary analysis in Excel, I imported the cleaned dataset into Tableau.

I developed a dashboard titled **Diabetes Analysis Dashboard**, incorporating KPI cards and multiple visualisations to communicate the findings.

The dashboard includes:

1. **Diabetes Distribution:** A chart comparing the number of diabetic and non-diabetic records.

2. **Average Glucose by Diabetes Status:** A comparison of average glucose levels between both groups.

3. **Average Insulin by Diabetes Status:** A comparison of average serum insulin levels, highlighting the difference between the two classifications.

4. **Average BMI by Diabetes Status:** A visual comparison of average BMI between diabetic and non-diabetic patients.

5. **Average Diastolic Blood Pressure by Diabetes Status:** A comparison of average diastolic blood pressure across the two groups.

6. **Age Group by Diabetes Status:** A chart showing the distribution of diabetes classifications across different age categories.

7. **Glucose Level by BMI Relationship:** A scatter plot intended to explore the relationship between glucose measurements and BMI.

The dashboard combines these visualisations to make the findings easier to interpret and compare.

## 8. Key Findings and Interpretation

The analysis revealed several notable patterns:

**1. Distribution of diabetes cases**

Of the 768 records analysed, 268 were classified as diabetic, representing 34.90% of the dataset. The remaining 500 records were classified as non-diabetic.

**2. Higher average glucose levels**

Patients classified as diabetic had a higher average glucose level (141) compared with the non-diabetic group (110).

**3. Higher average insulin levels**

The diabetic group had an average insulin level of 206.85, compared with 130.29 among the non-diabetic group.

This was one of the most interesting findings in the analysis.

Elevated insulin can occur in people with Type 2 diabetes because insulin resistance may cause the pancreas to produce more insulin in an attempt to maintain normal blood glucose levels.

However, this observation alone does not establish that the diabetic patients in this dataset have Type 2 diabetes. The dataset does not provide a confirmed diabetes subtype, and insulin measurements must be interpreted alongside other clinical information.

**4. Higher average BMI**

The average BMI was 35.407 among diabetic patients and 30.860 among non-diabetic patients.

This suggests that the diabetic group had a higher average BMI in the analysed records.

**5. Differences in blood pressure**

The diabetic group had an average diastolic blood pressure of 75, compared with 71 in the non-diabetic group.

Although the difference was relatively small, it provides another clinical parameter worth exploring.

## 9. Limitations of the Analysis

There are important limitations to consider:

- The analysis is based on 768 records and should not be generalised to the wider population without an appropriate sampling design.
- The dataset does not identify diabetes subtypes, so Type 1 and Type 2 diabetes cannot be distinguished.
- Missing or invalid clinical measurements may affect calculated averages.
- Differences between group averages do not establish causation.
- The scatter plot should be interpreted at the individual-record level to assess the relationship between glucose and BMI accurately.

These limitations are important when interpreting healthcare data and communicating findings responsibly.

## 10. Skills Demonstrated

Through this project, I demonstrated practical skills in:

- Microsoft Excel data management.
- Data cleaning and preprocessing.
- Duplicate and missing-value checks.
- Data transformation and categorisation.
- Exploratory Data Analysis (EDA).
- KPI development and calculation.
- Tableau data visualisation.
- Healthcare data interpretation.
- Dashboard design and data storytelling.
- Communicating data-driven findings.

## 11. Conclusion

This project provided an opportunity to apply data analytics techniques to a healthcare-related dataset and explore patterns in diabetes classification and associated clinical indicators.

By combining Excel for data preparation and Tableau for visualisation, I transformed raw patient records into a structured analytical dashboard.

One of the most notable observations was the difference in average insulin levels between the diabetic and non-diabetic groups, alongside differences in glucose levels and BMI.

Beyond the technical process, this project strengthened my interest in healthcare analytics and demonstrated how data analysis can contribute to understanding health-related patterns and supporting evidence-informed public health decisions.

## 12. Project Files

The repository contains:

- `diabetes_dataset.xlsx` – Excel workbook containing the prepared dataset and analysis.
- `Diabetes_Analysis_Dashboard.twbx` – Tableau packaged workbook (if included).
- `dashboard.png` – Screenshot of the completed dashboard.

## Author

**Ahmed Halima**

Human Physiology Graduate | Aspiring Healthcare Data Analyst

Interested in applying data analytics to healthcare research, public health, and evidence-based decision-making.
