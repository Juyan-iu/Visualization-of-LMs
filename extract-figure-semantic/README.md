# Semantic Extraction from Figure Captions
This directory contains Python scripts designed to analyze what is being visualized in figures and why, based on their captions.

## 1. Extraction via GPT-4o API
We utilize the GPT-4o API to perform semantic analysis on figure captions. The model is prompted to identify and extract core phrases that define:

What: The specific data or components shown in the figure.

Why: The underlying purpose or intent of the visualization (e.g., comparison, distribution, correlation).

## 2. Clustering and Labeling
Once the semantic phrases are extracted, the following steps are performed:

Phrase Embedding: Converting extracted text into high-dimensional vectors.

Clustering: Grouping similar "What" and "Why" concepts using clustering algorithms.

Label Assignment: Assigning representative labels to each cluster to categorize the visualization patterns across the dataset.
