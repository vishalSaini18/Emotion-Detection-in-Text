# Emotion Detection in Text

## Project Description
This project focuses on building a multi-class emotion detection system using Natural Language Processing (NLP) and deep learning techniques. The system classifies textual input into different emotional categories such as joy, sadness, anger, fear, love, and surprise.

The objective is to automatically understand human emotions from text data and demonstrate the application of deep learning models for complex NLP classification tasks.

## Dataset
- Source: Kaggle Emotion Dataset  
- Total Samples: ~20,000 labeled text instances  
- Classes: joy, sadness, anger, fear, love, surprise  

## Methodology
The project follows the standard NLP pipeline:
1. Text cleaning and normalization  
2. Tokenization and padding  
3. Feature extraction using word embeddings  
4. Training deep learning models for classification  

## Models Used
- BiLSTM with pre-trained embeddings (GloVe)  
- Transformer-based model (BERT fine-tuned)

## Performance
- Test Accuracy: ~87%  
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score  

## Tech Stack
- Python  
- TensorFlow / PyTorch  
- HuggingFace Transformers  
- NLTK / SpaCy  
- Scikit-learn  
- Pandas, NumPy  

## Repository Structure
emotion-detection-in-text/
│
├── data/ # Dataset files
├── notebooks/ # Jupyter notebooks
├── models/ # Saved trained models
├── preprocessing.py # Text preprocessing script
├── train.py # Training script
├── evaluate.py # Evaluation script
├── requirements.txt # Dependencies
└── README.md # Documentation
