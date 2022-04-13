# Safe-T:

Analysed malware classifier datasets to advise EV companies for reducing malfunction rates within their EVs using R. 

# Overview:

1. Data cleaning 

2. SMOTE analysis to identify the minority classes in to randomly oversample
 
3. Association rule mining was then used to determine relationships between co-occurring variables. 

4. Data visualisations were built with Plotly and consolidated on an interactive Tableau dashboard. 
 
5. We used Logistic Regression, Random Forest, and Neural Networks to predict malfunction detection capabilities 

   - Logistic Regression, Random Forest and Neural Networks were built twice with and without feature selection with Boruta. 
   
   - K-fold cross validation was used to improve Logistic Regression performances while Grid Search Algorithm was used to improve Random Forest and Neural Network performances.
