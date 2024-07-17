# Emotion Analysis in Conversations using NLP

This project implements and compares different models for emotion analysis and prediction in conversational data using Natural Language Processing techniques.

## Tasks

### Task 1: Emotion Classification

#### Model 1: BERT
- Accuracy: 0.9583
- F1-Score: 0.9584

#### Model 2: Graph Convolutional Networks with GloVe Encoding
- Accuracy: 0.7933
- F1-Score: 0.7288

### Task 2: Emotional Flip Detection

#### Model 1: BERT
- Accuracy: 0.8482
- F1-Score: 0.7785

#### Model 2: Custom LSTM Architecture
- Accuracy: 0.8438
- Macro F1-Score: 0.63
- Weighted F1-Score: 0.83

## Model Architectures

### BERT (Bidirectional Encoder Representations from Transformers)
- Used for both tasks
- Leverages pre-trained language understanding
- Fine-tuned for specific classification tasks

### Graph Convolutional Networks (GCN)
- Used for Task 1
- Utilizes graph structure to represent conversations
- Incorporates GloVe word embeddings

### Custom LSTM Architecture
- Used for Task 2
- Combines utterance embeddings with speaker and emotion data
- Processes sequential data to predict emotional flips

## Key Findings

- BERT outperformed GCN in Task 1 due to its contextual understanding and transfer learning capabilities.
- In Task 2, the custom LSTM model performed slightly better than BERT, likely due to its ability to incorporate speaker and emotion data alongside utterances.

## Contributors

1. Sanskar Ranjan
2. Jeremiah Rokhum
3. Saumil Lakra
4. Vishal Singh

## Future Work

- Explore additional pre-trained models and architectures
- Incorporate more contextual features to improve performance
- Investigate the impact of different embedding techniques on model performance

## References

[Add relevant references here]
