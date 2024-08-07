
# Crop Yield Prediction

This repository contains a Crop Yield Prediction project developed using Flask, HTML, CSS, and a machine learning model trained with Python. The project aims to predict crop yield based on various input features.

## DISCLAIMER ⚠️
This is a POC(Proof of concept) kind-of project. The data used here comes up with no guarantee from the creator. So, don't use it for making farming decisions. If you do so, the creator is not responsible for anything. However, this project presents the idea that how we can use ML into precision farming if developed at large scale and with authentic and verified data.
## MOTIVATION 💪
- Farming is one of the major sectors that influences a country’s economic growth.

- In country like India, majority of the population is dependent on agriculture for their livelihood. Many new technologies, such as Machine Learning and Deep Learning, are being implemented into agriculture so that it is easier for farmers to grow and maximize their yield.

- In this project, I present a website in which the Crop Yield Prediction of any country is implemented

  - In the Crop Yield Prediction, the user can provide the average rainfall data, country, year, pesticides, temperature and country from their side and the application will predict yield of their crop.
## Built with 🛠️

<p align="center">
  <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" alt="Python" width="50"/>
  <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" alt="JavaScript" width="50"/>
  <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" alt="HTML" width="50"/>
  <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" alt="CSS" width="50"/>
  <img src="https://raw.githubusercontent.com/numpy/numpy/7e7f4adab814b223f7f917369a72757cd28b10cb/branding/icons/numpylogo.svg" alt="NUMPY" width="90"/>
  <img src="https://raw.githubusercontent.com/pandas-dev/pandas/761bceb77d44aa63b71dda43ca46e8fd4b9d7422/web/pandas/static/img/pandas.svg" alt="PANDAS" width="90"/>
  <img src="https://camo.githubusercontent.com/55a55cebad6360bda8bca520c61e0e195dc7ee413bf9982f1ba86cab496f2388/68747470733a2f2f6d6174706c6f746c69622e6f72672f5f7374617469632f6c6f676f322e737667" alt="matplotlib" width="90"/>
  <img src="https://camo.githubusercontent.com/c84f8ccac2a223fcabe74cd7975a3b31a2618b29d2c4fcea268f16b9151ad5fd/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f302f30352f5363696b69745f6c6561726e5f6c6f676f5f736d616c6c2e7376672f3132383070782d5363696b69745f6c6561726e5f6c6f676f5f736d616c6c2e7376672e706e67" alt="scikit-learn" width="90"/>
</p>


## Demo

### Crop Yield Prediction
![crop_yield](https://github.com/user-attachments/assets/716f0584-8831-4f3f-bea6-5fccbba2c168)





## Table Of Content
## Features

- Predict crop yield using a trained machine learning model
- User-friendly web interface
- Easy to deploy and run locally 



## Installation

To get started, clone the repository and install the dependencies:

To run this project locally, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/PPanwar29/crop_yield_prediction.git
   cd crop-yield-prediction

2. **Create a Virtual Environment and Activate It**
    ```bash
   python -m venv venv
    source venv/Scripts/activate
2. **Install the Dependencies**
    ```bash
   Eg.= pip install -r numpy
        pip install -r scikit-learn
2. **Add your Modal**

    Place your trained model file (dtr.pkl,preprocessor.pkl) in   the root directory of the project.
## Usage/Examples

1. **Run Flask**
   ```bash
    python app.py
1. **Open the Application in Your Browser**
Go to link provided in your web browser.
Enter the required input features for crop yield prediction and click "Predict".

## Configuration

Ensure that your model.pkl file is correctly configured and placed in the root directory. The application will load this model to make predictions.

## Contact
If you have any questions or suggestions, feel free to reach out to me at pspanwar2972@gmail.com
