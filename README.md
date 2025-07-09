# A Multimodal and Synthetic Data Approach to Classifying Informativeness of Crisis Social Media Information

Code base for Waseda University SILS Thesis by Sumiko Teng
This repository contains a series of exploratory notebooks analyzing crisis-related tweets classification using multimodal approaches (text and image). The project compares performance across original and synthetically augmented datasets using various modeling techniques, including CLIP, multimodal cross attention model, and other classifiers.

## Notebooks Overview
| Notebook                      | Description                                                                                                                                                            |
| ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `crisis_dsma.ipynb`           | Performs exploratory data analysis (EDA), preprocessing, and runs unimodal (text/image) and cross-attention multimodal models on the original dataset. |
| `clip_zero_shot_crisis.ipynb` | Uses CLIP for zero-shot classification on the original dataset to evaluate performance without fine-tuning.                                                    |
| `clip_classifier.ipynb`       | Extracts CLIP embeddings and applies a logistic regression classifier for evaluation on the original dataset.                                            |
| `syn_gen.ipynb`               | Generates synthetic crisis data (both text and image prompts) using large language models and stable diffusion image generation model.                                                  |
| `eda_crisis.ipynb`            | Runs EDA on the synthetically generated dataset to evaluate alignment with the original data.                                     |
| `syn_crisis_dsma.ipynb`       | Repeats the full analysis; EDA, preprocessing, and running unimodal and multimodal models on the synthetically augmented dataset.             |
