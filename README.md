# AI-Driven Candidate Matching Tool for Recruiters

This project uses NLP and machine learning to automatically match resumes to a job description and rank candidates based on their relevance.

---

### 🔍 Why I Built This

As a Business Analyst with a background in recruitment, I wanted to automate the manual screening process using AI to streamline candidate selection. This project simulates how modern NLP techniques can be applied to evaluate and rank resumes efficiently and objectively.

---

### ⚙️ How It Works

* **TF-IDF Vectorization**: Converts resumes and job descriptions into numerical vectors based on word frequency
* **Cosine Similarity**: Measures how closely each resume matches the job description
* **Ranking Output**: Produces a ranked list of candidates based on their match score

---

### 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* TF-IDF
* Cosine Similarity

---

### 📈 Sample Output

| Candidate | Match Score (%) |
| --------- | --------------- |
| Resume\_1 | 35.02           |
| Resume\_3 | 35.02           |
| Resume\_2 | 0.00            |

> Resume\_1 and Resume\_3 both scored equally, showing strong alignment with the job description (Python, Flask, ML). Resume\_2 scored 0.00% due to lack of relevant terms.

---

### 🛋️ Installation Guide

To set up the environment:

```bash
pip install pandas scikit-learn nltk
```

---

### ▶️ Usage Instructions

1. Clone the repository or download the notebook.
2. Open `candidate_matching_tool.ipynb` in Jupyter or Google Colab.
3. Replace the `job_description` and `resumes` dictionary with your actual data.
4. Run all cells to view results.

---

### 📁 Sample Data

Included sample data is located directly in the notebook as inline text. For your own usage, replace:

```python
job_description = "..."
resumes = {"Resume_1": "...", "Resume_2": "..."}
```

with your own content.

---

### 🔄 Code Modularity

All logic is encapsulated in a reusable function `match_resumes(job_desc, resumes_dict)` to ensure clean structure and flexibility.

#### Error Handling

Basic checks and validation can be implemented to handle empty inputs or malformed resumes.

---

### 🧠 Algorithm Explanation

* **TF-IDF** was chosen to numerically represent text data by highlighting important but less frequent words.
* **Cosine Similarity** is effective in comparing high-dimensional text vectors without needing document length normalization.
* **Limitation**: It doesn't understand context or synonyms — future versions could use transformers or embeddings.

---

### 🌟 Future Enhancements

* Resume and job description upload support (PDF, DOCX)
* Enhanced NLP with BERT/transformer-based models
* User interface using Streamlit or Flask
* Integration with HR databases

---

### 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

### 🌐 Live Demo (Coming Soon)

We plan to deploy this as a Streamlit web app to enable recruiters to upload job descriptions and resumes and instantly view match rankings.

---

**⭐️ If you like this project, give it a star!**
