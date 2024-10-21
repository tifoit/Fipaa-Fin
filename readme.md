# Fipaa-Fin: Financial Text Analysis with Large Language Models

[![GitHub license](https://img.shields.io/github/license/tifoit/Fipaa-Fin)](https://github.com/tifoit/Fipaa-Fin/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/tifoit/Fipaa-Fin)](https://github.com/tifoit/Fipaa-Fin/issues)
[![GitHub stars](https://img.shields.io/github/stars/tifoit/Fipaa-Fin)](https://github.com/tifoit/Fipaa-Fin/stargazers)

This repository contains the source code and dataset for the research paper titled "Interpretation of textual information in annual reports of listed companies -based on a fine-tuned large language model". The study focuses on the textual information embedded in annual reports of publicly listed companies in the food and beverage sector, exploring its impact on financial performance.

## Key Features

- **Fine-tuned Large Language Model (LLM)**: Fipaa-Fin, a model specifically designed for analyzing textual disclosures in financial reports.
- **Open-source Dataset (FFM-findata)**: A dataset based on annual report data used for training and testing the model.
- **Advanced Text Mining Techniques**: Utilizes chain-of-thought reasoning and prompt engineering to create a unique multi-round dialogue dataset for financial analysis.

## Getting Started

To get started with Fipaa-Fin, follow these steps:

1. **Prerequisites**:
   - Python 3.8 or later
   - PyTorch 1.10 or later
   - Transformers library by Hugging Face

2. **Installation**:
   Clone the repository and install the required packages:
   ```bash
   git clone https://github.com/tifoit/Fipaa-Fin.git
   cd Fipaa-Fin
   pip install -r requirements.txt

3. **Data Preparation**:
   The dataset used in this study is available upon request. Please refer to the "Data Availability" section in the paper for details on how to request access.

4.**Model Training**:
   Run the training script with the prepared dataset:
   ```bash
   python train.py --data_path /path/to/your/dataset

5.**Model Inference**:
   Use the fine-tuned model for inference on new data:
   ```bash
   python infer.py --model_path /path/to/finetuned/model


## Documentation
- **Model Details**: The models directory contains the code for the Fipaa-Fin model and other related modules.
- **Dataset Structure**: The data directory includes the structure and examples of the dataset used in this study.
- **Training Scripts**: The training directory contains scripts for training the model.
- **Inference Scripts**: The inference directory contains scripts for using the trained model for predictions.




