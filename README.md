# Semantic Similarity Using BERT

This project implements a lightweight NLP system that predicts semantic similarity between two sentences using fine-tuned BERT models.
The model outputs a score between 0 (unrelated) and 5 (highly similar).





# Model Info

| Model             |          Dataset | Dev. Correlation |
|-------------------|------------------|------------------|
| Web STS BERT      | STS-B            |     0.893        |
| Clinical STS BERT | MED-STS          |     0.854        |


# Project Structure
semantic-similarity-using-bert/
│
├── semantic_text_similarity/
├── requirements.txt
└── README.md



# Notes

GPU gives significantly faster predictions.
Model files are cached in ~/.cache/torch/semantic_text_similarity/.

# Acknowledgment

This project uses publicly available fine-tuned BERT models adapted for real-world semantic similarity tasks.
