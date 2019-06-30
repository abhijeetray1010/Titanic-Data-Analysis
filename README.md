# Titanic-Data-Analysis
#### by Abhijeet Ray
### Introduction
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.
##### Purpose
To perform data analysis on titanic dataset. The project makes use of NumPy, Pandas, matplolib and Data Visualization Libraries.
##### About the dataset
This dataset contains demographics and passenger information from 891 of the 2224 passengers and crew on board the Titanic. Description of this dataset can be viewed on the Kaggle website, where the data was obtained (https://www.kaggle.com/c/titanic/data).
##### Questions
"One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class."
##### What factors made people more likely to survive?
Here we try to analyze which factors were more likely to contribute to the death of the passengers and classify who is more likely to survive depending on the  various factors.

Were social-economic standing like Passenger Class a factor in survival rate?
Did individual characteristics like age, gender, Adult or child determine your chances of survival?

First, the raw comma separated values (.cvs) data will be loaded into a Python (NumPy) series.
Secondly, Data Wrangling process would be carried out
Third, there will be some data exploration. This will be completed mostly by loading plots in order to better understand the data with visualization.

Data Description
(from https://www.kaggle.com/c/titanic)

Passenger ID : Serial ID
Survived: (0 = No; 1 = Yes)
Pclass: Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
Name: Full Name of the Passenger
sex: Male or Female
Age: age in years
SibSp: Number of Siblings/Spouses Aboard
Parch: Number of Parents/Children Aboard
Ticket: ticket Number
Fare: Passenger Fare
Cabin: Cabin number
Embarked: Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
