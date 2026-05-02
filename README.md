## 📖 Overview

This project builds an end-to-end NLP pipeline for **next word prediction**. Given a sequence of words, the model predicts the most probable word that comes next. The pipeline covers:

| Step | Description |
|------|-------------|
| 1️⃣ Data Collection | Shakespeare's *Hamlet* as the training corpus |
| 2️⃣ Data Preprocessing | Tokenization, sequence generation, padding & train/test split |
| 3️⃣ Model Building | Embedding + 2× LSTM + Dense (Softmax) layers |
| 4️⃣ Model Training | Trained with Early Stopping on validation loss |
| 5️⃣ Model Evaluation | Tested on sample sentences |
| 6️⃣ Deployment | Interactive Streamlit web application |