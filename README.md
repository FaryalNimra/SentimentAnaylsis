

## 🧠 Twitter Sentiment Analysis – NLP & Logistic Regression

A Natural Language Processing (NLP) project that performs sentiment analysis on tweets using classical machine learning techniques. This project covers the complete ML pipeline — from data preprocessing and feature extraction to model training and interactive deployment using **Gradio**.

### 📊 Problem Statement
This is a **multi-class classification** problem where the task is to classify tweets into one of the following sentiments:
- Positive 😊  
- Negative 😠  
- Neutral 😐  

### 🧪 Example Prediction
> **Input**: *"The service was really bad!"*  
> **Output**: **Predicted Sentiment:** ❌ Negative

---

### 🧰 Tech Stack

| Area             | Tools Used                                      |
|------------------|--------------------------------------------------|
| Language         | Python 3.x                                       |
| NLP              | NLTK (tokenization, stopwords)                   |
| Feature Extraction | CountVectorizer                                 |
| Model            | Logistic Regression (Scikit-learn)               |
| Data Handling    | pandas, numpy                                    |
| Visualization    | matplotlib, seaborn                              |
| Deployment (UI)  | Gradio                                           |

---

### 📂 Dataset Information

The project uses two datasets:  
- `twitter_training.csv`  
- `twitter_validation.csv`

**Columns:**

| Column Name | Description                      |
|-------------|----------------------------------|
| id          | Unique identifier for each tweet |
| information | Meta data (not used in training) |
| type        | Sentiment label                  |
| comment     | Actual tweet text                |

---

### ⚙️ Workflow

1. Data Loading & Exploration  
2. Text Preprocessing (cleaning, tokenization, stopword removal)  
3. Feature Extraction using CountVectorizer  
4. Model Training using Logistic Regression  
5. Evaluation (Accuracy, Confusion Matrix, etc.)  
6. Deployment using Gradio for real-time predictions

---

### 📸 Project Demo

<img width="869" height="341" alt="image" src="https://github.com/user-attachments/assets/c5f08297-fe56-410f-a7ea-1670d3b650f7" />

---

### 🚀 Highlights

- Clean and modular code structure following ML best practices  
- Real-time sentiment prediction through an intuitive Gradio interface  
- Clear data pipeline with EDA and performance metrics visualizations  
- Great for beginners learning NLP and model deployment  

---

### 👩‍💻 Author  
**Faryal Nimra**  
📧 [faryalnimra190@gmail.com](mailto:faryalnimra190@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/faryal-nimra-4a49a32b6)  
🌐 [Portfolio](https://portfolio-five-beige-ixn8l41et7.vercel.app/)


