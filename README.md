# Neural-Networks
Performed a deep learning model to predict whether a non-profit investment would be successful or not. Got an accuracy score of 72.6% 

How many neurons and layers did you select for your neural network model? Why?
I selected 24 and 12 for my first and second layers. Initially, I thought it would help my model gain more accuracy, but in reality I may have made it prone to overfitting. I initially started out with 10 and 8 layers in each layer and got an accuracy score of 73%. Even with my additions of 24 and 12 neurons, it did not increase the accuracy score of my model. 


Were you able to achieve the target model performance? What steps did you take to try and increase model performance?
I was not. I ran the model without any bucketing and was not able to get a score over 70. After bucketing the government ID tag, I was able to get a score of 73%. Then I increased my neurons from 10 and 8 to 24 and 12 which I thought would help my score increase in accuracy, but it did not. 

If you were to implement a different model to solve this classification problem, which would you choose? Why?
I would choose a random forest classifier because it generally has higher accuracy ratings. While it may take longer to spit out the test result, it ultimately may be more accurate. Using a decision tree may increase the amount of accuracy. 
