# Fraud Service

## Context
Imagine we (the data science team) built a fraud detection model in python, available in a Jupyter Notebook. The model uses features related to an online purchase and predicts whether or not the purchase is fraudulent. 

Though not necessary for this exercise, more information about the data and the model construction exercise is available here: https://github.com/alphasights/fraud-detection 

## Expectations
You should plan on spending 2-3 hours on this task. We understand that this time frame limits the scope of the implementation. The focus should be on delivering a working service, as explained below. We can subsequently discuss jointly the corners you may have cut, the design choices you made, and ways the design and implementation could be extended. 

## Task 
Your task is to build a python service to expose the predictive model for fraud that is created in the supplied Jupyter Notebook. Specifically, this includes:

1. Examining the supplied Jupyter notebook, and familiarizing yourself with the work previously carried out.
2. Extracting the model, and any needed additional information, and ingesting it into your service. 
3. Designing an API for interacting with the model. At a minimum, the API should allow for new potential instances of fraud to be sent to the service, and the service should respond with the model's prediction as to whether the instance is fraudulent
4. Implement the API. The response should be returned in a readable format. 
5. Include in your submission a README on getting the service up and running and instructions on how to send requests into your service.

## Potential final-round discussion points
- What testing approach would give you confidence that everything is working as expected?
- How would you incorporate a new, updated model into the service?
- The exploratory data analysis, feature engineering and model selection and tuning has been omitted from this exercise. How would you critique the work already done and what would you work on next to improve the model?
