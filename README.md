# Resume-Analyzer
The goal of this project (AI Resume Analyzer) is to demonstrate practical applications of Natural Language Processing (NLP) and Machine Learning techniques in real-world recruitment and HR analytics scenarios.

A machine learning–powered web application that analyzes resumes and job descriptions using Natural Language Processing (NLP) techniques and calculates a similarity score to measure job–resume compatibility.

🚀 Features

Upload resumes in PDF format

Paste any job description for analysis

Text preprocessing using NLP techniques

TF-IDF Vectorization for feature extraction

Cosine Similarity for resume–job matching

Keyword extraction using POS tagging

Interactive and user-friendly Streamlit UI

🧠 Technologies Used

Python

Streamlit (Web Interface)

NLTK (Tokenization, Stopwords, POS Tagging)

Scikit-learn (TF-IDF, Cosine Similarity)

PyPDF2 (PDF Text Extraction)

📂 Project Structure
Resume Analyzer/
│
├── app.py              # Main Streamlit application
├── requirements.txt    # Project dependencies
├── README.md           # Project documentation
└── .venv/              # Virtual environment (optional)
⚙️ Installation & Setup

Clone the repository:

git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer

Create and activate a virtual environment (recommended):

python -m venv .venv
.venv\Scripts\activate   # On Windows

Install dependencies:

pip install -r requirements.txt

Download required NLTK resources:

import nltk
nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
nltk.download('averaged_perceptron_tagger')

Run the application:

streamlit run app.py
📊 How It Works

Resume text is extracted from the uploaded PDF

Text is cleaned and preprocessed

Resume and job description are vectorized using TF-IDF

Cosine similarity is calculated to generate a match score

Important keywords are extracted and displayed

🎯 Use Cases

Job seekers optimizing resumes for specific roles

Students learning NLP and ML fundamentals

Portfolio project for machine learning engineers

Demonstration of AI-based resume screening systems

📌 Future Improvements

Support for multiple resumes

Skill gap analysis and recommendations

Named Entity Recognition (NER)

Resume ranking system

Deployment on cloud platforms

📜 License

This project is open-source and available under the MIT License.
