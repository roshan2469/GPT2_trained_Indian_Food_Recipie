# GPT-2 Fine-Tuned for Indian Recipe Generation
Overview

This project demonstrates domain-specific fine-tuning of GPT-2 for structured recipe generation focused on Indian cuisine. The model is trained on curated culinary data to generate coherent, culturally consistent, and well-structured recipes including ingredients, measurements, and cooking steps.

The objective is to showcase practical transfer learning using transformer-based architectures for niche content generation tasks.

Key Features

    -> Domain-adapted text generation
    
    -> Structured recipe formatting
    
    -> Ingredient-aware prompt completion
    
    -> Transfer learning on pretrained GPT-2
    
    -> End-to-end training and inference pipeline


Technical Stack

-> Python

-> PyTorch

-> Hugging Face Transformers

-> Tokenizers

-> Jupyter Notebook

Architecture

-> Base model: GPT-2 (pretrained transformer decoder)

-> Fine-tuning on formatted Indian recipe dataset

-> Causal Language Modeling objective

-> Prompt-based text generation

Training Pipeline

1. Dataset preprocessing and normalization

2. Tokenization and sequence formatting

3. Model loading from pretrained GPT-2

4. Fine-tuning using cross-entropy loss

5. Text generation via temperature sampling

Use Cases

-> AI-powered cooking assistants

-> Culinary content automation

-> Food-tech applications

-> Domain-specific LLM experimentation

Results

-> The model generates structured recipes including:

-> Dish titles

-> Ingredient lists

-> Sequential cooking instructions

-> Realistic spice combinations

Future Improvements

-> Larger dataset integration

-> Instruction tuning

-> Evaluation metrics (BLEU, ROUGE)

-> Deployment via API

    
