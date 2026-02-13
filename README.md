# Mental Health Sentiment Analysis with BERT

**⚠️ Status: Work In Progress - Not Completed Yet**

This project uses BERT (Bidirectional Encoder Representations from Transformers) to classify and analyze mental health-related text sentiment.

## Project Overview

The goal of this project is to build a sentiment analysis model that can detect emotional states and mental health concerns from text data using transformer-based deep learning.

## Project Structure

```
├── data/
│   ├── mental_health_combined_test.csv       
│   └── mental_heath_unbanlanced.csv          # Unbalanced dataset
├── notebooks/
│   ├── mental_health.ipynb                   # Main analysis notebook
└── README.md                                 # This file
```

## Features

- **BERT-based Sentiment Classification**: Uses pre-trained BERT model fine-tuned for mental health text
- **Data Analysis**: Includes exploratory data analysis and feature engineering
- **Model Training & Evaluation**: Training pipeline with Hugging Face Transformers library

## Requirements

See `requirements.txt` for all dependencies. Key packages include:
- transformers
- datasets
- pandas
- torch
- scikit-learn

## Setup

```bash
pip install -r requirements.txt
```

## Usage

Run the main analysis notebook:
```bash
jupyter notebook notebooks/mental_health.ipynb
```

## Model

Trained BERT model

## Current Progress

- [x] Data loading and exploration
- [x] Feature engineering
- [x] BERT model training
- [x] Model evaluation and metrics
- [ ] Performance optimization
- [ ] Deployment setup
- [ ] Documentation completion

