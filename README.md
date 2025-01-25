**Overview**

This repository explores techniques for Text Summarization, an essential task in natural language processing (NLP) that aims to generate concise and meaningful summaries from longer text documents. Text summarization can be applied in various domains such as news aggregation, legal document analysis, research articles, and more.

**The project implements two main approaches to summarization:**

- Extractive Summarization: Identifying and extracting key sentences from the text.
- Abstractive Summarization: Generating new sentences that summarize the main ideas in the text.

**Key Features**

**Extractive Summarization:**

  - Implementation using graph-based ranking algorithms such as TextRank.
  - Supports custom datasets for extractive summarization.

**Abstractive Summarization:**

  - Neural network-based models using Seq2Seq and Transformer architectures.
  - Pretrained models (e.g., BART, T5) for state-of-the-art results.

**Dataset Preparation:**

  - Scripts to preprocess and clean text datasets.
  - Supports multiple file formats such as .txt, .csv, and .json.

**Evaluation Metrics:**

  - Implementation of ROUGE and BLEU scores to assess summarization quality.
