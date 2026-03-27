# NLP Preprocessing Engine (Task 1 – Generative AI Internship)

## Overview

This project implements a robust Natural Language Processing (NLP) preprocessing pipeline designed to handle noisy, real-world text data. The goal is to transform unstructured text into clean, meaningful tokens suitable for machine learning models.

---

## Objectives

* Build a scalable and reusable NLP preprocessing function
* Handle noisy inputs such as emojis, URLs, numbers, and repeated characters
* Perform token-level analysis and frequency analysis
* Ensure robustness with proper error handling

---

## Features

### Text Preprocessing

* Converts text to lowercase
* Removes URLs and email patterns
* Removes numbers and special characters
* Handles repeated characters (e.g., "soooo" → "soo")
* Removes extra spaces
* Tokenizes text into words
* Removes short tokens (length ≤ 2), except "no" and "not"

### Token Analytics

* Total number of tokens
* Number of unique tokens
* Average token length per sentence

### Frequency Analysis

* Top 10 most frequent words
* Top 5 least frequent words

### Full Pipeline

* Modular pipeline function to process multiple sentences efficiently

### Error Handling

* Handles edge cases such as:

  * Empty input
  * Only emojis
  * Only numbers
  * Invalid inputs (None)

---

## Technologies Used

* Python
* NLTK (Natural Language Toolkit)
* Regular Expressions (re module)
* Collections (Counter)

---


## Sample Input

```
"I absolutely looooved this product 😍😍"
```

## Sample Output

```
Tokens: ['absolutely', 'looved', 'this', 'product']
Cleaned Sentence: absolutely looved this product
```

---

## Key Learnings

* Importance of text normalization in NLP
* Handling noisy and unstructured data
* Writing modular and reusable Python code
* Performing basic NLP analytics

---

## Conclusion

A complete NLP preprocessing engine was developed to clean and structure raw text data. The pipeline is modular, efficient, and suitable for real-world applications such as sentiment analysis and text classification.

---

## Author

Pavanchandra Devang L

---
