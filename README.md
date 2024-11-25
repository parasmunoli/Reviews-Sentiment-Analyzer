# Reviews Sentiment Analyzer

This project analyzes customer reviews to determine their sentiment (positive or negative). It uses machine learning models like Decision Tree, Random Forest, and XGBoost, trained on the `amazon_alexa.tsv` dataset, and provides an API for deployment.

---

## Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Data Processing](#data-processing)  
6. [Models](#models)  
7. [API Deployment](#api-deployment)  
8. [Contributing](#contributing)  
9. [License](#license)

---

## Overview

The **Reviews Sentiment Analyzer** identifies the sentiment expressed in customer reviews. The project includes preprocessed data, trained models, and a deployment-ready API to streamline integration into real-world applications.

---

## Features

- **Data Preprocessing:** Converts raw review data into vectorized inputs.  
- **Model Training:** Supports Decision Tree, Random Forest, and XGBoost models.  
- **Pretrained Models:** Access saved models for immediate evaluation.  
- **API Integration:** A Python-based API for seamless deployment.  

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/parasmunoli/Reviews-Sentiment-Analyzer.git
   cd Reviews-Sentiment-Analyzer

2. Install dependencies:
   ````bash
   pip install -r requirements.txt

## Usage

1. Train Models: Open the Jupyter notebook and follow the steps to preprocess data and train models.
2. Evaluate Models: Use the saved models provided in the repository for evaluation.
3. Run API:
   ````bash
   python app.py
   ````
   Access the API locally to test sentiment analysis functionality.

## Data Processing
The dataset (amazon_alexa.tsv) is preprocessed using techniques like:
    • Text vectorization with TF-IDF.
    • Scaling numerical features.
Processed data is available in the repository.

## Models
 • Decision Tree
 • Random Forest
 • XGBoost
Trained models are saved in the repository for immediate use.

## API Deployment
The project includes a Flask-based API (app.py) that provides endpoints for analyzing review sentiment.

1. Run the API locally:
   ````bash
   Copy code
   python app.py
   ````
2. Use tools like Postman to test the API with review data.