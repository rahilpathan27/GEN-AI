# Unit 1 – NLP Basics, Pre-Trained Models

This folder contains all work completed for **Unit 1: NLP Basics, Pre-Trained Models**.  
The unit focuses on understanding transformer architectures and applying Hugging Face pipelines to core NLP tasks.


---

## Unit1_Benchmark.ipynb (Phase 3 – Assessment)

This notebook contains benchmark experiments designed to test how different transformer architectures behave when forced to perform tasks they were **not designed for**.

### Models Used
- `bert-base-uncased` (Encoder-only)
- `roberta-base` (Encoder-only)
- `facebook/bart-base` (Encoder–Decoder)

### Experiments Performed
1. Text Generation  
2. Fill-Mask (Masked Language Modeling)  
3. Question Answering  

### Key Learnings
- Encoder-only models fail at text generation (expected behavior)
- BERT-style models excel at masked word prediction
- Question Answering requires task-specific fine-tuning
- Tokenizer compatibility (e.g., `[MASK]` vs `<mask>`) is critical

All observations are documented using structured tables with architecture-based explanations.

---

## Unit1_Project_Summarizer.ipynb (Phase 4 – Mini Project)

### Project Title
AI-Based News Article Summarizer using Transformer Models

### Problem Statement
News articles are often lengthy and time-consuming to read.  
This project aims to generate concise summaries using transformer-based summarization models.

### Model Used
- `sshleifer/distilbart-cnn-12-6`

### Why This Model
- Optimized for summarization tasks
- Faster and lighter than BART-large
- Suitable for CPU-based environments
- Officially recommended for Unit 1

### Features
- Accepts long-form news-style text
- Produces short, coherent summaries
- Demonstrates real-world use of encoder–decoder transformers

---

## Technologies Used
- Python 3
- Hugging Face Transformers
- PyTorch
- Jupyter Notebook

---

## 
Note
This repository is part of an academic hands-on module and is intended for learning and evaluation purposes.
