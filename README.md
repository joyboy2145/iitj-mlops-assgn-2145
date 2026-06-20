# MLOps Pipeline: Hugging Face Fine-Tuning & Experiment Tracking

A complete MLOps pipeline that converts a text classification task into a production-ready, traceable workflow. This project fine-tunes a DistilBERT model on the UCSD Goodreads book reviews dataset to predict book genres, using Kaggle for GPU training, Weights & Biases for experiment tracking, and Hugging Face Hub for model deployment.

## Setup Instructions

### 1. Prerequisites
Ensure you have Python 3.8+ installed along with the required API accounts:
* A free [Kaggle Account](https://www.kaggle.com) (for access to free T4 GPUs)
* A free [Weights & Biases Account](https://wandb.ai) (for experiment tracking)
* A free [Hugging Face Account](https://huggingface.co) (for model deployment)

### 2. Local Installation
Clone this repository and install the dependencies:
```bash
git clone [https://github.com/your-username/mlops-assignment2-pipeline.git](https://github.com/your-username/mlops-assignment2-pipeline.git)
cd mlops-assignment2-pipeline
run the jupyter notebook