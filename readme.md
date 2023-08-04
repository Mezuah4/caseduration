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
![image](https://github.com/Mezuah4/caseduration/assets/43442819/de207e17-7681-4f0a-9fe7-52ae858b1ca0)

![image](https://github.com/Mezuah4/caseduration/assets/43442819/22707839-b509-4f14-9572-62d54b4530da)

![image](https://github.com/Mezuah4/caseduration/assets/43442819/f535f19a-411c-4b6b-acc8-de8a7f430bb3)

#### Model Performance

![image](https://github.com/Mezuah4/caseduration/assets/43442819/8f5f13cc-0e14-468b-b3ec-de936abb804c)

![image](https://github.com/Mezuah4/caseduration/assets/43442819/2d02caf0-72e5-42ca-9980-fa4ccd94ef7c)
