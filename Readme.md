# Hotel Complaint Text Classification  

This project demonstrates a deep learning approach to automatically classify hotel customer complaints.  

---

## 🚀 How to Run the Notebook  

1. **Clone the Repository**  
   - Download the `Assignment.ipynb` and dataset files.  

2. **Setup Environment**  
   - The notebook is designed for **Google Colab**.  
   - Place the `GoogleNews-vectors-negative300.bin` file inside a folder named `nlp p-1` in your Google Drive (or update the path in the code).  

3. **Install Dependencies**  
   - The notebook installs required libraries automatically (e.g., `gensim`, `nltk`).  

4. **Run the Notebook**  
   - Execute all cells in order.  
   - The workflow includes preprocessing, model training, evaluation, and an interactive section for predicting new complaints.  

---

## 📚 Libraries Used  

- **pandas** → Data handling  
- **numpy** → Numerical operations  
- **torch** → Deep learning framework  
- **gensim** → Word2Vec embeddings  
- **scikit-learn** → Data splitting, label encoding, metrics  
- **nltk** → Text preprocessing (lemmatization, stopwords)  
- **re** → Regex-based text cleaning  

---

## ⚙️ Dependencies  

- **GPU** → Recommended for faster training  
- **Pre-trained Word2Vec** →  
  - Download [`GoogleNews-vectors-negative300.bin`](https://code.google.com/archive/p/word2vec/) (~1.6 GB)  
  - Place it in the correct Google Drive path (`nlp p-1`) or update the notebook path.  

---
