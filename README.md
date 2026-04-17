# Enterprise AI Adoption Readiness Assessment

## Overview

This project is a machine learning–based decision support tool that evaluates whether organizations are prepared to adopt artificial intelligence solutions.

It leverages company characteristics such as industry, company size, and AI tool usage to generate a readiness score and provide actionable recommendations. The goal is to support data-driven decision-making for AI strategy and investment.

## Problem Statement

Many organizations invest in AI without a clear understanding of their readiness, leading to failed implementations and wasted resources. This project addresses that gap by providing a predictive model that assesses AI adoption readiness.

## Solution

A Decision Tree classification model is used to:

* Predict whether a company is ready to adopt AI
* Estimate a readiness score
* Identify key drivers influencing adoption

## Key Features

* AI readiness prediction model
* Interactive recommendation system using ipywidgets
* Industry-level analysis of AI adoption trends
* Feature importance insights for decision-making

## Technologies Used

* Python
* pandas
* scikit-learn
* matplotlib
* seaborn
* ipywidgets

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Open the notebook:
   ai_adoption_readiness_predictor.ipynb

3. Run all cells to execute the model and interact with the tool.

## Results

* Model Accuracy: ~51%
* Identified key factors influencing AI readiness, including industry trends and company size
* Generated actionable recommendations based on predicted readiness

## Business Impact

This tool can be used by consulting firms and business leaders to:

* Evaluate organizational readiness for AI adoption
* Reduce risk associated with premature AI investments
* Prioritize high-value AI opportunities
* Support strategic technology planning

## Future Improvements

* Improve model performance with additional features and tuning
* Expand dataset for better generalization
* Deploy as a web-based application for broader accessibility
