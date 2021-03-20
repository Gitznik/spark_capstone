# Sparkify Churn Prediction


---
## Table of Contents
- [Sparkify Churn Prediction](#sparkify-churn-prediction)
  - [Table of Contents](#table-of-contents)
  - [Project description](#project-description)
  - [Files in this project](#files-in-this-project)
  - [* requirements.txt: Contains all python requirements to run this project.](#-requirementstxt-contains-all-python-requirements-to-run-this-project)
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

The EDA and first model training as well as evaluation is performed on the small subset of data in the `local.ipynb` notebook. 
There is also a notebook provided called `databricks.ipynb`, to train one select model that performed best in the local evaluation on the full data set. This model will not be ran though.

You can find an in depth description of the project on medium: [Predict churn in music streaming services](https://medium.com/p/700791a590fc)

---
## Files in this project
* notebooks/databricks.ipynb: Notebook to run on the full data set. Just contains the best performing model.
* notebooks/local.ipynb: Notebook to run on the subset of data. Contains the full EDA and a comparison of all tested models.
* .gitignore: Specifies which files and folders git should ignore
* LICENSE: License file, specifying the MIT licence
* local.html: HTML copy of the notebooks/local.ipynb file
* databricks.html: HTML copy of the notebooks/databricks.ipynb file
* README.md: Readme file
* requirements.txt: Contains all python requirements to run this project.
---

## Get it running
### Dependencies
This project was written in Python 3.8.6 and Spark 3.0.1.
You will need to install these packages with their dependencies:
* Numpy
* Pandas
* Matplotlib.pyplot
* Findspark
* Pyspark

You can find a list of all dependencies in the `requirements.txt` file, as well as the version numbers used in this project.
If you are using pip, you can install them with `pip install -r requirements.txt` from the root path of the project.

---
## Additional Information
### Author: 
[Robert Offner](https://github.com/Gitznik)

### License: 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

### Acknowledgements:
* [Udacity](https://www.udacity.com/) for providing the outline of the project as well as the data set.