     
                            #Mobile-Price-Range-Prediction

                                 AlmaBetter Verfied Project - AlmaBetter School

      ![Screenshot (24)](https://user-images.githubusercontent.com/102009481/177723478-13b7578b-630c-4da0-af38-ecd0738addb5.png)

problem statement
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.
The data contains information regarding mobile phone features, specifications etc and their price range. The various features and information can be used to predict the price range of a mobile phone.Analysis of given data set in following ways.
here, I started with loading the datset ,performing EDA and implemented 4 classification algorithms like random forest,decision tree, logistic regression and xgboost . among the algorithms logistic regression and xgboost performs well with tuning some of the hyperparameters and evaluated the model performance by using confusion matrix.
conclusion
From EDA we can see that here are mobile phones in 4 price ranges. The number of elements is almost similar.
half the devices have Bluetooth, and half don’t
there is a gradual increase in battery as the price range increases
Ram has continuous increase with price range while moving from Low cost to Very high cost
costly phones are lighter
RAM, battery power, pixels played more significant role in deciding the price range of mobile phone. 
form all the above experiments we can conclude that logistic regression and, XGboosting with using hyperparameters we got the best results


