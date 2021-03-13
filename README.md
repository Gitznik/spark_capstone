# Sparkify Churn Prediction


---
## Table of Contents
- [Sparkify Churn Prediction](#sparkify-churn-prediction)
  - [Table of Contents](#table-of-contents)
  - [Project description](#project-description)
  - [Get it running](#get-it-running)
    - [Dependencies](#dependencies)
  - [Additional Information](#additional-information)
    - [Author:](#author)
    - [License:](#license)
    - [Acknowledgements:](#acknowledgements)

---

## Project description
This project uses data from a fictional music streaming service called **Sparkify**. The purpose of this project is to use this data to predict user churn. Predicting whether a user will churn has high potential to prevent this from happening and increasing user retention. 

The dataset is 12 gigabytes in size and it makes most sense to process this dataset using cloud computing. To reduce the cost of this project, there also is a smaller subset of data that can be processed locally. 

The EDA and first model training as well as evaluation is performed on the small subset of data in the `local.ipynb` notebook. The full dataset is used in the `databricks.ipynb` notebook, to train one select model that performed best in the local evaluation.

You can find an in depth description of the project on medium: [Predict churn in music streaming services](https://medium.com/p/700791a590fc)

---

## Get it running
### Dependencies
This project was written in Python 3.8.6 and Spark 3.0.1. 
All other dependencies can be found in the requirements.txt.

---
## Additional Information
### Author: 
[Robert Offner](https://github.com/Gitznik)

### License: 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

### Acknowledgements:
* [Udacity](https://www.udacity.com/) for providing the outline of the project as well as the data set.