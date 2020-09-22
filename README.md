# Accident-Severity-Prediction-Model
 Prediction model to get  severity of an accident given the current weather, road and visibility conditions
 A description of the problem and a discussion of the background:
In an effort to reduce the frequency of car collisions in a community, a prediction model to get  severity of an accident given the current weather, road and visibility conditions. This prediction model can be used by the authorities to alert  alert drivers through SMS etc and remind them to be more careful.  Also this can help authorities to plan  road repair actions with needed urgency.
Description of the data and how it will be used to solve the problem  
Our predictor or target variable will be 'SEVERITYCODE' because it is used measure the severity of an accident from 0 to 5 within the dataset. Attributes used to weigh the severity of an accident are 'WEATHER', 'ROADCOND' ,'LIGHTCOND' and SDOT_COLCODE.
Severity can be: Property Damage Only Collision or Injury Collision.
Logistic Regression model has been used to solve the problem. Because our dataset only provides us with two severity code outcomes, our model will only predict one of those two classes. This makes our data binary, which is perfect to use with logistic regression.  


