The purpose of these notebooks are to perform exploratory analysis of the pricing data, then create a model to predict pricing for new data inputs.

AirBnB_Build_Notebook.ipynb contains a XGBRegressor Model that was trainined using NLP methods. It uses TFidfVectorizer to vectorize the description of the listing and all of its features.

(MVP) AirBnB Build Notebook.ipynb contains the final XGBResressor model which was implemented into the api.

The final model is an SKLearn pipeline, containing an encoder, imputer, scaler, and model. 
Predicting on the target of price per night rented resulted in a mean absolute error of ~50 between the predicted values and holdout data. 

Further improvements could include more columns being used in the model, different model architectures being searched, and additional hyperparameter tuning for each section of the pipeline. 
