# Solution - NASA Pushback to the Future Competition

Caltech "Moles" team respository for predicting pushback times at US airports.  

[Competition website &rarr;](https://www.drivendata.org/competitions/182/competition-nasa-airport-pushback-prescreened/page/712/)

## Overview
This repository contains code to create and execute a model to predict pushback time (defined as the time between when an airplane arives at and departs from the gate) as specified by the 2023 NASA Pushback to the Future Competition. Given provided data from ten US airports, a CatBoost model is trained separately on each airport following data cleansing and feature extraction. 



## Repository Structure


```
nasa-pushback-competition
├── README.md
├── data ------------------> holds raw data
├── model -----------------> holds trained model
├── requirements.txt ------> lists requirements
├── setup.py --------------> makes project pip installable
└── src
    ├── __init__.py
    ├── config.py ---------> path configuration
    ├── make_dataset.py ---> runs feature extraction
    ├── run_inference.py --> pipeline for making predictions
    ├── run_training.py ---> pipeline for training model
    └── utils.py ----------> helper functions used for inference
```

## Setup

Here is how you do setup:
```
codecodecode
```

## Run training

Here is how you run training:
```
codecodecode
```

## Run inference

Here is how you run inference:
```
codecodecode
```