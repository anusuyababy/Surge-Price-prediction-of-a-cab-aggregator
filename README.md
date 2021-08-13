# Surge-Price-prediction-of-a-cab-aggregator
using jupyter notebook, python, XGBOOST

Problem statement:
                   Sigma Cab Private Limited is a cab aggregator service. Their customers can download their app on smartphones and book a cab from anywhere in the cities they operate in. They, in turn search for cabs from various service providers and provide the best option to their client across available options. They have been in operation for little less than a year now. During this period, they have captured surge_pricing_type from the service providers. Details of the problem statement can be found in Kaggle.


Data dictionary:

   Variable 	                        Definition
Trip_ID 	                          ID for TRIP 
Trip_Distance 	                    The distance for the trip requested by the customer
Type_of_Cab 	                      Category of the cab requested by the customer
Customer_Since_Months 	            Customer using cab services since n months; 0 month means current month
Life_Style_Index 	                  Proprietary index created by Sigma Cabs showing lifestyle of the customer based on their behaviour
Confidence_Life_Style_Index 	      Category showing confidence on the index mentioned above
Destination_Type 	                  Sigma Cabs divides any destination in one of the 14 categories
Customer_Rating 	                  Average of life time ratings of the customer till date
Cancellation_Last_1Month 	          Number of trips cancelled by the customer in last 1 month
Var1, Var2 and Var3 	              Continuous variables masked by the company. 
Gender 	                            Gender of the customer
Surge_Pricing_Type 	                Predictor variable can be of 3 types

Evaluation metric:
               The evaluation metric for this competition is Accuracy Score.
