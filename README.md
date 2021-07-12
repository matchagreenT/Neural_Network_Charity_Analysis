# Neural_Network_Charity_Analysis

## Objective:
With our knowledge in machine learning and neural networks, we use features to provide the datasets to help our client to create binary classifiers. Its capable of predicting successful applicants for funding by Alphabet Soup. 

## Results:
Data Preprocessing:

![image](https://user-images.githubusercontent.com/77694480/125216990-a74c6580-e28d-11eb-9793-3ba5de10dc15.png)
![image](https://user-images.githubusercontent.com/77694480/125217032-b501eb00-e28d-11eb-8906-b8733bc949e1.png)
![image](https://user-images.githubusercontent.com/77694480/125217056-c0edad00-e28d-11eb-85dd-b2e39ca3324e.png)
![image](https://user-images.githubusercontent.com/77694480/125217073-cb0fab80-e28d-11eb-8460-404d05acbc7b.png)

- The IS_SUCCESSFUL column is the variable's target for the model
- Aside from the columns that will be drop, all other features will be used for the model
- The first features that were removed were, EIN and NAME. As they hold no value within the features. 

Compiling, Training and Evaluating:

![image](https://user-images.githubusercontent.com/77694480/125217729-5ccbe880-e28f-11eb-8d99-d1bdd9f7ea07.png)
![image](https://user-images.githubusercontent.com/77694480/125217754-6ead8b80-e28f-11eb-829d-e8547ce4526d.png)
![image](https://user-images.githubusercontent.com/77694480/125217779-7ec56b00-e28f-11eb-8cfc-00a1a1ca1640.png)

- First hidden layer consists of 80 neurons and the second hidden layer consists of 30. Both layers have an activation function called "relu", while the output layer is called "sigmoid"
- The model was not able to achieve the target's performance
- With many changes to try to make the model be more accurate. Yet, still, no changes

## Summary:
With the lack of data to comprise the accuracy of the model, the score ended up at 72%. Just short a few numbers from obtaining the accuracy that was needed but with enough data to included within in this model, possibly the accuracy of the score will be better.
