# Module17:Comparison various classifiers on bank marketing data
1. Input File: "bank-additional-full.csv"
2. Code Files: I have created 5 individual .ipynb files in the same directory:
   "DecisionTree_Classifier.ipynb" for the Decision Tree Classifier
   "KNN.ipynb" for the K-Neighbor classifier
   "Module17_LR.ipynb" for the Logistic Regression Classifier
   "Module17_SVM.ipynb" for the Support Vector Machine Classifier
   "Module17_Plot_Count.ipynb" to generate count plot for each category
   "Module17_deposit_subscribers.ipynb" to generate barplots of values that have the highest impact to subscribers making deposit
4. "categorical_feature_count" is an ouput plot generated by running Module17_Plot_Count.ipnyb
5. "barplot_deposit_subscribers.png" is the output plot generated by running Module17_deposit_subscribers.ipnyb
6. Finally, "Classifier_Comparison_Report" that provides comparison of the 4 classifiers. I compared 4 different classifiers (KNN, SVM, Logistic Regression and Decision Tree) on the input .csv file “bank-additional-full.csv”. Based on my analysis, I prefer to use Decision Tree Classifier (with Max Depth = 4, Min Samples Split = 2 and Classifier Criterion = gini). Overall this classifier works well with Test Accuracy = 86%. This model also was trained in 11s compared to SVM as an example that took 371s.
7. Business Insight: Clients that have highest probability of subscribing to deposit includes,
•	Job of Admin and Technician
•	Married
•	University or High School Degree
•	Has Housing Loan
•	No Personal Loan
•	Contact communication through Cellular
•	Days contacted on Thursday or Tuesday
•	Month contacted in May or August
•	Number of campaigns is 1 or 2
•	Outcome of previous marketing was a success
•	Number of contacts before the campaign is 1 or 2
•	Does NOT have credit in default

   


