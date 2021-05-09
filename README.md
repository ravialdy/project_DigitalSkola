# Final Project of Digital Skola Data Scientist Bootcamp : Home Credit Default Risk Analysis!

### Outline : 

* Data Overview
* Understanding Data
* Exploratory Data Analysis
* Data Visualisation
* Data Preprocessing
* Developing Model
* Evaluation
* Recommendation

### 1. Data Overview.

#### What is Home credit default risk data?

Dataset provided by Home Credit Group to predict clients repayment abilities.

Dataset include variables such as:

* Client's ID
* Gender
* Clients Income 
* ... and many more

![image](https://user-images.githubusercontent.com/68768305/117557355-34abe780-b09c-11eb-82cb-5481b61af6bc.png)

### 2. Exploratory Data Analysis.

* Obtain Descriptive Statistics of Data
* Check Missing Value 
* Check Duplicated Data
* Check Data Types 

#### a. Obtain Descriptive Statistics of Data.

![image](https://user-images.githubusercontent.com/68768305/117557385-8c4a5300-b09c-11eb-8dd7-6569a1c4ffb3.png)

#### b. Check Missing Value.

![image](https://user-images.githubusercontent.com/68768305/117557419-dc291a00-b09c-11eb-8c8f-2060a6250104.png)

#### c. Check Duplicated Data.

![image](https://user-images.githubusercontent.com/68768305/117557550-0deeb080-b09e-11eb-8ed7-e7f7516f550e.png)

#### d. Check Data Types.

![image](https://user-images.githubusercontent.com/68768305/117557485-68d3d800-b09d-11eb-9ed1-13635f385754.png)

##### Note : For more detail explanation, you can check our notebook!

### 3. Data Visualization.

![image](https://user-images.githubusercontent.com/68768305/117557581-83f31780-b09e-11eb-871a-f482c1617002.png)

![image](https://user-images.githubusercontent.com/68768305/117557587-92413380-b09e-11eb-88af-9c42f441a2d3.png)

### 4. Data Preprocessing.

#### a. Handling Anomalies.

Replacing data that does not make sense.

* Negative values of features *Days_Birth* and *Days_Employed*
* Impossible values of *Days_Employed*

#### b. Equalising independent variables in train and test set.

![image](https://user-images.githubusercontent.com/68768305/117559295-4eeec100-b0ae-11eb-89bd-29333b88a14b.png)

#### c. Convert Categorical data to numerical.

Using One Hot Encoding like this.

![image](https://user-images.githubusercontent.com/68768305/117559413-3f23ac80-b0af-11eb-9cac-8950ebfd97c5.png)

#### d. Imputing missing value.

![image](https://user-images.githubusercontent.com/68768305/117559474-e30d5800-b0af-11eb-9eb9-1836a056586f.png)

#### e. Train test split.

![image](https://user-images.githubusercontent.com/68768305/117559433-67aba680-b0af-11eb-9e47-f7c6f189b559.png)

#### f. Data Scaling.

![image](https://user-images.githubusercontent.com/68768305/117559495-10f29c80-b0b0-11eb-9946-024858aad908.png)

#### g. Data Balancing.

![image](https://user-images.githubusercontent.com/68768305/117559509-31225b80-b0b0-11eb-97c6-487e954fc988.png)

#### h. Feature engineering.

![image](https://user-images.githubusercontent.com/68768305/117559524-4e572a00-b0b0-11eb-9ba9-5abefc98a8cc.png)

### 5. Modelling.

#### We use LGBM with cross validation compared to other models like random forest, logistic, decision tree, etc because it can generate the highest roc-auc score even though it is also the longest in terms of its runtime.

![image](https://user-images.githubusercontent.com/68768305/117559655-582d5d00-b0b1-11eb-92c0-433b890a69bd.png)

![image](https://user-images.githubusercontent.com/68768305/117559601-e48b5000-b0b0-11eb-9141-9b8797248524.png)

![image](https://user-images.githubusercontent.com/68768305/117559609-ff5dc480-b0b0-11eb-80f0-fd46b28e00de.png)

### 6. Recommendation : Feature Importances.

![image](https://user-images.githubusercontent.com/68768305/117559677-890d9200-b0b1-11eb-838e-6fae69230838.png)

![image](https://user-images.githubusercontent.com/68768305/117559683-9a569e80-b0b1-11eb-98d8-a144f3c14dc7.png)

### 7. Submit to Kaggle.

![image](https://user-images.githubusercontent.com/68768305/117559700-c07c3e80-b0b1-11eb-8f31-f5d43d22fc0f.png)

### Team Members : 

* Ravialdy Hidayat
* Ricardo Valentino

### Reference :
* https://www.kaggle.com/willkoehrsen/start-here-a-gentle-introduction
* https://www.kaggle.com/codename007/home-credit-complete-eda-feature-importance
* https://www.kaggle.com/willkoehrsen/introduction-to-manual-feature-engineering
* https://www.kaggle.com/ogrellier/feature-selection-with-null-importances
* https://www.kaggle.com/jsaguiar/lightgbm-with-simple-features
* https://www.kaggle.com/gpreda/home-credit-default-risk-extensive-eda
* https://www.kaggle.com/shivamb/homecreditrisk-extensive-eda-baseline-0-772
* https://www.kaggle.com/tilii7/olivier-lightgbm-parameters-by-bayesian-opt









