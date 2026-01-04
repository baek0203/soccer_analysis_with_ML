# Soccer Analysis with Machine Learning

This project applies classical machine learning techniques to soccer event data to predict goal-scoring probability, extending beyond traditional Expected Goals (xG) models.

## Motivation (Why?)

In recent years, sports science and data-driven decision-making have become increasingly important in professional soccer.
I wanted to explore how machine learning can be applied to real soccer event data to better understand the factors that influence goal-scoring opportunities.

Rather than relying solely on xG, this project investigates multiple contextual and technical variables that contribute to scoring outcomes.

## Methodology (How?)

This project focuses on traditional machine learning approaches, emphasizing interpretability and feature-based analysis rather than deep learning.

Data Sources : StatsBomb open event data

Visualization and analysis tools : mplsoccer

Supporting materials and workflows inspired by Hudi-based data pipelines

Machine Learning Techniques

- Logistic Regression
- Tree-based models (e.g., Random Forest)

Key Features

- Shot location, Body part, Shot angle and distance, Assist type, Game context (open play, set piece, etc.)

## Objective (What?)

The main objective of this project is to:

- Predict the probability of a goal using multiple soccer event features, not limited to traditional xG assumptions.
By incorporating richer contextual variables, the model aims to provide:
- A more nuanced evaluation of shot quality
- Better insight into why certain chances result in goals
- An interpretable framework for soccer analytics

## Results & Insights

The model demonstrates that goal probability is influenced by a combination of spatial, technical, and contextual factors
Several non-xG features significantly improve predictive performance
Classical ML models provide clear feature importance, making them suitable for tactical analysis

## Limitations

limitations in data collecting as a student. good quality of data is only processed only Business price. 
Temporal dependencies between events are not explicitly modeled
Performance may vary across leagues and competitions


This project demonstrates that machine learning can enrich soccer analytics beyond xG by integrating multiple event-based variables, while maintaining interpretability and practical relevance.
