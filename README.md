# Springboard-Capstone-2
## **Predictors of Crime**

Crime rates are ever growing in the US. This study will analyze which variables are the best predictors of crimes. Analyzing such variables can help alleviate socioeconomic circumstances for communities which experience high crime rates.

![](Capstone%20Two%20(Geospatial%20Visualization)/ViolentCrimes.PNG)

### **1. Data**

The dataset is from the UCI MAchine Learning Reppository. The dataset is real and authentic. It was prepared using real data from socio-economic data from 1990 US Census, law enforcement data from the 1990 US LEMAS survey, and crimedata from the 1995 FBI UCR [13].
UCI Machine Learning Repository contains free datasets which can be used by anyone trying to hone their Machine Learning/Data Science skills. The dataset was originally acquired from Kaggle (another website which hosts Machine Learning competitions) and was cleaned through the various steps of the Capstone.
This dataset contains a total number of 147 attributes and 2216 instances.
For the purpposes of the Capstone, only 15 of the attributes were used to see which variable performed as the best predictor of crime rates across the US.

> * [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/communities+and+crime)

> * [Kaggle](https://www.kaggle.com/kkanda/communities%20and%20crime%20unnormalized%20data%20set)


### **2. Data Wrangling**
The Data Wrangling portion features steps in order to get acquainted with the dataset. 
* **Step 1:** All the appropriiate features such as unemployment rates, race, education, vacancy, and type of crime were observed, along with basic statistical details such as percentile, mean, max, min, and std. Furthermore, each column was checked for the percentage of missing values. 
* **Step 2:** The datset's categorical attributes were checked for unique values and any duplicate values under 'communityname'. Coommunities with the same names were checked which states they are from and were validated that the duplicates belonged to different states. Then the attributes of interest were averaged and grouped by state to see how each attribute differed from state to state. The distributions were also visulaized through horizontal bargraphs. Boxplots were also used to visulaize the distribution of Violent and NonViolent Crimes for each state.
![](Capstone%20Two%20(Data%20Wrangling)/CrimeBoxPlot.png)
