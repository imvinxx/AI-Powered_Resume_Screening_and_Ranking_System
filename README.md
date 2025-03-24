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
   git clone https://github.com/yourusername/resume-ranker.git
   cd resume-ranker
