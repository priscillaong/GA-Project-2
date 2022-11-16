# GA-Project-2

# Problem Statement
We are the Data team working at NexRes which is a property portal trusted for its extensive listings and comprehensive market information on residential property in Iowa.<br>
The aim of this project is to develop a Regression model that can predict to at least 80% accuracy of Iowa property prices by analysing and narrowing down a list of 80 housing features.<br>
This would help agents registered under NexRes to predict property sale prices and use this predictor to advise clients to optimise property for sale and maximise profits of their property.<br>
It is imperative for us to develop this model to maintain our status in the growing industry and empower our agents to continue providing top value to our clients, who rely on us to secure the best deal.<br>

# Data Dictionary
A copy of the data dictionary can be obtained here: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt

# Summary of Analysis
16 out of 80 features have been selected after going through the EDA process.<br>
Ridge Regression model was used to predict saleprice with an accuracy of 83%

# Conclusion/Recommendations
The aim of this project is to develop a Regression model that can predict to at least 80% accuracy of Iowa property prices by analysing and narrowing down a list of 80 housing features.<br>
In our project, we were given 80 housing features which might affect saleprice to analyse. We have narrrowed it down to 16 features after the EDA process. <br>
We then chose the Ridge Regression model to predict saleprices of houses in Ames as it yields the highest R2 and lowest RMSE value amongst all the regression models. The model has an accuracy of 83% in predicting saleprice. <br>
We believe that with such a model, saleprices of houses in Ames can be predicted more accurately by our housing agents and help our clients to optimise property for sale and maximise the profits of their properties. <br>
Moving forward, our recommendations are:<br>
1. To improve our predictions of housing saleprice by implementing another supervised learning model type to improve the accuracy of prediction to above 90%. <br>
2. The limitations to such a model is that it is specific to Ames, Iowa. Our model can be improved to predict saleprices of houses outside of this area.<br>
3. A more updated dataset (after 2020) can be analysed for a more accurate prediction in saleprice of houses.<br>
4. Other features such as amenities in the area or distance to Iowa State University could be studied as it may impact housing saleprice.
