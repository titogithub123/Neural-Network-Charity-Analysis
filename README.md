# Alphabet Soup Charity - Neural Network-Charity-Analysis
 
## Overview
The purpose of this analysis is to use a deep learning neural network technique to analyize and classify the potenial succeess of charitable contributions. 

## Results
### *Data pre-processing*
- The target for the model is IS_SUCCESSUL

- The features for the columns are 
    - application type
    - affiliation
    - classification
    - use case
    - organization
    - income amt
    - special consideration
    
- The columns that need to be removed are
    - ein
    - name

- Compiling, Training, and Evaluating the Model
    - I choose two hidden layers with 80 and 50 nodes as it would allow for ample training with the approximately 40 features. The activation function used was relu because it is best choose to give good speed for our binary sigmoid to be able to discern the output.
    - The mode accuracy was below 75% at about 73% and so below the threshold for our target.
    - To increase the performance I tried to increase the nodes used, as well as change the activation layer model to a tanah to see if it improved performance. 

## Summary
