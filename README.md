# AI Text Generation with DistilGPT2

This repository contains a simple Python script that uses a Pre-trained Transformer model to generate text completions.

## Overview
The script uses the [Hugging Face Transformers](https://huggingface.co/docs/transformers/index) library to load `distilgpt2`. This is a lightweight, faster version of GPT-2 that performs similarly while using fewer computational resources.

## Features
* **Text Generation:** Provides creative continuations for any text prompt.
* **Repetition Control:** Uses a `repetition_penalty` to ensure diverse output.
* **Batch Generation:** Configured to return multiple sequences for comparison.

## Getting Started

### Prerequisites
* Python 3.8+
* [PyTorch](https://pytorch.org/)

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
   cd YOUR_REPO_NAME
