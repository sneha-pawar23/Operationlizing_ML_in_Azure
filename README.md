# :star: Operationalizing The Machine Learning Model In Azure

This project is part of the Udacity Azure ML nanodegree.In this project,we use both Azure ML studio and pyhton SDK to build Automated ML experiment to deploy the best model by enabling authentication.Then, we enable the Application Insights to review importatnt information about the service when consuming the model.And, finally we will create, publish and interact with a pipeline.The main objective of this project is to build a machine learning model using Azure Container Services.We are provided with the banking dataset.
The main steps to be followed to perform project are as follows :-

1) Authentication
2) Automated ML Experiment
3) Deploy the best model
4) Enable logging
5) Swagger Documentation
6) Consume model endpoints
7) Create and publish a pipeline
9) Documentation

# :star: Architectural Diagram

![diagram](screenshots/image.png)

:pushpin: **Authentication** :- Authentication is crucial for the continuous flow of operations, continuous Integration and delivery system(CI/CD) rely on uninterrupted flows. If authentication is not set properly it requires human interactions and thus the flow is interrupted. Thus, its good to use authentication with automation because in ideal scenario the system doesn't stop waiting for a user to input a password.

Authentication types :-
 1) Key based
 2) Token based
 3) Interactive
 
:pushpin: **AutoML model** :- AutoMl is the process of automating the time consuming iterative tasks ofmachine learning models.AutoML iterates the eaxh and every mchine learning algorithms for the particular datasets which we assigned in azure and gives us the results of each algorithm.With automated machinelearning, you'll accelerate the time it takes to get production ready ML models with great ease and efficency.During training period,AutoML creates a several pipelines in parallel which tries different algorithms,parameters,feature selections and also with different metrices and produces a model with a trainig score.
 
:pushpin: **Deploy the best model** :-Deployment is about delivering a trained model into production so that it can be consumed by others.After deploying the model we need to know whether a model is working as excepted or no.User can initate an input request, usually via HTTP POST request.Here the model is deployed in ACI Azure container instance where ACI offers the fastest and simplest way to run a conatiner and also authrntication is enabled to preventunauthorized access.
 
:pushpin: **Enable logging** :-Logging is nothing but the informational output produced by the software usually in the form of text.Application insights is very useful tool to detect anomalies, visualize performance.It can be enabled before or after a deployment of the model.
 
 :pushpin: **Consume model endpoint** :-Here the endpoints allow other services to interact with deployed models.
             There are some interesting details we need to be aware of when trying to use HTTP and you will go through each of these:-
             
   1) Swagger
                    
   2) Consuming deployed services 
                    
   3) Benchmarking
                    
 * Swagger : A tool that eases the documentation efforts of HTTP API's.
  
 * Benchmarking : Being able to create a baseline of acceptable performance so that it can be compared day-to-day behavior.
  
 :pushpin: **Create and publish a pipeline** :- Automation is the core pillar of Deveops applicable to machine learning operations.A good features of azure is pipelines and there are closely related to automation.Some key factors covered about pipelines are:-
 
 1) Creating a pipeline
 
 2) Publishing a pipeline
 
 3) Interacting with a pipeline via HTTP API endpoint
 
 **Create a pipeline** :- This is the most common python SDK class you will see when dealing with the pipelines.Aside from accepting a workspace and allowing multiple steps to bepassed in,it uses a description that is useful to identify it later.
 
 **Publish a pipeline** :- Publishing a pipeline is the process of making a pipeline publicaly available.We can publish pipelines in azure machine learning studio,but we can also do it with python SDK.When pipeline is published, a public HTTP endpoint becomes available, allowing other services, including external ones to interact with an azure pipelines.
 
 :pushpin: **Documentation** :- I have documented the process by creating the screencast of this project as well as this readme.md file describes the complete process of the second project. 
  


# :star: Key Steps

_TODO_: Write a short discription of the key steps. Remeber to include all the screenshots required to demonstrate key steps.

# :star: Screen Recording

_TODO_ Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

# :star: References

:sparkles: [Microsoft_documentation](https://docs.microsoft.com/en-us/documentation/)

:sparkles: [set_up_authentication](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-setup-authentication)

:sparkles: [Application_insights](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-enable-app-insights)

:sparkles: [troubleshooting](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-troubleshoot-deployment?tabs=azcli)

:sparkles: [compute_instance](https://docs.microsoft.com/en-us/azure/machine-learning/concept-compute-instance)

:sparkles: [Swagger_home_page](https://swagger.io/tools/swagger-ui/)

:sparkles: [How_to_consume_webservice](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-consume-web-service?tabs=python)

:sparkles: [Apache_benchmark_tool](https://httpd.apache.org/docs/2.4/programs/ab.html)

:sparkles: [Machinelearning_pipelines](https://docs.microsoft.com/en-us/azure/machine-learning/concept-ml-pipelines)

:sparkles: [Create_run_ML_Pipeline](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-create-machine-learning-pipelines)

:sparkles: [Pipeline_endpoint_class](https://docs.microsoft.com/en-us/python/api/azureml-pipeline-core/azureml.pipeline.core.pipeline_endpoint.pipelineendpoint?view=azure-ml-py)

