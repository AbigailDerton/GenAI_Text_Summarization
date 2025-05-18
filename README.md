# GenAI_Text_Summarization
Demonstration on how to use generative AI models for text summarization.

## Model Summary
[BART](https://www.google.com/url?q=https%3A%2F%2Farxiv.org%2Fabs%2F1910.13461) is a sequence-to-sequence transformer combining a bidirectional (BERT-style) encoder with an autoregressive (GPT-style) decoder. It is pre-trained by corrupting input text and learning to reconstruct it. BART is particularly strong at generation tasks like summarization and translation, and also effective for classification and question answering.

[TinyLlama](https://www.google.com/url?q=https%3A%2F%2Fhuggingface.co%2FTinyLlama%2FTinyLlama-1.1B-Chat-v1.0) is a compact, 1.1 billion-parameter model based on the LLaMA 2 architecture and tokenizer. Pre-trained on approximately 3 trillion tokens, TinyLlama is designed for efficiency and performs well on fundamental NLP tasks such as text generation and summarization.

## Files
The text_summarization.ipynb file demonstrates how to use generative AI models for text summarization. It employs BART, a large language model fine-tuned on the CNN/DailyMail dataset, and TinyLlama, a lightweight variant of LLaMA 2, to summarize a Reuters news article about pet adoption.
