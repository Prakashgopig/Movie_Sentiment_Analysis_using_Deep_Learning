# IMDB Sentiment Analysis

## Overview
This project involves performing sentiment analysis on the IMDB Movie Reviews dataset. The goal is to classify movie reviews as either positive or negative using natural language processing (NLP) techniques and neural networks. The analysis includes data cleaning, exploratory data analysis (EDA), text preprocessing, and building machine learning models.

## Key Features
- Data preprocessing for text cleaning, including removal of HTML tags, URLs, and stopwords.
- Exploratory data analysis to visualize sentiment distributions and word counts.
- Sentiment classification using two neural network models with different optimizers (RMSProp and Adam).
- Word cloud visualizations for frequent words in positive and negative reviews.

## Libraries Used
- `nltk`
- `pandas`
- `matplotlib`
- `seaborn`
- `plotly`
- `wordcloud`
- `sklearn`
- `keras`
- `collections`

## Project Workflow

### 1. Data Loading and Exploration
- Loaded the IMDB Movie Reviews dataset.
- Performed exploratory data analysis to understand sentiment distribution and review characteristics.

### 2. Data Preprocessing
- Cleaned text data by removing noise such as HTML tags, URLs, and special characters.
- Tokenized and stemmed the text for normalization.
- Removed duplicate reviews to ensure data uniqueness.

### 3. Exploratory Data Analysis (EDA)
- Visualized the distribution of sentiments (positive vs. negative).
- Created word clouds for positive and negative reviews.
- Analyzed the most frequent words in each sentiment category.

### 4. Text Vectorization
- Transformed text data into numerical format using TF-IDF vectorization.

### 5. Splitting the Dataset
- Split the dataset into training (70%) and testing (30%) subsets.

### 6. Neural Network Models
- **Model 1**: Built using RMSProp optimizer.
- **Model 2**: Built using Adam optimizer.
- Evaluated both models on the test set and compared performance.

## Results
- Both models were trained on subsampled data to optimize performance.
- Test accuracy and loss were calculated for each model.
- Training performance was visualized using loss and accuracy plots.

## Visualizations
- Distribution of word counts in reviews.
- Word clouds for the most frequent words in positive and negative reviews.
- Bar plots showing the most common words in each sentiment category.

## How to Run the Code
1. Install the required libraries: `pip install -r requirements.txt`.
2. Download the dataset and place it in the project directory.
3. Run the notebook or script to execute the analysis.

## Dataset
- **Source**: IMDB Movie Reviews dataset.
- The dataset contains two columns:
  - `review`: Text of the review.
  - `sentiment`: Sentiment label (positive or negative).
