# Predict Bike Sharing Demand with AutoGluon

## Introduction to AWS Machine Learning Final Project

## Overview
This project utilizes the AutoGluon library to tackle the Bike Sharing Demand competition on Kaggle. By leveraging Tabular Prediction techniques, we will analyze and fit data from CSV files provided by the competition to predict bike-sharing demand effectively.

Bike-sharing demand forecasting is crucial for businesses like Uber, Lyft, and DoorDash, as accurate predictions enable better resource allocation, improved customer experiences, and reduced service delays.

Throughout this project, several models will be trained and optimized, culminating in multiple competition submissions that reflect the progression of our predictive efforts. Additionally, a comprehensive report detailing our methodologies, results, and insights will be created, allowing us to share our findings publicly on Kaggle and showcase our work.

## Getting Started
* Clone this template repository into AWS Sagemaker Studio (or local development).
* Visit the [Kaggle Bike Sharing Demand Competition](https://www.kaggle.com/c/bike-sharing-demand) page. There you will see the overall details about the competition including overview, data, code, discussion, leaderboard, and rules. You will primarily be focused on the data and ranking sections.

### Dependencies

```
Python 3.7
MXNet 1.8
Pandas >= 1.2.4
AutoGluon 0.2.0 
```

### Installation
For this project, it is highly recommended to use AWS Sagemaker Studio. This will simplify much of the installation needed to get started.

For local development, you will need to setup a jupyter lab instance.
* Follow the [jupyter install](https://jupyter.org/install.html) link for best practices to install and start a jupyter lab instance.
* If you have a python virtual environment already installed you can just `pip` install it.
```
pip install jupyterlab
```
* There are also docker containers containing jupyter lab from [Jupyter Docker Stacks](https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html).

## Project Instructions

1. Create an account with Kaggle.
2. Download the Kaggle dataset using the kaggle python library.
3. Run the jupyter notebook.
