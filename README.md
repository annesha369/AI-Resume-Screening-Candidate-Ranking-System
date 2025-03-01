# AI Resume Screening & Candidate Ranking System

## Overview
This project is a **Streamlit-based AI Resume Screening & Candidate Ranking System** that helps recruiters efficiently screen resumes by ranking them based on their similarity to a given job description. The system uses **TF-IDF vectorization** and **cosine similarity** to measure the relevance of each resume.

## Features
- Upload multiple resumes in **PDF format**.
- Extract text from PDFs using `PyPDF2`.
- Rank resumes based on similarity to a given job description.
- Display ranked resumes in a tabular format.
- Interactive **Streamlit** UI for easy use.

## Technologies Used
- **Python**
- **Streamlit** (for the web interface)
- **PyPDF2** (for extracting text from PDFs)
- **scikit-learn** (for TF-IDF vectorization and cosine similarity)
- **pandas** (for handling and displaying results)

## Installation & Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-repo/ai-resume-screening.git
   cd ai-resume-screening
   ```
2. **Create a virtual environment (optional but recommended)**
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```
3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
4. **Run the application**
   ```sh
   streamlit run app.py
   ```

## Usage
1. Enter the **job description** in the provided text area.
2. Upload **PDF resumes** using the file uploader.
3. Click submit to **rank the resumes**.
4. View the ranked resumes in a sorted table based on similarity scores.

## File Structure
```
📂 ai-resume-screening
│-- 📜 app.py (Main Streamlit application)
│-- 📜 requirements.txt (Dependencies)
│-- 📜 .readme (Project documentation for GitHub)
```

## Issues & Improvements
### Known Issues
- Some PDFs may not have selectable text, leading to inaccurate text extraction.
- The system does not currently handle **image-based resumes** (e.g., scanned PDFs).

### Possible Improvements
- Implement OCR (e.g., `Tesseract`) for extracting text from image-based resumes.
- Enhance UI for better visualization of ranking.
- Implement NLP techniques for better semantic matching.

## Contribution
If you'd like to contribute, feel free to submit a **pull request** or report an **issue**.


## Author
Annesha Panda - [Annesha Panda](https://github.com/annesha369)

