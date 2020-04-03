## prepr_machine_learning_summer_internship_challange
Data Visualization challenge for summer internship challenge

## Task_1 Visualize Labour Data by province pivotable by age, sex and industry / sector:

[1] Data we taken from statcan website references are given below.

[2] I have provided visualization sample for each pivotable for one province and for the other provience we can derive same with the         code given in the notebook. 

[3] The detail conclusion is given in each jupyter notebook.



## Task_2 Train data using LSTM to predict the data over time:

[1] I have used job_skills.csv file as data source and predict the category based on preferred qualification using LSTM as for text         squence model Recurrent Neural Network work better than the other.

[2] My model has 2 LSTM layer seperated by Dropout(0.2) and followed by Dense and Activation for prediction.

[3] I first used 80% as trainng data and 20% as validation data but due to lake of Data my model overfit and gives me 98% training and       just 20% test accuracy to tackle the overfitting I have choose another approach.

[4] In my second model I have used stratified K-fold ith 10 splits to validate my model and I have improved the accuracy from 20% to 48% 
    I also have used some l2 regularization and some other regularization technique to address overfitting.
    
[5] More information can be find in my Task_2 jupyter notebook.    


## References:

[1]Statistics Canada.  Table  14-10-0023-01   Labour force characteristics by industry, annual (x 1,000)

[2]Statistics Canada.  Table  14-10-0017-01   Labour force characteristics by sex and detailed age group, monthly, unadjusted for seasonality (x 1,000)
