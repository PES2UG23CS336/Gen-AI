# Data Anonymizer using NER

This project implements a simple data anonymization system using a pre-trained BERT-based Named Entity Recognition model from Hugging Face.

## Features
- Detects organization and location entities
- Replaces sensitive data with anonymized labels
- Fully CPU-based, no training required

## Model
dbmdz/bert-large-cased-finetuned-conll03-english

## Example
Input:
The contract was awarded to AlphaTech Solutions in Singapore.

Output:
The contract was awarded to [ORG] in [LOC].
