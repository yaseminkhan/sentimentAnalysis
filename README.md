# Sentiment Analysis with VADER, RoBERTa, and Transformers

## Project Overview

This project performs sentiment analysis on the IMDB Movie Reviews dataset using three different models: VADER, RoBERTa, and a Transformer-based model from Hugging Face. The goal is to compare the performance of these models in predicting sentiment (positive or negative).

## Dataset

The dataset used is the **IMDB Movie Reviews** dataset, which is balanced with 25,000 positive and 25,000 negative reviews. This dataset is commonly used as a benchmark for sentiment classification tasks.

### Citation
```plaintext
@InProceedings{maas-EtAl:2011:ACL-HLT2011,
  author    = {Maas, Andrew L.  and  Daly, Raymond E.  and  Pham, Peter T.  and  Huang, Dan  and  Ng, Andrew Y.  and  Potts, Christopher},
  title     = {Learning Word Vectors for Sentiment Analysis},
  booktitle = {Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies},
  month     = {June},
  year      = {2011},
  address   = {Portland, Oregon, USA},
  publisher = {Association for Computational Linguistics},
  pages     = {142--150},
  url       = {http://www.aclweb.org/anthology/P11-1015}
}
```

## Models

- **VADER**: A lexicon and rule-based sentiment analysis tool specifically attuned to social media texts.
- **RoBERTa**: A transformer-based model fine-tuned for sentiment analysis.
- **Hugging Face Transformers**: Another transformer model from the Hugging Face library, known for its robust NLP capabilities.

## How to Run

This project is designed to be run in [Google Colab](https://colab.research.google.com/). Open the `sentimentAnalysis.ipynb` file in Colab to execute the analysis. Make sure the necessary libraries are installed, which can be done directly within Colab.