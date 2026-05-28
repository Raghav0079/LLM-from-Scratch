# LLM from Scratch

A collection of Jupyter notebooks that build core large language model (LLM) concepts from the ground up. This repo follows the learning path in the YouTube playlist below and mirrors each step as a hands-on notebook.

Playlist: https://www.youtube.com/playlist?list=PLPTV0NXA_ZSgsLAr8YCgCwhPIJNNtexWu

## What is inside

- Tokenization and byte pair encoding
- Embeddings (token, position, vector)
- Attention (causal, trainable self-attention)
- GPT-style architecture walkthrough
- Data preprocessing and input-output pairs
- Pretraining, loss, and validation
- Decoding strategies
- Model weights loading and utilities

## Notebooks

- Tokenizer.ipynb
- Byte_Pair_Encoding.ipynb
- Token_Embeddings.ipynb
- Position Embeddings.ipynb
- Vector_embedding.ipynb
- Attention mechanism.ipynb
- Causal Attention.ipynb
- Trainable Self Attention.ipynb
- LLM Architecture.ipynb
- LLM_Data_Preprocessing.ipynb
- Data_Loader_Input_Output_Pairs.ipynb
- LLM Pretraining.ipynb
- LLM Loss function.ipynb
- LLM Training Validation Loss.ipynb
- LLM Decoding Strategies.ipynb
- Model_Weights_Loaded.ipynb
- Classification finetuning data loading.ipynb

## Getting started

1. Create and activate a Python environment.
2. Install the notebook dependencies you need (for example, PyTorch, NumPy, and Jupyter).
3. Open any notebook and run cells in order.

Example:

```bash
python -m venv .venv
. .venv/Scripts/activate
pip install jupyter torch numpy
jupyter notebook
