#  NLP Analysis of Pride and Prejudice (Chapters I–IV)

This project performs Natural Language Processing (NLP) analysis on the first four chapters of *Pride and Prejudice* by Jane Austen.

---

##  Objectives

- Text preprocessing (tokenization, normalization)
- Stopword removal
- Stemming (SnowballStemmer)
- Frequency distribution analysis
- Manual TF-IDF implementation
- Scikit-learn TF-IDF comparison
- WordCloud visualizations

---

##  Tools & Libraries

- Python
- NLTK
- Scikit-learn
- WordCloud
- Matplotlib
- NumPy

---

##  Key Techniques Applied

- Regex-based punctuation filtering
- Token normalization
- Term Frequency (TF)
- Inverse Document Frequency (IDF)
- Manual TF-IDF implementation
- Document-level analysis (chapter-wise)
- Visualization of weighted term importance

---

##  Project Structure

pride-prejudice-nlp-analysis/
- data/
  - pride_prejudice_ch1_to_ch4.txt
- notebooks/
  - PrideandPrejudiceNLPAnalysis.ipynb
- outputs/
  - wordcloud_frequency.png
  - tfidf_doc1.png
  - tfidf_doc2.png
  - tfidf_doc3.png
  - tfidf_doc4.png
  - tfidf_combined.png
- requirements.txt
- README.md

---

##  Methodology

1. Extracted Chapters I–IV from the original text and saved them as a separate `.txt` passage file.
2. Preprocessed text using:
   - Lowercasing
   - Strict punctuation removal (letters-only tokens)
   - Stopword removal
   - Short word filtering (length < 3)
   - Stemming (SnowballStemmer)
3. Computed word statistics:
   - Frequency distribution (Counter)
   - Total token occurrences and unique token types
   - Frequency brackets (hapax, 2–5, 6–20, etc.)
4. TF-IDF analysis across 4 documents (Chapters I–IV):
   - Scikit-learn TF-IDF
   - Manual TF-IDF using textbook formula
5. Generated visualizations:
   - Frequency-based wordcloud
   - TF-IDF wordcloud per chapter
   - Combined TF-IDF wordcloud (Ch1–Ch4)

---

##  How to Run

### Option A — Run in Google Colab
1. Upload the notebook and the passage `.txt`
2. Run cells from top to bottom

### Option B — Run locally
1. Install dependencies:

   pip install -r requirements.txt

2. Open the notebook:

   jupyter notebook notebooks/PrideandPrejudiceNLPAnalysis.ipynb

---

##  Outputs

The `outputs/` folder contains:
- Frequency WordCloud (after preprocessing)
- TF-IDF WordClouds for each chapter
- Combined TF-IDF WordCloud for Chapters I–IV

---

##  Author

MSc Big Data Analytics — NLP Coursework Project
