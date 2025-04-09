# 🚨 Lung Cancer Risk Analysis Using Power BI & SQL 🚨- Portfolio Challenge
This project aims to analyze lung cancer cases using a data-driven approach, leveraging SQL for data exploration and Power BI for visualization.

<br>
<img src = "https://github.com/user-attachments/assets/bd94510b-2563-4509-8461-ee826609aeaa" width="600" height="350"/>

## **Important Links**
### [LINKEDIN POST](https://www.linkedin.com/posts/amaresam-sai-bharath-chand-47ba50168_lung-cancer-analysis-activity-7298771500776468481-DBHt?utm_source=share&utm_medium=member_desktop&rcm=ACoAACgFj58BoP2A-0POvwS4i3iyqDd6SpSslbo)
### [PRESENTATION](https://github.com/user-attachments/files/19658172/lung_cancer_anlysis.pdf)
### [DASHBOARD](https://app.powerbi.com/view?r=eyJrIjoiMzJkYWRmMDItZjgxNy00OWNlLThlMjMtNTY0MzczMzA1OWUwIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=bc7870b28086c252e3ff)
### [SQL CODES](https://github.com/user-attachments/files/19658229/SQL_codes.pdf)


## 🔍 Business Problem
Lung cancer remains one of the most prevalent and deadliest diseases worldwide, with several contributing factors such as smoking, passive smoking, air pollution, and occupational exposure. Understanding the key risk factors, survival trends, and treatment outcomes can help healthcare professionals and policymakers optimize prevention, early detection, and treatment strategies.


## Meta data and Queries :

<p> The Lung Cancer Prediction Dataset contains patient records that help in analysing risk factors associated with lung cancer. 
It includes demographic details such as age, gender, and country, along with medical and lifestyle factors like smoking habits, passive smoking exposure, and air pollution levels. 
The dataset also provides genetic risk levels, lung cancer diagnosis status, cancer stage, and treatment types, making it useful for predictive modelling and healthcare analytics. 
Additionally, it includes computed risk scores, survival years, and mortality rates, which can be used to assess the impact of different factors on patient outcomes. 
The dataset is valuable for identifying high-risk individuals, studying smoking-related lung cancer trends, and developing early detection strategies. 
Researchers and data analysts can leverage this dataset to build machine learning models for cancer prediction, survival analysis, and personalized treatment recommendations.</p>

### Table Columns :

    ID INT PRIMARY KEY,
    Country VARCHAR(255),
    Population_Size INT,
    Age INT,
    Gender VARCHAR(10),
    Smoker VARCHAR(3),
    Years_of_Smoking INT,
    Cigarettes_per_Day INT,
    Passive_Smoker VARCHAR(3),
    Family_History VARCHAR(3),
    Lung_Cancer_Diagnosis VARCHAR(3),
    Cancer_Stage VARCHAR(50),
    Survival_Years INT,
    Adenocarcinoma_Type VARCHAR(50),
    Air_Pollution_Exposure VARCHAR(10),
    Occupational_Exposure VARCHAR(3),
    Indoor_Pollution VARCHAR(3),
    Healthcare_Access VARCHAR(50),
    Early_Detection VARCHAR(3),
    Treatment_Type VARCHAR(50),
    Developed_or_Developing VARCHAR(50),
    Annual_Lung_Cancer_Deaths INT,
    Lung_Cancer_Prevalence_Rate FLOAT,
    Mortality_Rate FLOAT


### Question To Solve : 

#### Basic Level
1. Retrieve all records for individuals diagnosed with lung cancer.
2. Count the number of smokers and non-smokers.
3. List all unique cancer stages present in the dataset.
4. Retrieve the average number of cigarettes smoked per day by smokers.
5. Count the number of people exposed to high air pollution.
6. Find the top 5 countries with the highest lung cancer deaths.
7. Count the number of people diagnosed with lung cancer by gender.
8. Retrieve records of individuals older than 60 who are diagnosed with lung cancer.

#### Intermediate Level
1. Find the percentage of smokers who developed lung cancer.
2. Calculate the average survival years based on cancer stages.
3. Count the number of lung cancer patients based on passive smoking.
4. Find the country with the highest lung cancer prevalence rate.
5. Identify the smoking years' impact on lung cancer.
6. Determine the mortality rate for patients with and without early detection.
7. Group the lung cancer prevalence rate by developed vs. developing countries.

#### Advanced Level
1. Identify the correlation between lung cancer prevalence and air pollution levels.
2. Find the average age of lung cancer patients for each country.
3. Calculate the risk factor of lung cancer by smoker status, passive smoking, and family history.
4. Rank countries based on their mortality rate.
5. Determine if treatment type has a significant impact on survival years.
6. Compare lung cancer prevalence in men vs. women across countries.
7. Find how occupational exposure, smoking, and air pollution collectively impact lung cancer rates.
8. Analyze the impact of early detection on survival years.

##  💡 Key Takeaways:
- Smoking is the leading risk factor, but passive smoking and pollution also contribute significantly.
- Early detection drastically improves survival rates, emphasizing the need for awareness and screening programs.
- Developing countries face higher challenges due to limited healthcare access and environmental exposure.
- Data-driven insights can help in targeted interventions, improving patient outcomes and reducing mortality rates.

![image](https://github.com/user-attachments/assets/9b1e8005-9f6d-4d82-9654-4e568a33e3cd)

## Conclusion
Lung cancer remains a critical global health challenge, with smoking, air pollution, and genetic factors playing a significant role in its prevalence. 
Through SQL analysis and Power BI visualization, this study uncovered key insights into risk factors, survival rates, and the impact of early detection and treatment.


## **Thanks to**

- This project is part of **Futurion Tech** Portfolio challenge

- A Big thank you to **Futurion Tech** and **Sakshi Mogal** for providing this wonderful opportunity! 

## Hi, I'm Bharath! 👋
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://codebasics.io/portfolio/Amaresam-Sai-Bharath-Chand)
&emsp;
[![Gmail](https://img.shields.io/badge/bharath.temp3@gmail.com-white?logo=Gmail)](mailto:bharath.temp3@gmail.com)
&emsp;
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amaresam-sai-bharath-chand-47ba50168/)
&emsp;
[![youtube](https://img.shields.io/badge/youtube-1DA1F2?style=for-the-badge&logo=youtube&logoColor=red)](https://youtu.be/ZkzLYNFPqwk)
&emsp;









