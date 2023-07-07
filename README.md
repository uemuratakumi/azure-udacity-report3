# Your Project Title Here
This is final report of udacity's Machine Learning Enginner with Microsoft Azure.

## Project Set Up and Installation
There is no special set up is need.
Just only use azure default setting.

## Dataset
I used 'Boston house price' data in sklearn as dataset.

### Overview
In this dataset, there are 13 features that is related to house price and house price.

### Task
In this project, 13 features is used as input and price is used as output.
And I conduct regression task.

### Access
I access to the data by using sklearn library.

## Automated ML
Since this is regression task, I set task of AutoMLConfig equal 'regression'.
And I want to make the model that has more linearity, so I set primary_metric to 'peason_correlation' 
But this is not real project, I set early stopping strictly.
Other logging setting is same with sample of SDK.

### Results
XGBoostRegressor is choiced as best model of auto-ML.
And the parameter "tree_method": is "auto".

![automk-rundetail](https://github.com/uemuratakumi/azure-udacity-report3/assets/132246132/b65b051b-6718-45d9-9cc3-b4d7873a9d88)

![automl-best](https://github.com/uemuratakumi/azure-udacity-report3/assets/132246132/c324b18a-4670-408b-a845-0b2015cc0ecc)

## Hyperparameter Tuning
I used neural network model as the base model since I want to use neural network model in real project, so I try it as a practice.
And by using hyperdrive, I swing the number of dense matric [10-100] and learing rate[0.0001-0.01].


### Results
*TODO*: What are the results you got with your model? What were the parameters of the model? How could you have improved it?

*TODO* Remeber to provide screenshots of the `RunDetails` widget as well as a screenshot of the best model trained with it's parameters.

## Model Deployment
*TODO*: Give an overview of the deployed model and instructions on how to query the endpoint with a sample input.

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:
- A working model
- Demo of the deployed  model
- Demo of a sample request sent to the endpoint and its response

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
