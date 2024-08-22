# Sentiment Classification Pipeline using Marathi BERT Model

This repository contains a Sentiment Classification Pipeline built using a Transfer Learning approach with a BERT-based model fine-tuned specifically for the Marathi language.

## Model Overview
**Base Model:** The pipeline leverages the [l3cube-pune/marathi-roberta](https://https://huggingface.co/l3cube-pune/marathi-roberta), a BERT-based transformer model pre-trained on Marathi text data.

**Transfer Learning:** I employed Transfer Learning to adapt this pre-trained transformer model. By fine-tuning it on a custom dataset tailored for sentiment classification, the model is better equipped to accurately predict sentiment in Marathi text.

**Sentiment Classification:** The fine-tuned model is integrated into a pipeline that detects Marathi text input, classifies its sentiment, and outputs a sentiment score and label in Marathi.
Features

**Language Detection:** Automatically detects whether the input text is in Marathi.
**Sentiment Analysis:** Provides a sentiment score and the corresponding label for Marathi text.

**Custom Fine-Tuning:** Fine-tuning on a specific dataset enhances the model's performance in classifying sentiments accurately for Marathi.



## Future Improvements

To further enhance the performance of the Sentiment Classification Pipeline, the following steps will be implemented:

### Data Preprocessing:

**Duplicate Removal:** The dataset will undergo additional preprocessing to identify and remove duplicate entries, ensuring cleaner and more reliable data for training.
**Class Balancing:** The dataset will be balanced so that each class has a similar representation. This step is crucial to avoid bias towards any particular sentiment during classification.
### Class Consolidation:

To improve generalization and model performance on unseen data, similar categories will be merged. For instance, the existing categories "angry," "negative,angry," and "Negative" will be consolidated into a single "Negative" class. This will help in creating a more balanced dataset and a more effective model for sentiment classification.

These enhancements will contribute to better model accuracy, particularly when dealing with varied and previously unseen Marathi text data.
