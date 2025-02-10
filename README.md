
# IMDB Reviews Sentiment Analysis

Sentiment Analysis of IMDB Reviews using Transformer  
`(distilbert-base-uncased-finetuned-sst-2-english)`

## Table of Contents
- [Overview](#overview)
- [Step-by-Step Guide](#step-by-step-guide)
- [Usage](#usage)
- [License](#license)

## Overview
This repository demonstrates how to perform sentiment analysis on IMDB reviews. It uses a Transformer model—**distilbert-base-uncased-finetuned-sst-2-english**—to classify reviews into positive or negative sentiments. The main interactive element is provided through the Jupyter Notebook file `imdb_sentiment_analysis.ipynb`.

## Step-by-Step Guide

1. **Clone the Repository**  
   Open your terminal and run the following command to clone the repository:
   ```bash
   git clone https://github.com/harshhmaniya/IMDB-Reviews-Sentiment-Analysis.git

2. **Navigate to the Repository Directory**  
   Change your working directory to the cloned repository:
   ```bash
   cd IMDB-Reviews-Sentiment-Analysis
   ```

3. **Launch the Jupyter Notebook**  
   Start Jupyter Notebook and open the `imdb_sentiment_analysis.ipynb` file:
   ```bash
   jupyter notebook imdb_sentiment_analysis.ipynb
   ```
   This notebook contains the interactive code cells that guide you through the process of performing sentiment analysis using the specified Transformer model.

4. **Follow the Interactive Cells**  
   Execute the notebook cells one by one. The cells will load the model and process sample IMDB reviews to display their sentiment (positive or negative).

## Usage
The provided Jupyter Notebook is set up for interactive exploration. You can modify the cells to input your own IMDB reviews for sentiment prediction using the `distilbert-base-uncased-finetuned-sst-2-english` Transformer model. Simply run the cells in sequence to see the results.

## License
This project is licensed under the [MIT License](LICENSE).
