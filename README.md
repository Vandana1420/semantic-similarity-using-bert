# Semantic Similarity Using BERT

This project implements a lightweight NLP system that predicts semantic similarity between two sentences using fine-tuned BERT models.
The model outputs a score between 0 (unrelated) and 5 (highly similar).


# Features

Fine-tuned BERT models for similarity scoring
Simple Python API
CPU/GPU support
Batch prediction support


# Model Info

| Model             |          Dataset | Dev. Correlation |
|-------------------|------------------|------------------|
| Web STS BERT      | STS-B            |     0.893        |
| Clinical STS BERT | MED-STS          |     0.854        |


# Performance

Uses BERT encoder for rich semantic understanding
Optimized for batch inference
GPU acceleration available
Cached model downloads for faster reuse

# Notes

GPU gives significantly faster predictions.
Model files are cached in ~/.cache/torch/semantic_text_similarity/.

# Acknowledgment

This project uses publicly available fine-tuned BERT models adapted for real-world semantic similarity tasks.
