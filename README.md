# SMS & Email Spam Detection

An end-to-end Machine Learning application that classifies text messages (SMS/Email) as **Spam** or **Ham (Not Spam)**. The project covers data preprocessing, feature extraction, model training, and an interactive application interface via `app.py`.

## Features
- Real-time spam vs. ham prediction for user-entered messages
- Text preprocessing pipeline (cleaning, tokenization, stemming/stopword removal)
- TF-IDF vectorization (`vectorizer.pkl`) paired with a trained classification model (`model.pkl`)
- Complete exploratory and training workflow available in the Jupyter Notebook

## Tech Stack
- **Language:** Python
- **Data & NLP:** Pandas, NumPy, NLTK
- **Machine Learning:** Scikit-learn, TF-IDF Vectorizer
- **App & Experimentation:** `app.py`, Jupyter Notebook (`sms-spam-detection.ipynb`)

## Project Structure
```text
sms-spam-detection/
├── app.py                      # Main application script for inference/UI
├── sms-spam-detection.ipynb    # Data exploration, preprocessing, and model training
├── spam.csv                    # Dataset used for training and evaluation
├── model.pkl                   # Saved trained classification model
├── vectorizer.pkl              # Saved TF-IDF vectorizer
└── README.md                   # Project documentation
