# Security Access Risk Prediction — DNN vs Random Forest

Machine learning project predicting user security access risk scores 
from cybersecurity behavioural signals.

## Project Overview

Built as part of the AI & Machine Learning Graduate Certificate at 
Humber Polytechnic. This project compares two ML approaches for 
predicting insider threat and access risk in enterprise environments.

**Tools:** Python · TensorFlow/Keras · Scikit-Learn · MinMaxScaler

## Problem Statement

Enterprise security teams need to identify high-risk user behaviour 
before incidents occur. This model predicts risk scores from signals 
including failed login attempts, access time deviation, and 
location anomalies.

## Models Compared

| Model | MAE | MAPE |
|-------|-----|------|
| Deep Neural Network (128→64→32→1) | 4.43 | 11.6% |
| Random Forest | 5.66 | 13.9% |

**DNN outperformed Random Forest on accuracy** — however, Random Forest 
was identified as preferable in regulated security environments due to 
its explainability advantage for audit and compliance requirements.

## Key Skills Demonstrated

- Deep Neural Network architecture design (TensorFlow/Keras)
- Model comparison and evaluation (MAE, MAPE)
- Feature engineering from cybersecurity signals
- Business judgment — accuracy vs explainability trade-off analysis
- MinMaxScaler normalisation for neural network inputs

## Dataset

- 1,156 clean samples
- Features: failed logins, access time deviation, location anomalies
- Target: continuous risk score (regression task)

## Key Insight

Raw accuracy is not always the right metric. In regulated environments 
like banking and healthcare, an explainable model that auditors can 
follow is often more valuable than a black-box model with marginally 
better numbers. This project documents that trade-off explicitly.

## About

Built as part of the AI & Machine Learning Graduate Certificate program 
at Humber Polytechnic, Toronto, ON (2026).
