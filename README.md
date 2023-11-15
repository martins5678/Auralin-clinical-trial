[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://bankoleridwan.github.io/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bankoleridwan/)

> *(Disclaimer: The clinical dataset is fabricated for the sake of data wrangling practice on Udacity. It is constructed to simulate real-world dataset with the consults of real doctors. The 'auralin' and 'novodra' are NOT real insulin products, however, it mimics the real clinical trial for an inhaled insulin, Afrezza.)*

## Introduction
[![Banner](https://raw.githubusercontent.com/bankoleridwan/Auralin-clinical-trial/main/Auralin/Insulin.jpg)](https://images.unsplash.com/photo-1593491205049-7f032d28cf5c?auto=format&fit=crop&q=80&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&w=1470)


The increasing prevalence of diabetes in the 21st century is alarming. Diabetes, a persistently elevated blood sugar level due to the inability to produce sufficient Insulin or the inability of the body to use its own Insulin, can lead to more serious complications like stroke, blindness, kidney failure, and heart attacks if not properly managed. 

Although diabetes is not curable, the discovery of Insulin by Frederick Banting in the 1920s was like a miracle for diabetes management, and people with severe diabetes with only a few days left were saved. 

Despite being a beacon of hope, Insulin faced challenges. Insulin can only be administered by a needle multiple times daily because of its high molecular weight, susceptibility to enzymatic degradation, and low diffusion rate across the stomach wall. Although there have been some recent innovations in the insulin method of administration, including insulin pumps, won’t there be better compliance if there is an oral insulin tablet? In this phase II clinical trial, we compare the effectiveness of Auralin, an oral Insulin, using Novodra, a popular injectable insulin, as a standard. 




## Problem Statement/ Hypothesis 

> Auralin, an oral insulin, will demonstrate comparable efficacy in glycemic control to Novodra, the injectable Insulin while offering greater patient compliance and convenience due to its oral form. The study aims to determine whether Auralin’s oral delivery method can achieve similar or superior results in managing blood glucose levels compared to Novodra


## Outcome
By harnessing statistical techniques and Python programming, I have been able to unearth latent patterns within the dataset. Armed with this valuable information, I am poised to make data-driven decisions that will facilitate informed assessments of the safety and efficacy of auralin.

## Skills and Tools Used
* Programming Language: Python
* Project Management: Trello Board
* Statistical modeling
* Data Manipulation
* Data Visualization
* Data Cleaning
* Communication
* Report writing


## Task Overview
Here is a concise high-level review of the critical tasks to achieve the project goal.

* Loaded and reconciled the dataset into a single table.
* In-depth exploration, manipulation, and handling of data quality and structural issues such as missing values, duplicated entries, wrong formatting, etc.


#### Duplicated Entries

> A comprehensive examination for duplicate entries shows John Doe is a single patient with six different patient ID. 

![Duplicated entries](https://raw.githubusercontent.com/bankoleridwan/Auralin-clinical-trial/main/Auralin/duplicated%20enteries.PNG)



#### Structural Anomaly

> Three distinct features: 'treatment', 'start_dose' and 'end_dose' are reported as two features: 'auralin' and 'novodra'.

![structure Anomaly](https://raw.githubusercontent.com/bankoleridwan/Auralin-clinical-trial/main/Auralin/structural%20anomaly.PNG)


### Cleaned Dataset
Following the comprehensive cleaning process aimed at addressing the identified dataset issues, here are the resultant outcomes.

![Cleaned Dataset](https://raw.githubusercontent.com/bankoleridwan/Auralin-clinical-trial/main/Auralin/cleaned%20dataset.PNG)


* Visualized relationship between features of interest for insightful pattern and enhanced the pattern by engineering new features.
* Performed statistical analysis to test the hypothesis. 






## Insights / Outcomes

Below are some of the remarkable insights gleaned from the analysis.

#### Do patients on Auralin have higher glycemic control than those on Novodra?


> A statistically significant difference (t = 3.08, p = 0.002, $\alpha$ = 0.05) in HbA1c changes between Novodra and Auralin treatments. Therefore, we reject the null hypothesis, concluding that Novodra leads to a significantly greater HbA1c change than Auralin.

![Hba1c Change](https://raw.githubusercontent.com/bankoleridwan/Auralin-clinical-trial/main/Auralin/hba1c%20change.png)

#### Are adverse effects observed depending on the dose of aural or no vodka?

> Many of the side effects are a result of the model of administration: throat irritation and nausea for Auralin and injection site discomfort for Novodra. However, the common side effects of headache and hypoglycemia are reported in more patients taking Auralin compared to Novodra.

![Side Effect](https://raw.githubusercontent.com/bankoleridwan/Auralin-clinical-trial/main/Auralin/side%20effects.png)


#### Does an increased dose of auralin or Novodra translate to increased HbA1c Reduction?

> There is an inverse relationship between the dosage of auralin (Corr. Coef. = -0.0730) and its corresponding impact on the HbA1c levels, whereas Novodra (Corr. Coef. = 0.0898) demonstrates a direct proportional relationship with the response. Using the minimum effective dose of auralin can mitigate the side effects.

![Dose Correlation](https://raw.githubusercontent.com/bankoleridwan/Auralin-clinical-trial/main/Auralin/dose%20correlation.png)                    


Ready to unlock the full potential of your data? I'm excited to collaborate and help your business thrive through data-driven insights. [Get in touch!](https://bankoleridwan.github.io/#contact:~:text=My%20Resume-,Contact%20Me,-Ready%20to%20unlock)
