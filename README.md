## Project Description (≈350 words)

**Build AI Resume Analyzer Using Python, NLP & Streamlit** is an end-to-end machine learning project designed to automatically evaluate how well a candidate’s resume matches a given job description. The goal of this project is to demonstrate practical applications of Natural Language Processing (NLP) and Machine Learning techniques in real-world recruitment and HR analytics scenarios.

The application allows users to upload a resume in PDF format and paste a job description into a simple, interactive web interface built with Streamlit. Once submitted, the system extracts textual content from the resume, cleans and preprocesses the text using NLP techniques such as lowercasing, tokenization, and stopword removal, and then converts both the resume and job description into numerical representations using TF-IDF vectorization.

To quantify the similarity between the resume and the job description, the project employs Cosine Similarity, a widely used metric in information retrieval and text mining. The resulting similarity score is presented as a percentage, giving users an intuitive understanding of how closely their resume aligns with the job requirements. This helps job seekers identify gaps in their resumes and optimize them for specific roles, while also demonstrating how automated resume screening systems work behind the scenes.

In addition to similarity scoring, the project extracts important keywords from the job description using part-of-speech tagging to identify relevant nouns and adjectives. This feature highlights the most significant skills and terms expected by employers, further assisting users in tailoring their resumes effectively.

The project emphasizes clean code structure, modular design, and practical ML workflows, making it suitable for students, beginners in machine learning, and developers looking to build portfolio-ready AI projects. By combining Python, NLP libraries like NLTK, machine learning tools from scikit-learn, and an intuitive Streamlit UI, this project showcases how AI models can be integrated into user-friendly applications with real-world value.

---

# README.md

## Build AI Resume Analyzer Using Python, NLP & Streamlit

A machine learning–powered web application that analyzes resumes and job descriptions using Natural Language Processing (NLP) techniques and calculates a similarity score to measure job–resume compatibility.

---

## 🚀 Features

* Upload resumes in **PDF format**
* Paste any **job description** for analysis
* Text preprocessing using NLP techniques
* **TF-IDF Vectorization** for feature extraction
* **Cosine Similarity** for resume–job matching
* Keyword extraction using **POS tagging**
* Interactive and user-friendly **Streamlit UI**

---

## 🧠 Technologies Used

* **Python**
* **Streamlit** (Web Interface)
* **NLTK** (Tokenization, Stopwords, POS Tagging)
* **Scikit-learn** (TF-IDF, Cosine Similarity)
* **PyPDF2** (PDF Text Extraction)

---

## 📂 Project Structure

```
Resume Analyzer/
│
├── app.py              # Main Streamlit application
├── requirements.txt    # Project dependencies
├── README.md           # Project documentation
└── .venv/              # Virtual environment (optional)
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer
```

2. Create and activate a virtual environment (recommended):

```bash
python -m venv .venv
.venv\Scripts\activate   # On Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Download required NLTK resources:

```python
import nltk
nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
nltk.download('averaged_perceptron_tagger')
```

5. Run the application:

```bash
streamlit run app.py
```

---

## 📊 How It Works

1. Resume text is extracted from the uploaded PDF
2. Text is cleaned and preprocessed
3. Resume and job description are vectorized using TF-IDF
4. Cosine similarity is calculated to generate a match score
5. Important keywords are extracted and displayed

---

## 🎯 Use Cases

* Job seekers optimizing resumes for specific roles
* Students learning NLP and ML fundamentals
* Portfolio project for machine learning engineers
* Demonstration of AI-based resume screening systems

---

## 📌 Future Improvements

* Support for multiple resumes
* Skill gap analysis and recommendations
* Named Entity Recognition (NER)
* Resume ranking system
* Deployment on cloud platforms

---

## 📜 License

This project is open-source and available under the MIT License.

---

⭐ If you find this project useful, feel free to star the repository and contribute!
