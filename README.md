# HeartFlex - Heart Disease Predictor  <img width="50" alt="Screen Shot 2020-07-03 at 5 41 08 PM" src="https://user-images.githubusercontent.com/59619895/86521125-b6970880-be1a-11ea-8aca-8fde154e7225.png">

## Description
* An app developed using `Flutter` to predict the risk of having an heart attack.
* Uses a hyperparameter tuned `LogisticRegression` machine learning model with an accuarcy of 86% to predict the result.
* Uses a total of `thirteen` paramaters (details can be found in folder `machine_learning_model`) as the basis of scoring.
* A Python backend is used to load the trained machine learning model and provide the result in json format to the Flutter frontend

---

## Visuals
![final_pls_1](https://user-images.githubusercontent.com/59619895/86520800-65851580-be16-11ea-86c8-ad58366a72ed.gif)


![final_pls_2](https://user-images.githubusercontent.com/59619895/86520831-cb719d00-be16-11ea-91c5-1c10410e2a0f.gif)

---

## Requirements

* In order for the code to work:
  * Please ensure to run the python backend to access the result of the machine learning model

* To run on a real device please run the following commands on the terminal and replace the `url` in the code with the url derived
  * brew cask install ngrok
  * ngrok http 5000



