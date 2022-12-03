
# Operationalizing Machine Learning

This project is part of the Udacity Azure ML Nanodegree. This project aims to create the best model using Azure ML studio and Python SDK. Also, I have provided the steps followed. Here I consumed the provided dataset “bankmarkting_train” which contains the marketing campaign of a Portugal baking institution. The final goal is to predict the whether the client will subscribe to a bank team deposit (column y).

As part of the Automated experiment, I have done the following activities, using ML studio register the dataset, created Auto ML, choose the best model and deployed in (ACK instance, enabled the Application insight logging and Enabled Authentication). Tested the final endpoint with swagger documentation.

Part of the pipeline experiment done the following activities, used existing workspace, Attached existing AmlCompute, load TabularDataset , Configure AutoML using AutoMLConfig , Train the model using AmlCompute ,  Explore the results and tested the best-fitted model.


## Architectural Diagram
 ![Process Flow Diagram](/ML%20Architecture.png "Process Flow Diagram")


## Key Steps
 - Created dataset name and location 
 
 ![Process Flow Diagram](/Registered%20Dataset.png "Register Dataset")
 
 - Automated ML Job completed status 
 
 ![Process Flow Diagram](/Experiment_Completed.png "Experiment completed")
 
 - Best model summary
 ![Process Flow Diagram](/Experiment_Bestmodel.png "Experiment_Bestmodel")
 
 ![Process Flow Diagram](/Experiment_Bestmodel_2.png "Experiment_Bestmodel_2")
 
  - Deployment step and enable applicaiton Inisght 
 
 ![Process Flow Diagram](/EnableAppInsight.png "EnableAppInsight")
 
  - Endpoint deployment status 
  
 ![Process Flow Diagram](/DeployBestModel%20ACI.png "DeployBestModel")
 
  - logger details
 
 ![Process Flow Diagram](/Endpoint%20deployment.png "Endpoint%20deployment")
 

   
 ![Process Flow Diagram](/Endpoint%20deployment_Finished.png "Endpoint%20deployment_Finished")
 
  - Applicaiton insight logging 
 
 ![Process Flow Diagram](/AppInsightoutput.png "AppInsightoutput")
 
  - Swagger enpoint testing
 
 ![Process Flow Diagram](/Swaggerrun.png "Swaggerrun")
  
 ![Process Flow Diagram](/Swaggerrun_command.png "Swaggerrun_command")
 
   - Endpoint result
  
 ![Process Flow Diagram](/EndpointResult.png "EndpointResult")
 
  - Pipeline running details
 
 ![Process Flow Diagram](/pipleiline%20created.png "pipleiline%20created")
 
   - Pipeline run status
 
 ![Process Flow Diagram](/Pipeline%20run%20final%20model.png "Pipeline run final model")
 
 - Jupyter Notebook run details
  
 ![Process Flow Diagram](/published%20pipeline%20overview.png "Published new pipeline")

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
- The automated ML can provide the data clean-up activity summary to generate the best data for the prediction. 
- This fine tune data can be used for further processing and save the computation.

- Before passing to the actual predication, we might need to fine-tune the data

- The experiment can provide a tentative duration of how much time is required to complete the end-to-end process.

