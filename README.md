 Automated SMS Spam Classifier

 📌 Overview

This project is an end-to-end machine learning application for SMS spam detection. It classifies messages as spam or ham (not spam) using natural language processing (NLP) and machine learning techniques. The model is trained using a dataset of SMS messages and deployed with a user-friendly interface for real-time predictions.

 Tech Stack

- Python
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn
- NLTK
- Streamlit

🚀 Installation

1. Clone this repository:
   git clone (https://github.com/vijittiwari/AI-ML-Project.git)
   cd AI-ML-Project
  
2. Create a virtual environment (optional but recommended):
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
  
3. Install dependencies:
   pip install -r requirements.txt

 📌 Usage

 Run the Streamlit app:
 streamlit run app.py
  
 📄 Dataset
  The model is trained on an SMS spam dataset containing labeled messages as either spam or ham. Preprocessing includes text cleaning, tokenization, and vectorization using TF-IDF.

 💡 Results
  The trained model achieves high accuracy in detecting spam messages. Different algorithms were tested, and the best-performing model was selected based on precision, recall, and F1-score.





