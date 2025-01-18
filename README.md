
# Life Expectancy Prediction and Hyperparameter Optimization with Optuna
## Project Overview
This project predicts Life Expectancy using health expenditure data with a Random Forest Regressor. It involves preprocessing data, training a model, and optimizing its performance through Optuna to fine-tune hyperparameters. The model's accuracy is evaluated using MAE, MSE, and R². The project demonstrates the application of machine learning and hyperparameter optimization to real-world health data.

###  Hyperparameter Optimization with Optuna
To optimize the performance of the model, **Optuna** is used to fine-tune the hyperparameters of the Random Forest Regressor:
- **n_estimators**: Number of trees in the forest.
- **max_depth**: Maximum depth of each tree.
- **min_samples_split**: Minimum samples required to split an internal node.
- **min_samples_leaf**: Minimum samples required to be a leaf node.

The optimization process runs for 100 trials, each time adjusting these hyperparameters for better model performance.
![image](https://github.com/user-attachments/assets/6a61b101-ef68-449e-baf4-35aeeb8cc430)

### Rebuilding the Model
After optimizing the hyperparameters, the model is retrained with the best-found parameters, and the performance is re-evaluated to see the improvements.

Visualizing the Optuna Results
![image](https://github.com/user-attachments/assets/69359358-6711-4595-ae72-d8ff6069155e)

![image](https://github.com/user-attachments/assets/9d093d8d-e0d9-4316-91f1-eefa5140ddfc)

![image](https://github.com/user-attachments/assets/11270310-3fce-491a-aaa2-35e2b882d63d)

![image](https://github.com/user-attachments/assets/8c5c3c4d-9866-49e7-86cf-51a0f3981727)
## Results
Before optimizing the hyperparameters, the model's evaluation metrics are as follows:
![image](https://github.com/user-attachments/assets/7768bacb-89ff-4f69-ac67-cfd40f6c9fce)

After optimizing the hyperparameters, the model's evaluation metrics are as follows:
![image](https://github.com/user-attachments/assets/776d2867-b689-484f-90f5-2fceae506242)






