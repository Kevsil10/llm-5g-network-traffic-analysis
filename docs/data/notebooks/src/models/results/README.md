# Comparative Study of Large Language Models for Intrusion Detection in 5G Networks

## Overview

This project presents a comparative study of Large Language Models (LLMs) applied to intrusion detection in 5G networks. The research evaluates **BERT, RoBERTa, and GPT-2** using the UNSW-NB15 dataset to investigate their capabilities in distinguishing normal network traffic from malicious activity.

The project follows a quantitative and experimental methodology, using model fine-tuning and classification metrics to compare performance.

## Research Objectives

- Evaluate BERT, RoBERTa, and GPT-2 for network intrusion detection.
- Analyze their ability to classify normal and malicious network traffic.
- Compare model performance using Accuracy, Precision, Recall, and F1-score.
- Explore the application of transformer-based language models to cybersecurity and 5G network traffic analysis.

## Dataset

**UNSW-NB15** was used to evaluate the models. The dataset contains normal network traffic and multiple categories of attacks and is used in this study as the basis for the intrusion detection experiments.

## Models Evaluated

| Model | Description |
|---|---|
| BERT | Transformer-based language model evaluated for intrusion detection. |
| RoBERTa | Optimized BERT-based architecture evaluated for traffic classification. |
| GPT-2 | Autoregressive language model adapted for network traffic classification. |

## Evaluation Metrics

The models were evaluated using the following metrics:

- **Accuracy:** Overall proportion of correct predictions.
- **Precision:** Proportion of predicted attacks that were actual attacks.
- **Recall:** Proportion of actual attacks correctly detected.
- **F1-score:** Harmonic mean of precision and recall.

## Key Findings

The thesis reports that **RoBERTa achieved the strongest overall performance** among the evaluated approaches, with an F1-score of approximately 0.80 and precision of approximately 0.81 for the attack class.

The GPT-2 experiment, evaluated on a sample of 5,000 records, reported an accuracy of approximately 0.77.

These results reflect the experiments documented in the thesis and should be interpreted within the dataset, preprocessing, and evaluation conditions used in the study.

## Technologies

- Python
- PyTorch
- TensorFlow
- Hugging Face Transformers
- Tokenizers
- Pandas
- Scikit-learn
- Matplotlib and Seaborn
- Jupyter Notebook
- Google Colab
- Visual Studio Code

## Repository Structure

```text
llm-5g-network-traffic-analysis/
├── data/        # Dataset documentation and data access instructions
├── docs/        # Thesis and research documentation
├── models/      # Model information and saved artifacts, if available
├── notebooks/   # Experimental notebooks
├── results/     # Evaluation results, tables, and figures
├── src/         # Source code
└── README.md    # Project overview
```

## Future Work

Potential extensions identified in the thesis include evaluating newer language models, expanding the datasets and attack categories, improving explainability, and exploring real-time intrusion detection.

## Author

**Ing. Kevin Francisco Silva Castro**

Telematics Engineering | Big Data | Cloud Computing | Network Security

---

*This repository documents a research project developed as part of a Master's thesis on the application of large language models to intrusion detection in 5G networks.*
