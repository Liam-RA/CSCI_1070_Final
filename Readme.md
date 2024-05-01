Final Project: Chronic kidney Disease dataset

Null hypothesis: Blood urea will not have any correlation with Chronic Kidney Disease

Alternate Hypothesis: Blood urea will have a correlation with Chronic Kidney Disease (true)


Visuals: heatmap, confusion matrix, boxplot, roc curve, 

Cleaning: 1. convert the categorical values into ints. 2. fill the nulls with values that refelct the distribution of of the non-null values. 3. Standard scalar? (made it worse) 4. Oversampling? (mixed results). 

No get_dummies: the categorical values were binary, so a simple 0 & 1 work. 

Models used: forest, KNN, XGB, logistic regression, SVC

Model tuning: Depends on the model