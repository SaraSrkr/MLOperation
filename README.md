
# Machine Learning Operations Project

This project goes through the main steps that take the trained model into production and allow the project stakeholder get ability to interact with it and consume endpoint to get or post data.

## Short description of future improvment
This project use ACI service to deploy the model which is known by its fast and simplicity and as a future improvement we can try to use AKS service that can expand but it will take more effort.

Another suggestion is to improve the auto ML accuracy or choose another algorithm or maybe we can add more data to the model, or add more columns. Also we can make new columns with existing ones with future engineering, not future selection.

## Architectural Diagram
<img src="images/ML Operation Project.jpg" >

## Key Steps

## Automated ML Expermint : register bankmarketing dataset and create auto ML expermint and deploy the best model

Transfer trained model to production need to have a completed experiment for training model or auto ML 
Then choose the best model and deploy it to create endpoint allow others interact with model through it.

<img src="images/Registered Datasets.jpg">

<img src="images/experiment is shown as completed.jpg">

<img src="images/the best model .jpg">

## enable login and excute logs.py to enable application insights

First step to interact with the endpoint model is the ability to login to it by its URL.
Here we enable the application insights to allow login. 


<img src="images/Application Insights is enabled.jpg">

<img src="images/logs by running the provided logs script.jpg">

<img src="images/logs by running the provided logs script 2.jpg">

## Show Swagger documentation after run swagger.sh and serve.py 

I change the port to 9000

<img src="images/swagger runs .jpg">

## Concume Model Endpoint : copy rest url and its key to endpint.py file and excute it then excute benchmark.sh

<img src="images/endpoint script runs against the API producing JSON output from the model.jpg">


<img src="images/Apache Benchmark 1.jpg">

<img src="images/Apache Benchmark 2.jpg">

<img src="images/Apache Benchmark 3.jpg">


## Create, Publish and Consume a Pipeline : uploud jubter notebook and update the varibales to meet my enviroment then run all cells to create and puplish pipeline

<img src="images/pipeline has been created.jpg">

<img src="images/pipeline endpoint.jpg">

<img src="images/Bankmarketing dataset with the AutoML module.jpg">

<img src="images/Published Pipeline overview.jpg">

<img src="images/Use RunDetails Widget.jpg">

<img src="images/pipeline scheduled run.jpg">


## Screen Recording

https://drive.google.com/file/d/1P6XFEQ15Xv8kNYpX9wJI7rnuaQ9_GzhQ/view?usp=sharing


## Standout Suggestions
------
