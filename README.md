# 🎬 **IMDB MOVIE ANALYSIS** 
*Data Science Analysis of 3000+ Movies for Movie Producers*


***

## 📊 **What it does**
Complete analysis of **IMDB dataset (3000+ movies)** answering **6 key business questions** for movie producers:

1. **Highest profit movie** + producers, director, actors
2. **Best language** for highest average ROI
3. **All unique genres** in dataset
4. **Top 3 producers** by average ROI
5. **Actor in most movies** + their performance summary
6. **Top 3 directors' favorite actors**

***

## 🚀 **Quick Start**

### **Google Colab (2 minutes)**
```bash
1. Open https://colab.research.google.com
2. Upload 'imdb_data (1).csv' 
3. Copy-paste the single Python script
4. Run → Get all insights instantly!
```

### **Local Setup**
```bash
git clone https://github.com/YOUR_USERNAME/imdb-movie-analysis.git
cd imdb-movie-analysis
pip install -r requirements.txt
python movie_analysis.py
```

***

## 📈 **Sample Output**
```
🎥 HIGHEST PROFIT MOVIE
Title: Avatar
Profit: $2,789,900,000
Producers: Lightstorm Entertainment
Director: James Cameron
Actors: Sam Worthington, Zoe Saldana

🌍 BEST LANGUAGE: English (ROI: 345%)
🏆 TOP PRODUCERS: Warner Bros, Universal, Disney
👨‍🎤 TOP ACTOR: Samuel L. Jackson (23 movies)
```

***

## 📁 **Files**
| File | Description |
|------|-------------|
| `movie_analysis.py` | **Main script** - Complete analysis |
| `imdb_data (1).csv` | **Dataset** - 3000+ IMDB movies |
| `README.md` | This file |
| `requirements.txt` | Dependencies |

***

## 🛠 **Features**
- ✅ **One-click analysis** - Single Python file
- ✅ **JSON parsing** - Handles complex IMDB data structure
- ✅ **Profit/ROI calculation** - Automatic
- ✅ **Error handling** - Robust parsing with `ast.literal_eval`
- ✅ **Production-ready** - Clean output formatting
- ✅ **Colab optimized** - Zero setup required

***

## 🔧 **Tech Stack**
```python
pandas    # Data manipulation
numpy     # Calculations
ast       # Safe JSON parsing
collections.Counter  # Actor/director counting
```

***

## 📋 **Requirements**
```txt
pandas>=2.0.0
numpy>=1.21.0
```

***

## 🎯 **Business Insights for Producers**
```
✅ Which movies make MOST PROFIT?
✅ Best LANGUAGE for ROI?
✅ Hottest PRODUCERS to partner with?
✅ Actors with PROVEN track record?
✅ Directors who deliver RESULTS?
```

***

## 🧪 **How to Test**
```python
# 1. Upload dataset
from google.colab import files
files.upload()  # Select imdb_data (1).csv

# 2. Run analysis
%run movie_analysis.py
```

***

## 📈 **Key Metrics Calculated**
| Metric | Formula | Business Value |
|--------|---------|----------------|
| **Profit** | `revenue - budget` | Absolute success |
| **ROI** | `(revenue-budget)/budget` | Investment return |
| **Avg ROI/Language** | Groupby analysis | Market selection |
| **Actor Frequency** | Cast counter | Bankable stars |

***

## 🔍 **Data Structure**
```
IMDB Dataset Columns:
├── budget, revenue → PROFIT/ROI
├── genres → Multi-genre parsing
├── production_companies → Producers  
├── cast → Actor lists
├── crew → Directors (job='Director')
└── original_language → Language ROI
```

***



## 📄 **License**
MIT License - Free to use for commercial movie production! 🎥

***
 
*March 2026 | Yogesh Kumar Yadav* 

***
