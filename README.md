# Neural_Network_Charity_Analysis

## Purpose
The purpose of this analysis was to use the given data of past foundations to see if we could create a model that would predict a good investment using deep learning.

## Results

- The target variable was IS_SUCCESSFUL because those were good investments in the past
- The rest of the variable that were not identifiers were the features
- Identifier variables such as Namea and EIN were not neccessary
- I chose to have three layers starting with 129 nuerons because that was three times 43 which were the number of features. Then I decreased that amount by 66 percent for each layer because that is reccommended. 

- I was not able to achieve target performance and after multiple attempts maxed out at 73.4%
![image](https://user-images.githubusercontent.com/83510059/141709438-90c9b574-235e-4ede-bd62-469617475043.png)

- I tried switching activation functions, adding layers, increasing nuerons, and taking away features to achieve a higher accuracy score.

## Summary
The over all results had a lot of loss as each attempt had over 50% and the accuracy never achieved 75%. I would try different Random Forest machine learning as that is both faster and easier to understand so it might help the data scientist to find the unneccary features.
