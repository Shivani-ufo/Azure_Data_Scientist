## Inferencing

In machine learning, inferencing refers to the use of a trained model to predict labels for new data on which the model has not been trained.


### Real-Time Inferencing

The model is deployed as part of a service that enables applications to request immediate, or real-time, predictions for individual or small numbers of data observations.In Azure Machine learning, you can create real-time inferencing solutions by deploying a model as a real-time service, hosted in a containerized platform such as Azure Kubernetes Services (AKS).
**Deploying a Real-Time Inferencing Service**
You can deploy a model as a real-time web service to several kinds of compute target, including local compute, an Azure Machine Learning compute instance, an Azure Container Instance (ACI), an Azure Kubernetes Service (AKS) cluster, an Azure Function, or an Internet of Things (IoT) module. Azure Machine Learning uses containers as a deployment mechanism, packaging the model and the code to use it as an image that can be deployed to a container in your chosen compute target.


### Batch Inferecing

**What is Batch Inferencing?**
In many production scenarios, long-running tasks that operate on large volumes of data are performed as batch operations. In machine learning, batch inferencing is used to apply a predictive model to multiple cases asynchronously - usually writing the results to a file or database.In Azure Machine Learning, you can implement batch inferencing solutions by creating a pipeline that includes a steps to read the input data, load a registered model, predict labels, and write the results as its output.