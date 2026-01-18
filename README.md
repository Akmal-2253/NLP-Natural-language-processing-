# Learn NLP Practically with Python

This repository is designed to help learners **understand and practice Natural Language Processing (NLP) concepts using Python**. It is not just about code—it focuses on **how things work in practice**, step by step.

## What You Will Learn

Through this project, you will get hands-on experience with:

### 1. Tokenization
- **Word Tokenization:** Breaking text into individual words to analyze them.  
- **Sentence Tokenization:** Splitting text into sentences to handle large texts in smaller chunks.  
*Practical Tip:* Tokenization is the first step in almost all NLP tasks.

### 2. Stop Words Removal
- Removing common words like "the", "is", "and", which do not carry important meaning.  
- Helps focus on the **meaningful words** in your text.  

### 3. Stemming
- Reduces words to their root form (e.g., "running" → "run").  
- Libraries used: **PorterStemmer, LancasterStemmer, SnowballStemmer, RegexpStemmer**.  
*Practical Tip:* Useful for search engines or text classification where exact forms are not needed.

### 4. Lemmatization
- Converts words to their **dictionary/base form** considering their part-of-speech.  
- Example: "mice" → "mouse", "studying" → "study".  
*Difference from stemming:* Lemmatization is more accurate and linguistically meaningful.

### 5. Part-of-Speech (POS) Tagging
- Assigns a **grammatical role** to each word (noun, verb, adjective, etc.).  
- Helps in understanding sentence structure and meaning.

### 6. N-Grams
- **Bigrams & Trigrams:** Groups of 2 or 3 consecutive words.  
- Helps analyze patterns, phrases, and context in text.

### 7. Count Vectorizer
- Converts text into **numerical frequency vectors**.  
- Vocabulary is built from all unique words in your dataset.  
*Practical Tip:* Used as input for machine learning models.

### 8. Word Sense Disambiguation
- Finds the **correct meaning of a word in context** using algorithms like Lesk.  
- Example: "order" can mean a sequence, a command, or a society depending on context.

---

## How to Use

1. Open the notebook `NLPpractice.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Run each section step by step to see how the text is processed.
3. Modify the text to try **different examples** and understand how NLP handles them.

---

## Why This Project is Useful

- Makes you **think about language practically**.
- Helps understand **how NLP tools work under the hood**, not just copy-paste.
- Prepares you for more advanced tasks like **text classification, sentiment analysis, or chatbot development**.

---

## Author

**Akmal Sultan** – Exploring NLP concepts and practical applications in Python

