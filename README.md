# 🧠 LLM-Based Medical Chatbot 

Fine-tuned an open-source LLM (**Deepseek Carbon**) on medical datasets to create an AI-powered medical consultant capable of reasoning through complex clinical cases.

## Project Overview

* Fine-tune LLMs using domain-specific data
* Apply reasoning models for medical diagnostics
* Use free tools for scalable training and deployment

## 🧰 Tech Stack

* **Model**: Deepseek Carbon (open-source reasoning LLM)
* **Fine-tuning**: LoRA, tokenization, quantization
* **Tools**: Google Colab, Kaggle Notebooks, Hugging Face
* **Frameworks**: PyTorch, Weights & Biases (W\&B)

## 📂 Features

* Chain-of-thought reasoning on patient symptoms
* Domain-specific accuracy via custom datasets
* Lightweight, cloud-compatible deployment

## 📊 Experiment Tracking

All model training and evaluations were tracked using **Weights & Biases**, including:

* Hyperparameters
* Fine-tuning iterations
* Performance metrics

## 💻 Getting Started

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/ai-doctor-3.0.git
   ```

2. Set up your environment (e.g., in Colab):

   ```bash
   pip install -r requirements.txt
   ```

3. Launch training with:

   ```bash
   python train.py
   ```
