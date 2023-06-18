# Embedding-a-Machine-Learning-Model-into-a-Web-Application-FastAPI



This repository provides a step-by-step guide on how to embed a machine learning model into a web application using FastAPI. FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints. By following this guide, you will learn how to create a simple web application that exposes a machine learning model as an API endpoint.


## Summary

| Name                       | Description        |
| -------------------------- | ------------------ | 
| Code                       | LP6                | 
| Project Name               | Embedding a Machine Learning Model into a Web Application : FastAPI | 
| Published Article          | https://medium.com/@kwabenaabrefa/embedding-machine-learning-for-sepsis-prediction-into-a-web-application-with-fastapi-1887512bc62d |
| Deployed Ap                | https://huggingface.co/spaces/KwabenaMufasa/Sepsis_Machine_Learning_API_-_FastAPI    |
|                            |                    | 



## Project Description
The "Tweets Sentiment Analyzer App" is a gradio online application that employs Huggingface pre-trained models to classify the sentiment of tweets about Covid-19 vaccinations. The software allows users to enter a keyword or phrase linked to Covid-19 vaccinations and provides real-time sentiment analysis of the resulting tweets. DistilBERT is the model utilized in the app. The program also provides a visualization of the findings of the analysis, allowing users to readily view the distribution of favorable, negative, and neutral tweets about Covid-19 vaccinations.



## Setup
----

For manual installation, you need to have Python3 on your system. Then you can clone this repo and being at the repo's root :: friendly_web_interface_for_ML_models> ... follow the steps below:

Windows:

  `python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt`

Linux & MacOs:

  `python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt`


NB: For MacOs users, please install Xcode if you have an issue.



## App Execution

To execute the sentiment analysis application, follow these steps:

Make sure the required dependencies are installed.

Run the deployment script:

bash
Copy code
python app.py
Access the application through a web browser using the provided URL.

Enter the text you want to analyze for sentiment and submit the form.

Click the 'Analyze' button to get the predicted sentiment of the text

The application will process the input text and provide the sentiment analysis result.





## Author
----
FOSTER NANA KWABENA ABREFA

