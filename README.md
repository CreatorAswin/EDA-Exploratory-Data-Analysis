# Exploratory-Data-Analysis-EDA-of-Titanic-The-Ship-that-Sinked-
Exploratory Data Analysis (EDA) of "Titanic : The Ship that Sinked"

EDA or Exploratory Data Analysis is the brainstorming stage of Machine Learning. It is a very important step which takes place after feature engineering and acquiring data and it should be done before any modeling. It's very important for a data scientist to be able to understand the nature of the data without making assumptions.

The purpose of EDA is to use summary statistics and visualizations to better understand data, and find clues about the tendencies (the patterns and trends in the data) of the data, its quality and to formulate assumptions and the hypothesis of our analysis. At this stage, all the useful insights are drawn and correlations between the variables are understood.

EDA or Exploratory Data Analysis is an approach for summarizing, visualizing, and becoming intimately familiar with the important characteristics of a data set.
 
## The main objective is to cover how to:
1. Read and examine a dataset and classify variables by their type: Quantitative vs. Categorical
2. Handle categorical variables with numerically coded values
3. Perform univariate and bivariate analysis and derive meaningful insights about the dataset
4. Identify and treat missing values and remove dataset outliers
5. Build a correlation matrix to identify relevant variables

## RMS Titanic
The RMS Titanic was a British passenger liner that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after it collided with an iceberg during its maiden voyage from Southampton to New York City. There were an estimated 2,224 passengers and crew aboard the ship, and more than 1,500 died, making it one of the deadliest commercial peacetime maritime disasters in modern history. The RMS Titanic was the largest ship afloat at the time it entered service and was the second of three Olympic-class ocean liners operated by the White Star Line. The Titanic was built by the Harland and Wolff shipyard in Belfast. Thomas Andrews, her architect, died in the disaster

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.


## Content
survival Survival : 0 = No, 1 = Yes

pclass Ticket class : 1 = 1st(Upper), 2 = 2nd(Middle), 3 = 3rd(Lower)

sex : M (Male), F (Female)

Age : Age in years (Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5)

sibsp : of siblings / spouses aboard the Titanic ( The dataset defines family relations in this way...)

parch : of parents / children aboard the Titanic (The dataset defines family relations in this way...)
(Parent = mother, father Child=daughter, son, stepdaughter, stepson. Some children travelled only with a nanny,therefore parch=0 for them.)

ticket : Ticket number

fare : Passenger fare

cabin : Cabin number

embarked : Port of Embarkation C = Cherbourg, Q = Queenstown, S = Southampto

## Data Visualizing

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/Pclass.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/survived.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/sex.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/sibsp.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/parch.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/embarked.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/age.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/fare.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/pclass%20and%20survived.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/sex%20and%20survived.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/embarked%20and%20survived.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/age%20and%20fare.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/fare%20and%20pclass.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/fare%20and%20embarked.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/viloin%20sex%20and%20survived%20and%20pclass.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/viloin%20sex%20and%20fare.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/viloin%20sex%20and%20survived.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/viloin%20sex%20and%20pclass.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/crosstab%20sex%20and%20survived.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/crosstab%20sex%20and%20pclass%20and%20survived%20%20and%20embarked.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/count%20sex%20and%20pclass%20and%20survived.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/catplot%20sex%20and%20survived.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/catplot%20survived%20and%20pclass.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/boxplot%20age.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/boxplot%20fare%20.png)

![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/pairplot.png)


![](https://github.com/CreatorAswin/EDA-Exploratory-Data-Analysis/blob/master/heatmap.png)
