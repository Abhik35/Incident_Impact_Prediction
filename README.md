# Incident_Impact_Prediction
To predict the impact of the incident raised by the customer.
##Objective:

Whenever a service being provided to the customer is disrupted, the customer raises a complaint to the customer service; who in turn raises a ticket. 
When an incident is logged, a lot of data related to the incident is recorded for ex: time, status …
Our objective is to predict the impact of an incident i.e whether it is High, Medium or Low, so that the company can optimize the resource allocation to focus on the important incidents.
A quicker resolution translates to customer satisfaction/retention which leads to better business.

##Project Flow
Understanding the business problem.
Data collection
Data preparation.
EDA and Feature Engineering
Model building
Model training and evaluation
Deployment

##Challenges faced?
Dominance of categorical features.
Ambiguity in representation of null values.
Date time features recorded using object datatype and had few null values.
poor correlation between features and target except for a few features.
imbalanced dataset.


##How did you overcome?
Categorical features encoded with appropriate encoding techniques.
All ambiguous cases considered as null values after multiple discussions with team, mentor and some analysis.
Date time features converted to correct datatypes and appropriate features extracted.
Poor correlations - Used feature selection techniques to eliminate unwanted features and consulted with a subject expert to verify if the finalized features were really important for predictions.
Imbalanced dataset - Used SMOTE for balancing the dataset but performance was same with/without SMOTE.
