# Predict-schizophrenia-using-brain-anatomy



## Table of Contents

* [About the Project](#about)
* [Problematic](#problematic)

## About

Welcome to our project on predicting schizophrenia using brain anatomy 🧠! 

This project was completed as part of [Edouard Duchesnay](https://github.com/duchesnay)'s Machine Learning course at the University of Paris 1 Panthéon-Sorbonne. Our team, consisting of [Yanis Rehoune](https://github.com/Yanisreh) and [Lucie Gabagnou](https://github.com/luciegaba), is proud to present our findings.

The results of the project were submitted through both a research paper included in this repository and a submission to the Challenge platform specified in the tutorial at https://github.com/duchesnay/brain_anatomy_schizophrenia.git. The research paper provides a thorough overview of the methodology and results of the study.

Explore our project and learn more about the exciting potential of using machine learning to diagnose schizophrenia based on brain anatomy. Join us in advancing the field of medical AI and discover the groundbreaking insights we uncovered!

## Problematic

Schizophrenia is a complex psychiatric disorder associated with widespread brain atrophy. In this project, we aim to predict the clinical status of individuals with schizophrenia versus healthy controls using grey matter (GM) measurements from brain imaging. 

The data used for this project consists of 410 samples in the training set and 103 samples in the test set, obtained through voxel-based morphometry (VBM) using the cat12 software. 

The software provides two types of data:
- Regions of Interest (ROIs) of Grey Matter scaled for Total Intracranial Volume, with 284 features.
- VBM GM 3D maps or images in the MNI space, containing 3D images of shapes (121, 145, 121). Masking the brain results in 331,695 input features (voxels) for each participant.

The goal of this project is to learn a predictor of the clinical status of individuals with schizophrenia and healthy controls using the grey matter measurements provided by the previous data. 





