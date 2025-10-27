# blackcoffer-text-analysis-nlp
Data extraction, text cleaning, and sentiment analysis project using Python (BeautifulSoup, NLTK, and TextBlob) to compute sentiment and readability metrics from articles.


# 🧠 Blackcoffer Data Extraction & NLP Analysis
📄 Overview

This project automates data extraction, text preprocessing, and sentiment analysis for articles sourced from given URLs. It performs sentiment scoring, readability computation, and linguistic analysis to derive multiple metrics like Polarity, Subjectivity, FOG Index, and Word Complexity.

⚙️ Features

Web scraping using BeautifulSoup to extract article titles and content.

Text preprocessing with NLTK Stopwords and MasterDictionary.

Calculation of sentiment metrics:

Positive, Negative, Polarity, and Subjectivity Scores.

Readability analysis including:

FOG Index, Complex Words, Syllables per Word, Average Word Length.

Exports the final structured results to Excel (output1.xlsx).

Modular, fully reproducible Python pipeline.

🧩 Tech Stack

Languages: Python
Libraries: Pandas, Requests, BeautifulSoup, NLTK, TextBlob, OpenPyXL, tqdm
Tools: Excel, Jupyter Notebook
Methodologies: Sentiment Analysis, Readability Metrics, NLP Pipeline Design

🧱 Project Architecture
├── main.py                 # Core pipeline script
├── Input.xlsx              # List of URLs
├── output1.xlsx            # Final output with sentiment & readability metrics
├── MasterDictionary/       # Positive & Negative word lists
├── StopWords/              # Stop word sets
├── Text Analysis.docx      # Methodology documentation
├── Instruction.txt         # Setup & run instructions
├── Objective.docx          # Project objective
└── requirements.txt

🧮 Metrics Computed
Category	Variables
Sentiment	Positive Score, Negative Score, Polarity Score, Subjectivity Score
Readability	Avg Sentence Length, % Complex Words, Fog Index
Word-Level	Word Count, Complex Word Count, Syllables per Word, Personal Pronouns, Avg Word Length
▶️ How to Run

Clone the repository:

git clone https://github.com/JayKumarPal0108/blackcoffer-text-analysis-nlp.git
cd blackcoffer-text-analysis-nlp


Install dependencies:

pip install -r requirements.txt


Run the main script:

python main.py


View results in output1.xlsx.

📊 Sample Output
URL_ID	URL	Positive Score	Negative Score	Polarity	Fog Index
101	example.com/article1	45	12	0.58	14.7
102	example.com/article2	18	30	-0.25	12.3
🧠 Learning Outcomes

End-to-end text analytics pipeline design.

Implementation of custom sentiment scoring logic using word dictionaries.

Mastery of readability and linguistic metrics.

Application of data engineering techniques for text-based ETL.

📈 Author

Jaykumar Pal
📍 Data Analyst | Aspiring Data Scientist
🔗 LinkedIn
 | GitHub
