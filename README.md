# Phase 3 Project - SyriaTel Dataset

Primary Repository for Mason Walter's Phase 3 Project

### Project Overview / Business Problem

Build a classifier to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company.

Most naturally, my audience here is the telecom business itself, interested in reducing how much money is lost because of customers who don't stick around very long. The question I'm asking is: Are there any predictable patterns here?

### The Data

For this project I chose to use the SyriaTel Dataset provided on Kaggle.  It is a binary problem therefore is fairly straightforward in goals
for the models as well as interpretation of results.

### Modeling

I started with a dummy model then built logistic regression and gridsearch models and tuned them to further improve results. This inclutes increasing tolerance and iterations for the logistic regression model as well as heavy tweaking to the parameters of the gridsearch model.

### Evaluation

Overall the model performs well but some more tweaking is necessary for a better picture of when customers will churn.
Right now the model does a fantastic job determining when someone will stay with our service however there is a lot of room for imporvement in predicting when they will leave.


### Conclusion

When retraining the model steps will be taken to improve recall.  These include seperating the call, charge, and minutes columns into each of their own dataframes then scaling each individually.  I will also make use of the location data.  


### Deliverables

There are 3 deliverables for this project:
    1. A Githib Repository with a ReadMe file
    2. A Jupyter Notebook
    3. A Presentation