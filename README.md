# Deploy a python machine learning model as a web service
## First steps to deploy a Machine Learning model. This tutorial is divided into 3 parts: Get the data (generate data), Train the model, Expose the model as a web service.

## Run the webserver app.py
## Use of a POST to make a prediction
##  curl -X POST \
##   http://localhost:9099/predict \
##   -H 'Content-Type: application/json' \
##   -d '{"features": [0]}'

## You can access the explanations at the original tutorial link: https://developer.ibm.com/technologies/artificial-intelligence/tutorials/deploy-a-python-machine-learning-model-as-a-web-service/