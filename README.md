# AI-Powered Resume Screening and Ranking System 🚀

An intelligent system to automate resume screening using NLP and machine learning. Ranks PDF resumes against job descriptions via **TF-IDF vectorization** and **cosine similarity**, with a Streamlit-powered interface.


## Features ✨

- **PDF Resume Parsing**: Extracts text from PDF files using PyPDF2
- **AI Ranking Algorithm**: 
  - TF-IDF vectorization for text representation
  - Cosine similarity scoring (0-1 scale)
- **Streamlit UI**:
  - Job description text input
  - Multi-file PDF upload
  - Real-time ranking table
  - CSV export capability
- **Lightweight**: Processes 100 resumes in <20 seconds

## Installation ⚙️

### Prerequisites
- Python 3.8+
- pip package manager

### Steps
1. Clone repository:
   ```bash
   git clone https://github.com/imvinxx/AI-Powered_Resume_Screening_and_Ranking_System.git

2. Install dependencies
   ```bash
   pip install -r requirements.txt

3. Run streamlit
   ```bash
   streamlit run resume_ranker.py


### Usage 🖥️
1. Enter job description in text area
2. Upload PDF resumes (multiple files supported)
3. Click Rank Resumes
4. View/download ranked candidates:


### Tech Stack 🛠️
  Component         	Technology
                
  Frontend	          Streamlit
  PDF Processing	    PyPDF2
  NLP & ML	          scikit-learn, TF-IDF
  Data Handling	      pandas


### Limitations & Future Scope 🔮
#### Current:
- Text-based PDFs only (no image/scan support)
- English language only

#### Planned:
- DOCX resume support
- BERT embeddings integration
- Skill entity recognition
- Bias detection module

  
