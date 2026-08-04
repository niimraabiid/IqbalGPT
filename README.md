# IqbalGPT
 
A character-level GPT language model trained from scratch on the poetry of Allama Iqbal, built using Andrej Karpathy's nanoGPT framework.
 
## What it does
 
Generates Iqbal-style poetic text via autoregressive sampling. The model was trained entirely from scratch on a single work: **"The Secrets of the Self" (Asrár-i Khudí)**, R.A. Nicholson's 1920 English translation of Iqbal's original Persian philosophical poem — a public domain text sourced from Project Gutenberg.

## Model details
 
- Transformer architecture (nanoGPT), trained from scratch
- 4 layers, 4 attention heads, 256-dim embeddings, 256 block size, 0.2 dropout — sized down deliberately to suit the smaller single-source corpus
- Character-level tokenization
- Trained on Google Colab (T4 GPU)

## Data
 
- Source: [*The Secrets of the Self*](https://www.gutenberg.org/ebooks/57317), translated by Reynold A. Nicholson (Macmillan, 1920), via Project Gutenberg — public domain
- Original work: *Asrár-i Khudí* by Muhammad Iqbal (Lahore, 1915)
- 90/10 train/validation split

## A note on this project
 
This model is a small technical exercise in character-level language modeling — it is not, and could never be, a replacement for Allama Iqbal's actual words. Iqbal's poetry carries philosophical depth, spiritual weight, and linguistic mastery that no few-million-parameter model trained on a laptop or free-tier GPU could approach. This project exists to explore how transformers learn structure and style from text, using his work as a respectful case study — not to imitate or diminish it.
 
## Acknowledgments
 
- [nanoGPT](https://github.com/karpathy/nanoGPT) by Andrej Karpathy
- Text sourced via [Project Gutenberg](https://www.gutenberg.org)
 
