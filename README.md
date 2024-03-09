# TRINIT-Matrix-Masters-ML02-
# Sexual Harassment Detection System

This repository contains code for detecting instances of sexual harassment in text descriptions using machine learning models. The system employs both traditional machine learning classifiers (Support Vector Machines) and deep learning models (LSTM) for multi-label classification of text descriptions into different categories of harassment.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Results](#results)

## Introduction

Sexual harassment is a prevalent issue in society, especially in online platforms and workplaces. This project aims to develop a system that can automatically detect instances of sexual harassment in text descriptions. The system utilizes both traditional machine learning and deep learning techniques to classify text descriptions into various categories of harassment, such as commenting, ogling, and touching/groping.

## Dataset

The dataset used in this project consists of labeled text descriptions, where each description is labeled with multiple harassment categories. The dataset is available in the `dev.csv` file. It includes the following columns:

- `Description`: Text descriptions of incidents.
- `Commenting`: Binary label indicating whether the incident involves commenting harassment.
- `Ogling/Facial Expressions/Staring`: Binary label indicating whether the incident involves ogling, facial expressions, or staring harassment.
- `Touching/Groping`: Binary label indicating whether the incident involves touching or groping harassment.

## Results
The performance of the models can be evaluated using metrics such as accuracy, precision, recall, and F1-score. The results of the model evaluation on the validation set are provided in the notebook.


