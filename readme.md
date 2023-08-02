# Statistical Analysis and Machine Learning Approaches for Predicting Police Scotland Case Investigation Duration

## Abstract
The aim of this project was to use statistical analysis techniques and machine learning models
to investigate the feasibility of a model driven decision support system for Police Scotland case
allocation.

As well as using graphical methods, statistical tests were conducted on the feature/target pairs
to identify associations between variables. To predict the investigation duration of cases, both
Regression and Classification approaches were attempted using two popular machine learning
algorithms - artificial neural networks and CART decision trees.

Statistical analysis identified some interesting trends in the data and found statistically significant
associations between numerous feature/target pairs. Weak but statistically significant correlations
were found between the investigation duration and occur range (Spearman’s ρ 0.227) and report
delay (Spearman’s ρ 0.185). Furthermore, at least one dominant category was found to exist in
each categorical variable (P < .001) tested. Despite regression model performance being rather
modest, the simplified binary classification models successfully identified approximately 75% of
cases solved in the same day and approximately 55% of cases taking longer.

The results of the analysis, model evaluation and additional work suggest that model performance
could be improved if more features were available in the dataset. Hence, carrying the implication
that Police Scotland should begin storing more case specific information by default.

## Dataset
Freedom of Information Disclosure: [Here](https://www.scotland.police.uk/access-to-information/freedom-of-information/disclosure-log/disclosure-log-2022/february/22-0170-detected-crimes-by-reported-date-type-mmw-etc/)

## Summary

#### Bivariate Analysis
![image](https://github.com/Mezuah4/caseduration/assets/43442819/e36d133c-31ff-4db6-80a9-2ac49b79b317)

![image](https://github.com/Mezuah4/caseduration/assets/43442819/ad7aa956-d977-4862-bf5c-43ba3fc21ec3)

![image](https://github.com/Mezuah4/caseduration/assets/43442819/d6e461e7-7537-4a74-b94e-7c45741ca784)

#### Model Performance

![image](https://github.com/Mezuah4/caseduration/assets/43442819/fe6a3296-fb64-4e2b-ad1e-d88eb3813c5a)

![image](https://github.com/Mezuah4/caseduration/assets/43442819/a6a7a192-c995-401a-a325-74a4d28b284d)
