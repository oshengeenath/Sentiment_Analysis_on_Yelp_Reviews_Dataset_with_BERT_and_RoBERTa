# Sentiment Analysis on Yelp Reviews with BERT and RoBERTa

## Project Overview
This repository contains the code and documentation for performing sentiment analysis on Yelp reviews using two state-of-the-art models: Hugging Face's bert-base-multilingual-uncased and cardiffnlp/twitter-roberta-base-sentiment-latest. The project aims to compare these models' effectiveness in analyzing sentiments expressed in Yelp reviews.

### Models Used
- **BERT Multilingual Uncased**: A model capable of understanding multiple languages, ideal for the diverse linguistic nature of Yelp reviews.
- **Twitter RoBERTa**: Specially fine-tuned for sentiment analysis, this model excels in understanding the nuances of English-language sentiments.

## Getting Started

### Prerequisites

### Installation
1. Clone the repository:
   ```bash
   git clone [repository URL]
   ```
2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Data Preparation**:
2. **Model Training and Evaluation**:
   - To train the BERT model: `python train_bert.py`
   - To train the RoBERTa model: `python train_roberta.py`
3. **Sentiment Analysis**:
   - Run `python analyze_sentiments.py` to start the sentiment analysis process.
   - Results will be saved in the `results/` directory.

## Acknowledgements
- Hugging Face for the transformer models.
- CardiffNLP for the Twitter RoBERTa model.
- Yelp for the dataset.
