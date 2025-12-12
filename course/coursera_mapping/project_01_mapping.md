# Project 1 – Mapping Coursera Materials  

This document maps folders and notebooks from the Coursera Advanced Machine Learning specialization to the needs of Project 1 (Tabular Healthcare ML). The goal is to tell you which course materials to consult now, which to skip for now, and which to return to later.  

## Read now  

These folders contain lessons and assignments that are directly useful for building a strong tabular model:  

- **02_DS_Competition** (How to Win a Data Science Competition: Learn from Top Kagglers)  
  - *Why read*: This course covers feature engineering, data preprocessing, leakage prevention, cross‑validation, evaluation metrics and ensembling. These topics are essential for Project 1 because they teach you how to prepare data, avoid leakage and build strong baseline models on structured data.  
  - *Suggested notebooks*: lessons on feature engineering, evaluation metrics, cross‑validation strategies and the first couple of assignments.  

- **Shared materials on optimization and regularization** from the deep learning course  
  - *Why read*: Even though deep learning is not used for Project 1, the introductory sections on gradient descent, overfitting and regularization provide valuable intuition about training models and preventing overfitting. Read these lightly to understand general training dynamics.  

## Skip for now  

These folders are not necessary for Project 1 and can be safely ignored until later modules:  

- **01_DL** – Deep Learning  
- **03_Bayesian** – Bayesian Methods  
- **04_NLP** – Natural Language Processing  
- **05_RL** – Reinforcement Learning  
- **future courses** – Unreleased or unrelated topics  

These courses introduce neural networks, probabilistic models, natural language processing and reinforcement learning. They will be relevant for later projects but are not needed for a first tabular model.  

## Come back later  

After completing Project 1, revisit these materials as you progress through the program:  

- **01_DL** – Once you start learning deep learning, return here for Module 1.  
- **03_Bayesian** – When you reach the Bayesian module, consult these notebooks for EM, variational inference and Gaussian processes.  
- **04_NLP** – During the NLP project, these notebooks will form the backbone of your learning.  
- **05_RL** – When exploring reinforcement learning, these materials will guide you.  

## New terms introduced  

- **Cross‑validation**: A technique for splitting your data into multiple training and validation sets to estimate how well your model will perform on unseen data. It helps avoid overfitting by ensuring that every data point is used for both training and validation at different folds.  

- **Data leakage**: When a model has access to information during training that would not be available when making real predictions. Leakage causes overly optimistic performance estimates. For example, using features that are derived from the target variable or using future data in a historical prediction.  

- **Baseline model**: A simple initial model used as a reference point. Building a baseline allows you to establish a minimum performance threshold and to measure improvements when you experiment with more complex models. 
