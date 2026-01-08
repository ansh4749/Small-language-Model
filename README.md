Small Language Model (SLM) – Built From Scratch

![SLM Banner](https://img.shields.io/badge/Status-Active-brightgreen)

 Overview

This repository contains a **Small Language Model (SLM)** developed entirely from scratch. The model is designed for **text generation, completion, and understanding**, showcasing a simplified yet functional implementation of a transformer-based language model.  

Unlike pre-built libraries or pretrained models, this project demonstrates the core mechanics of language modeling, including **tokenization, embedding layers, attention mechanisms, and training loops**. The model is trained on the **Tiny Stories dataset from Hugging Face**, a compact dataset ideal for experimenting with story generation.

---

## Features

- Transformer-based architecture implemented from scratch
- Custom tokenizer for text processing
- Training from scratch on the **Tiny Stories dataset**
- Lightweight and efficient for experimentation
- Text generation and completion capabilities
- Easy to extend for advanced NLP tasks

---

## Project Structure

├── data/ # Tiny Stories dataset files
├── src/ # Source code for model, training, and evaluation
├── notebooks/ # Jupyter notebooks for experiments and demos
├── models/ # Saved checkpoints of trained models
├── README.md


## Key Highlights

Trained entirely on the Tiny Stories dataset from Hugging Face

Everything is implemented from scratch — no external high-level transformer libraries used

Provides a clear understanding of the inner workings of a language model

Lightweight enough to run on a personal machine for experimentation


## Future Improvements

Support for larger datasets and longer sequences

Optimization using mixed precision and gradient checkpointing

Integration with token embeddings from pretrained models for better performance

Advanced fine-tuning capabilities


## References & Inspirations


"Attention Is All You Need" – Vaswani et al., 2017

Hugging Face Transformers Documentation (for concepts, not code)

Tiny Stories dataset: https://huggingface.co/datasets/tiny-stories

Various NLP tutorials and papers on building language models from scratch


## License

This project is licensed under the MIT License – see the LICENSE
 file for details
