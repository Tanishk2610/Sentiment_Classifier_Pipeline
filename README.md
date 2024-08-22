BERT, which stands for Bidirectional Encoder Representations from Transformers, is a state-of-the-art language model developed by researchers at Google AI Language in 2018. It has significantly advanced the field of natural language processing (NLP) by enabling machines to understand the context of words in a sentence more effectively than previous models.

Sentiment Classification Pipeline using Marathi BERT Model
This repository contains a Sentiment Classification Pipeline built using a Transfer Learning approach with a BERT-based model fine-tuned specifically for the Marathi language.

Model Overview
Base Model: The pipeline leverages the l3cube-pune/marathi-roberta model, a BERT-based transformer model pre-trained on Marathi text data.
Transfer Learning: I employed Transfer Learning to adapt this pre-trained transformer model. By fine-tuning it on a custom dataset tailored for sentiment classification, the model is better equipped to accurately predict sentiment in Marathi text.
Sentiment Classification: The fine-tuned model is integrated into a pipeline that detects Marathi text input, classifies its sentiment, and outputs a sentiment score and label in Marathi.
Features
Language Detection: Automatically detects whether the input text is in Marathi.
Sentiment Analysis: Provides a sentiment score and the corresponding label for Marathi text.
Custom Fine-Tuning: Fine-tuning on a specific dataset enhances the model's performance in classifying sentiments accurately for Marathi.
