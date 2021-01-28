# :star: Operationalizing The Machine Learning Model In Azure

The main objective of this project is to build a machine learning model using Azure Container Services.We are provided with the banking dataset. The main steps to be followed to perform project are as follows :-

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
                    
  **Swagger** : A tool that eases the documentation efforts of HTTP API's.
  
  **Benchmarking** : Being able to create a baseline of acceptable performance so that it can be compared day-to-day behavior.
  
 :pushpin: **Create and publish a pipeline** :-
  


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

