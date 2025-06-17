Organic battery predictor

This project has the following files:

1. multi_task_learning.ipynb: Loading the organic battery dataset, scaling, splitting and training models for 5 folds

2. meta_learner.ipynb: Loading the 5 multi-task models (for 5 folds) and then train on validation dataset (test on training set)

3. inverse_design.ipynb: Specify the reference candidate(s), modify the SMILES and predict the properties using the trained model

    
This repository is based on our published work  [AI-Driven Discovery of High Performance Polymer Electrodes for Next-Generation Batteries](https://doi.org/10.1002/pol.20250198)

