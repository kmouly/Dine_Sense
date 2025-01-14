# Dine Sense

## Introduction
**Dine Sense** is a sentiment analysis system designed to evaluate restaurant reviews using advanced Natural Language Processing (NLP) techniques. The project helps restaurant owners and customers understand the overall sentiment of reviews, whether they are positive or negative. By automating the review analysis process, Dine Sense provides valuable insights to improve customer experiences and business strategies.

---

## About the Dataset
The dataset used in this project comprises restaurant reviews collected from Kaggle.  
**Dataset link:** [Restaurant Reviews (TSV)](https://www.kaggle.com/datasets/maher3id/restaurant-reviewstsv/data)

### Dataset Details:
- **Text reviews:** Descriptive feedback from customers.
- **Ratings:** Binary values:  
  - `0`: Negative sentiment  
  - `1`: Positive sentiment  

The dataset was preprocessed to clean text data, remove noise, and tokenize sentences for effective sentiment analysis.

---

## Features
- **Sentiment Analysis:** Classifies reviews as positive or negative.
- **NLP Techniques:** Utilizes tokenization, lemmatization, and vectorization.
- **Visualization:** Displays sentiment trends through graphs and charts.
- **User-Friendly Interface:** An interactive web interface for seamless navigation and review insights.
- **Future Scope:** Potential integration with live customer review feeds for real-time analysis.

---

## Tech Stack
- **Programming Language:** Python
- **Libraries/Frameworks:**
  - Pandas & NumPy (data processing)
  - Scikit-learn (machine learning models)
  - Natural Language Toolkit (NLTK) & spaCy (NLP)
  - Matplotlib & Seaborn (data visualization)
  - Flask(web interface)
- **Tools:** Google Colab Notebook, VSCode

---

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Dine-Sense.git
   cd Dine-Sense
   
### 2. Install Dependencies
Ensure you have all necessary dependencies installed by using the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

---
## **Deployment**
The application is deployed on platform[Render](https://render.com). However, due to memory constraints on free-tier deployments, the audio upload feature might not work reliably.
