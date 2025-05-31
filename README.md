# ai-candidate-matching-tool
"AI tool to rank resumes against job descriptions using NLP and machine learning."
# AI-Driven Candidate Matching Tool for Recruiters

This project uses NLP and machine learning to automatically match resumes to a job description and rank candidates based on their relevance.

---

### 🔍 Why I Built This

As a Business Analyst with a background in recruitment, I wanted to automate the manual screening process using AI to streamline candidate selection. This project simulates how modern NLP techniques can be applied to evaluate and rank resumes efficiently and objectively.

---

### ⚙️ How It Works

- **TF-IDF Vectorization**: Converts resumes and job descriptions into numerical vectors based on word frequency
- **Cosine Similarity**: Measures how closely each resume matches the job description
- **Ranking Output**: Produces a ranked list of candidates based on their match score

---

### 🛠️ Technologies Used

- Python  
- Pandas  
- Scikit-learn  
- TF-IDF  
- Cosine Similarity

---

### 📈 Sample Output

| Candidate | Match Score (%) |
|-----------|-----------------|
| Resume_1  | 35.02           |
| Resume_3  | 35.02           |
| Resume_2  | 0.00            |

> Resume_1 and Resume_3 both scored equally, showing strong alignment with the job description (Python, Flask, ML). Resume_2 scored 0.00% due to lack of relevant terms.

---

### 🚀 How to Run

You can run this project in:
- **Jupyter Notebook**
- **Google Colab** (recommended for quick testing)

---

### 📁 Files

- `candidate_matching_tool.ipynb`: Main Python notebook
- `README.md`: Project documentation
- (Optional) `sample_resumes.txt`: Example resume snippets
- (Optional) `output.csv`: Match scores

---

### 🔗 Future Improvements

- Add support for PDF and DOCX parsing
- Integrate with Streamlit for live demo
- Add keyword weighting or custom scoring logic

---

**⭐️ If you like this project, give it a star!**
