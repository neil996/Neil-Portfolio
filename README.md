# Neil_Portfolio
Data Science Projects Portfolio


# [Project 1:Analyzing Covid-19 Deaths in Patients with Different Conditions among Various Counties in the United States of America](https://github.com/neil996/Factors-affecting-Covid-19.)

* The project aims to generalize the effects of Novel coronavirus across different counties in United States Of America and moreover discuss various different factors affecting the same. We have taken into account multiple age factors which are getting affected due to the virus and moreover takes into account different condition factors. The project looks to find distinct and diverse factors in various age groups, i.e. how they are impacting Covid deaths and cases across various regions in United States. The domain of the datasets is related to health care as discussed above the project aims to identify the impact of Covid. The datasets have been selected to take into account all these factors so as to combine diverse factors to get a generalized sense from the available data. The data is obtained mainly from Centre for Disease Control and Prevention which is Federal organization collecting data on daily or random basis as per their availability, moreover as per their description states and local authorities reports the cases regularly to keep the data up to date.

VIM (Visualization and Imputation of Missing Values) package helps to visualize the missing data in a deep way and thus can help to apply specific mechanisms which can be helpful in analyzing the missing values and deciding whether to impute/replace or remove it, while Fig Shows the implementation of VIM package.

![image](https://user-images.githubusercontent.com/78203289/120682224-1d41fd80-c494-11eb-8139-a3317a1da040.png)

Regression Techniques Implemented:
i. XGBoost ii. Random Forest iii. Multiple Linear Regression iv. Decision Tree

Classification Models Implemented:
i. KNN(K-Nearest Neighbor) ii. SVC(Support Vector Classification)

1.) Conditions contributing to Covid deaths by age groups across different counties in United States

• Models Buildup

i) XGBoost Model: In our model buildup XGBoost Cross validation is done using xgboost in-built method such as xgb.cv, which tweeks certain parameters and thus is helpful to get the evaluation log which contains the minimum and maximum tress which are built, using this data we can get the minimum number of trees which are required to predict the dependent variables in the dataset.

ii) Random Forest Model: In our model we have used only 50 trees as increasing the number of trees is increasing computation to an indefinite time and thus is not able to give submissive results, thus the trees has been pruned down to avoid computational error within the model.

2.) United States COVID cases and deaths

• Models Buildup

i) Multiple Regression Model: Multiple regression model takes into account multiple factors affecting the dependent variable in the dataset. Also it generates dummy variables, as the data contains many categorical variables which requires special needs as they cannot be entered into the regression model as it is, thus they are recoded into a series of variables.

ii) Decision Tree Model: Decision Tree works on the model of nodes and constructing a tree with a certain length, in some cases maximum depth variable can be used to much extent. Decision Tree works on the concept of splitting the nodes and thus we have to define the number of minimum splits while defining the decision tree model.We have used rpart library as part of decision tree in R to build and execute the model, moreover the model is also pruned to get the best possible decision tree with minimum number of splits and complexity parameter and as it is a regression model we have used method as anova

3.) United States Covid-19 cases and deaths over time

• Models Buildup:

i) KNN (K-Nearest Neighbor): KNN or K nearest Neighbor is a classification as well as Regression model, which takes into the Euclidean distance. KNN application is rather simple as compared to other Machine Learning methods, moreover the number of Hyper-parameters required in KNN is only defining the number of neighbors i.e. k.After this the KNN model is applied with the optimal parameters and accuracy is checked using different libraries such as confusionMtarix which gives a cumulative results on the accuracy of the data along with Kappa value and many other.

ii) Support Vector Classification: SVC or Support Vector Classification like KNN algorithm make use of Euclidean distance. The motive for using SVC is that it can generalize for a large set of data as SVC uses epsilon hyperplane to get the model parameters in a high dimensional space. We made use of radial basis function while defining the kernel as with the help of kernel the model is able to visualize the parameters in a high dimensional space and can give the values necessary for the model, to build support vectors.

Findings: • In the year 2020 California has the highest number of number of deaths in all age groups, on grouping the results By Year, followed by Florida and New Jersey

image

• The state wise distribution as shown in Fig. 11. Shows Texas having highest number of Total Deaths followed by Georgia, moreover Texas even has highest number of New cases thus throwing new insight how different counties are showing increasing trends in cases and death rates.

image

• Arizona has the highest number of confirmed deaths recorded and also has the highest number of probable new deaths also it has the confirmed number of deaths crossing 5 million. As shown in Fig. 12. Shows different Pie charts.

image
