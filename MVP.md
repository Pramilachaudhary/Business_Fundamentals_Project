# Features involved in determining heart disease risk in a person

**Business Problem:** The goal of this project is to predict heart disease at early stage in order to reduce death rates through Fitbit.

**solution path :** To build a logistic regression model to predict heart disease.

**Measures of success:** Successfully reduce the number of peaople die due to heart disease.

**Why heart disease data :**
According to data I found on cdc.gov which says that the heart disease is ranking number one cause of death in US since year 2000
which makes it deadliest disease in the human life accross the world.
source: https://www.cdc.gov/nchs/hus/contents2019.htm?search=Heart_disease,

**Preliminary Analysis:**
The below analysis shows the 2018 death certificate report and their cause of death and 
it clearly shows that heart disease topped among other causes of death.

Valuesin the data set are Age-adjusted deaths per 100,000 population. (only used 2018 data points)

<img width="641" alt="Screen Shot 2022-02-07 at 2 13 46 PM" src="https://user-images.githubusercontent.com/89863226/152881122-f0afdd6f-216b-4177-907a-5404819174dd.png">


The chart below shows that the age group from 50 t0 60 has higher chance of having a heart disease. 

<img width="633" alt="Screen Shot 2022-02-07 at 12 44 27 PM" src="https://user-images.githubusercontent.com/89863226/152873731-89bc8530-c778-417b-bd75-01394efc177f.png">

Chest pain is positively coorelated with the target
The chart below shows that Asymptomatic pain type has higher number of people who had heart disease.
which means there are other factors which can be involved in this like weight, family history, smoking etc.
<img width="615" alt="Screen Shot 2022-02-07 at 12 45 22 PM" src="https://user-images.githubusercontent.com/89863226/152873742-310fea03-f5ed-413b-9a4f-9096a5234f8e.png">

Further in the analysis I would add more features likes max heart rate, Cholestrol etc.
