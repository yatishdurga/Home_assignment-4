# 🧠 NLP Mini Project – Preprocessing, NER, Attention, and Sentiment Analysis

This project contains implementations of four foundational Natural Language Processing (NLP) tasks using Python and popular libraries like NLTK, spaCy, NumPy, and HuggingFace Transformers. Each task demonstrates a different aspect of modern NLP pipelines.

---

## 📌 Table of Contents
- [Q1: NLP Preprocessing Pipeline](#q1-nlp-preprocessing-pipeline)
- [Q2: Named Entity Recognition (NER)](#q2-named-entity-recognition-ner)
- [Q3: Scaled Dot-Product Attention](#q3-scaled-dot-product-attention)
- [Q4: Sentiment Analysis with Transformers](#q4-sentiment-analysis-with-transformers)
- [Short Answer Questions](#short-answer-questions)

---

## ✅ Q1: NLP Preprocessing Pipeline

**Tools Used:** `nltk`

**Task:**  
Perform NLP preprocessing including:
1. Tokenization
2. Stopword Removal
3. Stemming

**Input Sentence:**



**Sample Output:**
- Original Tokens  
- Tokens without stopwords  
- Stemmed words

**Install Dependencies:**
```bash
pip install nltk


## ✅ Q2: Named Entity Recognition (NER) with spaCy

**Tools Used:** spaCy

**Task:**  
Use a pre-trained spaCy model to extract named entities along with their labels and character positions.

**Input Sentence:**  
"Barack Obama served as the 44th President of the United States and won the Nobel Peace Prize in 2009."

**Sample Output:**  
- Named entities such as:
  - `Barack Obama` → `PERSON`
  - `2009` → `DATE`
  - `the United States` → `GPE`
- Character start and end positions

**Install Dependencies:**
```bash
pip install spacy
python -m spacy download en_core_web_sm


Q3: Scaled Dot-Product Attention
Tools Used: numpy, scipy

Task:
Implement the scaled dot-product attention mechanism:

Compute Q × Kᵀ

Scale by √d

Apply softmax

Multiply by V


Q = [[1, 0, 1, 0], [0, 1, 0, 1]]
K = [[1, 0, 1, 0], [0, 1, 0, 1]]
V = [[1, 2, 3, 4], [5, 6, 7, 8]]

Q4: Sentiment Analysis with Transformers
Tools Used: transformers (HuggingFace)

Task:
Use a pre-trained pipeline to perform sentiment analysis on a given sentence.

Input Sentence:
"Despite the high price, the performance of the new MacBook is outstanding."

Output:

Sentiment label (e.g., POSITIVE)

Confidence score (e.g., 0.9991)




