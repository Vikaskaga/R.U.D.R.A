# AI-Powered Personalized Newsletter Generator

## 📖 Project Overview
This project is an intelligent, AI-driven newsletter generator that fetches articles from RSS feeds, processes them using NLP techniques, and curates personalized newsletters for distinct user personas. Each newsletter highlights the most relevant articles categorized by topics of interest, ensuring a tailored reading experience.

## 🚀 Key Features
- ✅ Automated article fetching from multiple RSS sources
- ✅ AI-powered article summarization (using Transformer models)
- ✅ Embedding-based personalization and content matching
- ✅ Markdown newsletters with highlight and categorized sections
- ✅ Relevance score calculation for accuracy validation
- ✅ Optional PDF conversion (Colab-ready script provided)

## 👥 User Personas
- **Alex Parker** — Tech Enthusiast
- **Priya Sharma** — Finance & Business Guru
- **Marco Rossi** — Sports Journalist
- **Lisa Thompson** — Entertainment Buff
- **David Martinez** — Science & Space Nerd

## 🛠️ Technologies Used
- Python
- feedparser, newspaper3k
- transformers, sentence-transformers
- jinja2, markdown2
- pdfkit (with wkhtmltopdf)

## 📂 Project Structure
```
Vikaskaga/R.U.D.R.A/
├── newsletters/            # Generated newsletters (MD & PDF)
├── RUDRA.ipynb             # Main Colab notebook
├── RUDRA.py   # Colab script for PDF conversion
└── requirements.txt        # Dependencies
 
## ⚙️ How to Run
1. Clone the repository `Vikaskaga/R.U.D.R.A` from GitHub.
2. Open `RUDRA.ipynb` in Google Colab.
3. Install dependencies in the Colab environment:
```python
!pip install -r requirements.txt
```
4. Run all cells in `RUDRA.ipynb` to generate newsletters and display relevance scores.
5. Optionally, convert markdown files to PDFs using `generate_pdf_colab.py`.



## 📧 Contact
*Created for the R.U.D.R.A. Placement Process — AI & Automation Engineer Role*  
GitHub Repository: [Vikaskaga/R.U.D.R.A](https://github.com/Vikaskaga/R.U.D.R.A)
My email id: vikas.kaga@associates.scit.edu
