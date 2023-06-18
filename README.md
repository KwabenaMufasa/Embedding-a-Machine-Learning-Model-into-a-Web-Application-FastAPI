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
The goal of this project is to build a web application that can predict the probability of sepsis for a patient based on various clinical features. The machine learning model used in this application is trained on a dataset that includes patient demographics, vital signs, and laboratory measurements. The trained model takes these input parameters and generates a probability score indicating the likelihood of sepsis.


The web application built with FastAPI allows users to interact with the model through a user-friendly API. Users can send a POST request to the API endpoint with the required input parameters, and the application will return the predicted probability of sepsis. This enables healthcare professionals and researchers to quickly assess the risk of sepsis for a patient and take appropriate actions.

## Setup

 Install the required packages to be able to run the evaluation locally.

You need to have [`Python 3`](https://www.python.org/) on your system (**a Python version lower than 3.10**). Then you can clone this repo and being at the repo's `https://github.com/kwasiasomani/Machine-Learning-FastAPI/tree/main`  follow the steps below:

- Windows:
        
        python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  






## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.




## Resources

FastAPI documentation: https://fastapi.tiangolo.com


scikit-learn documentation: https://scikit-learn.org


TensorFlow documentation: https://www.tensorflow.org


PyTorch documentation: https://pytorch.org





## Author

FOSTER NANA KWABENA ABREFA


--------
Happy coding! If you have any questions, feel free to contact me.

