!["Logistic Regression Importances"](https://raw.githubusercontent.com/MattInglisWhalen/RecipeSiteTraffic/main/images/importance_logreg.png "Importances")

This repository is a record of the final project for my Professional Data Scientist certification on DataCamp. The data is synthetic and was produced solely for the purpose of the exam. 

The interactive python notebook [recipe_site_traffic.ipynb](https://github.com/MattInglisWhalen/RecipeSiteTraffic/blob/main/recipe_site_traffic.ipynb) 
performs cleaning, exploratory analysis, and predictive modelling for data regarding fictional cooking recipes that are posted online. Various
feature columns include calorie count and meal type, with the target variable being whether or not the recipe experiences high traffic. The goal of the project
was to predict from the feature columns whether or not a recipe would be classified as a 'high-traffic' or a 'low-traffic' recipe, with the stress being placed
on being as sure as possible that any recipe classified as 'high-traffic' would, in fact, attain that label. As such, more emphasis was placed on `precision`
as a test statistic, rather than `accuracy`. 
