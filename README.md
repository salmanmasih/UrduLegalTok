# UrduLegalTok

## Evaluating and Adapting Tokenizers for Low-Resource Legal NLP

UrduLegalTok is a practical learning and research project focused on understanding how tokenization affects Urdu legal text. The project examines tokenizer algorithms, multilingual token efficiency, Urdu Unicode normalization, custom tokenizer training, vocabulary adaptation, and legal-text integrity.

The project is being developed as part of a structured learning journey in language modeling, multilingual NLP and low-resource LLM adaptation.

## Project Objectives

- Implement the main ideas behind BPE and Unigram tokenization.
- Compare tokenization behavior across English and Urdu legal texts.
- Measure fragmentation, compression and cross-language token-cost differences.
- Study Urdu Unicode and orthographic variation.
- Train controlled Urdu–English tokenizers.
- Explore legal-domain vocabulary adaptation.
- Evaluate legal-term and fixed-context retention.

## Project Structure

| Module | Purpose |
|---|---|
| `01_foundations` | Unicode, UTF-8, BPE, Unigram, Viterbi and model inputs |
| `02_tokenizer_benchmark` | English–Urdu tokenizer comparison and token-tax analysis |
| `03_normalization` | Conservative Urdu Unicode normalisation |
| `04_custom_tokenizer` | Controlled BPE and Unigram tokenizer training |
| `05_vocabulary_adaptation` | Urdu legal vocabulary and embedding adaptation |
| `06_legal_evaluation` | Legal-term fragmentation and context-retention evaluation |
| `src` | Reusable Python source code |
| `tests` | Unit and integration tests |
| `data` | Demonstration text, legal terms and normalization examples |
| `results` | Generated experiment results |
| `figures` | Generated plots and visualisations |


## Scope

The initial version uses small, public or manually created examples for learning and reproducibility. Results from demonstration data will not be presented as general research findings about Urdu or pretrained language models.

## Licence

This project is released under the MIT License.
