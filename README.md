🎬 IMDB MOVIE ANALYSIS
Data Science Project for Movie Producers

📊 Overview
This project performs an in-depth analysis of an IMDB dataset containing 3000+ movies. It answers key business questions to help movie producers make data-driven decisions.

🚀 Key Insights Generated

✔️ Highest profit movie along with its producer, director, and actors
✔️ Best language based on highest average ROI
✔️ Complete list of unique genres in the dataset
✔️ Top 3 producers ranked by average ROI
✔️ Most frequent actor and their performance summary
✔️ Top 3 directors and their most preferred actors

⚡ Quick Setup
🔹 Google Colab (Fastest Way)
Open Google Colab
Upload imdb_data (1).csv
Paste the Python script
Run and get insights instantly
🔹 Local Setup
cd imdb-movie-analysis
pip install -r requirements.txt
python movie_analysis.py
📈 Sample Output

🎥 HIGHEST PROFIT MOVIE

Title: Avatar
Profit: $2,789,900,000
Producers: Lightstorm Entertainment
Director: James Cameron
Actors: Sam Worthington, Zoe Saldana

🌍 BEST LANGUAGE: English (ROI: 345%)
🏆 TOP PRODUCERS: Warner Bros, Universal, Disney
👨‍🎤 TOP ACTOR: Samuel L. Jackson (23 movies)

📁 Project Files
File Name	Description
movie_analysis.py	Main script for complete analysis
imdb_data (1).csv	Dataset with 3000+ movies
README.md	Project documentation
requirements.txt	Required libraries
🛠 Features

✔️ Single-file execution (one-click analysis)
✔️ Handles complex JSON-like data safely
✔️ Automatic profit and ROI calculation
✔️ Robust error handling
✔️ Clean and structured output
✔️ Fully compatible with Google Colab

🔧 Tech Stack
pandas → Data manipulation
numpy → Numerical computations
ast → Safe parsing of structured data
collections.Counter → Frequency analysis
📋 Requirements
pandas >= 2.0.0
numpy >= 1.21.0
🎯 Business Value

This project helps producers answer critical questions:

✔️ Which movies generate maximum profit?
✔️ Which language gives the best ROI?
✔️ Which producers are most successful?
✔️ Which actors consistently perform well?
✔️ Which directors deliver strong results?

🧪 How to Run
from google.colab import files
files.upload()

%run movie_analysis.py
📊 Key Metrics
Metric	Formula	Purpose
Profit	revenue - budget	Measures total earnings
ROI	(revenue - budget) / budget	Investment efficiency
Avg ROI (Language)	Grouped analysis	Market strategy
Actor Frequency	Count of appearances	Star power
🔍 Dataset Structure
budget, revenue → Profit & ROI
genres → Multi-category classification
production_companies → Producers
cast → Actors
crew → Directors (job = Director)
original_language → Language analysis
📄 License

MIT License – Free for commercial and personal use 🎥

✨ Created by Yogesh Kumar Yadav
📅 March 2026
