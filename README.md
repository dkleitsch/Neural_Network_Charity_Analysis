# Neural Network Charity Analysis
## Overview
Using Python, Pandas, and TensorFlow, a neural network was created to determine which non-profit organizations should receive funds from Alphabet Soup.
## Results
### Data Preprocessing
- Target: IS_SUCCESSFUL
- Features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
- Removed: NAME, EIN
### Compiling, Training, and Evaluating the Model
- For the first attempt, I used three hidden layers with 120, 80, and 45 nodes respectively and two activation functions (ReLU and Sigmoid).  I was trying to see if adding more hidden layers and nodes would increase the accuracy of the model.
- I was not able to achieve the target model performance.

![Attempt 1](https://github.com/dkleitsch/Neural_Network_Charity_Analysis/blob/main/Neural%20Net/Attempt%201.png)

- For attempt 2, I added more nodes to each hidden layer and changed the activation function to tanh.  This did not result in the target model performance either.

![Attempt 2](https://github.com/dkleitsch/Neural_Network_Charity_Analysis/blob/main/Neural%20Net/Attempt%202.png)

- For attempt 3, I added an additional hidden layer and changed the activation function to ReLU.  This also did not result in the target model performance.

![Attempt 3](https://github.com/dkleitsch/Neural_Network_Charity_Analysis/blob/main/Neural%20Net/Attempt%203.png)

## Summary
All of my attempts resulted in models with accuracy scores around 72%.  I think decreasing the features included in the model may help improve the model's performance because then there might be less unnecessary information getting in the way.
