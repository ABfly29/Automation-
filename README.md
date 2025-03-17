Podcast Transcript Summarizer & Social Media Formatter

📌 Project Overview

This project automates the process of extracting insights from a podcast transcript, summarizing key takeaways, and formatting them for Twitter and LinkedIn posts. It allows manual review before publishing and saves the output in a structured Word file.

🔧 Features

✅ Automatically extracts key insights from a podcast transcript (Word file)

✅ Summarizes content using NLP techniques

✅ Formats insights for Twitter & LinkedIn

✅ Saves formatted posts in a Word file for manual review

✅ Ready for future automation with Twitter & LinkedIn APIs

🚀 How It Works

Upload a Word file containing the podcast transcript.

Extract key insights using NLP-based summarization (LSA Summarizer).

Format the insights into structured social media posts.

Save the insights in a new Word file for manual review.

📂 File Structure

|-- Podcast_Transcript (1).docx   # Input file with podcast transcript
|-- Podcast_Insights.docx         # Output file with extracted insights & social media posts
|-- extract_insights_social.py    # Python script to automate extraction & formatting
|-- README.md                     # Project documentation

🛠 Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/ABfly29/Podcast-Summarizer.git
cd Podcast-Summarizer

2️⃣ Install dependencies

pip install docx sumy nltk

3️⃣ Download NLTK Tokenizer

import nltk
nltk.download('punkt')

🔹 Usage

Run the script to extract insights and format them for social media:

python extract_insights_social.py

📝 Future Enhancements

✅ Integrate Twitter & LinkedIn API for auto-posting

✅ Improve summarization using AI models (T5, BERT)

✅ Add sentiment analysis for enhanced insights

🏆 Contributing

Feel free to submit pull requests or open issues for improvements. 🚀

📄 License

This project is open-source under the MIT License.

🙌 Acknowledgments

NLTK & Sumy for text summarization

Python-docx for handling Word files

Twitter & LinkedIn API docs for social media automation

