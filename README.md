# Insurance-Data-Analysis-in-Python

## Table of Contents
- [Project Overview](#project-overview)
- [Project Description](#project-description)
- [Objective](#objective)
- [Domain](#domain)
- [Dataset Source](#dataset-source)
- [Dataset Description](#dataset-description)
- [Tasks Performed](#tasks-performed)
- [Findings](#findings)
  
### Project Overview
An insurance agency, ABC Insurance, has a large dataset containing information about their policyholders and claims. They want to perform exploratory data analysis (EDA) on this dataset to gain insights that can help them make better business decisions and improve their operations.

![Screenshot_24-3-2025_164153_lms simplilearn com](https://github.com/user-attachments/assets/5719ad09-2ce9-4bbc-bede-059ff234bff4)

### Project Description
The agency wants to analyze the different body types and the environment that affect the premium. The disease's effect or the cost of treatment differs depending on the circumstances. For example, a smoker's medical insurance premium may be higher than that of a healthy person, because smokers are more likely to develop chronic diseases. The agency wants to analyze the data to research healthcare premium costs. 

### Objective
To analyze the dataset that will help to create a model that will predict the cost of medical insurance based on various input features. 

### Domain
Healthcare. 

### Dataset Source
insurance dataset (insurance.csv) 

### Dataset Description
- age - Age of the person
- sex - Female or Male
- BMI - BMI value to estimate an individual's health and fitness condition
- children - number of children (1,2 ,3,4 or 5)
- smoker - the person is a smoker or not
- region - Specifies the region (northeast,northwest,southeast,southwest)
- charges - the amount of insurance   

### Tasks Performed
1. Imported libraries such as Pandas, matplotlib, NumPy, and seaborn and loaded the insurance dataset.
2. Checked the shape of the data along with the data types of the column.
3. Checked missing values in the dataset and find the appropriate measures to fill in the missing values.
4. Explored the relationship between the feature and target column using a count plot of categorical columns and a scatter plot of numerical columns.
5. Performed data visualization using plots of feature vs feature.
6. Checked if the number of premium charges for smokers or non-smokers is increasing as they are aging.
7. After each step, I had specified the observations.

![Screenshot_24-3-2025_163959_lms simplilearn com](https://github.com/user-attachments/assets/1e14e5bc-2d13-4f49-9845-b475560bd8a6)

![Screenshot_24-3-2025_164239_lms simplilearn com](https://github.com/user-attachments/assets/39392fd6-58e3-4edd-af67-5700f0ca77b3)

![Screenshot_24-3-2025_164319_lms simplilearn com](https://github.com/user-attachments/assets/45ed1391-e3a0-4c41-a50d-265a47604007)

### Findings
- From the Analysis, we came to know that in each region the number of smokers is greater than the number of non-smokers  and among them the male smokers are dominating.
- As the age increases there is a gradual increase in the charges.
- Since most of the people is from the southeast region, the insurance charge is high in southeast region.
