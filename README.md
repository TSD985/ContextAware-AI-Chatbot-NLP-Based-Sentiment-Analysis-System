## 🤖 ContextAware AI Chatbot – NLP Based Sentiment Analysis System
### 📘 Overview

ContextAware AI Chatbot is an NLP-powered conversational assistant developed using Python, Flask, and Machine Learning techniques.

The chatbot analyzes user input in real time, preprocesses textual data using NLP pipelines, predicts sentiment using a trained machine learning model, and generates context-aware responses based on sentiment classification.

The system was trained on an 84K+ English sentiment dataset and designed with support for multilingual dataset integration to improve conversational understanding across different languages and user contexts.

The project demonstrates practical implementation of Natural Language Processing, sentiment analysis, text vectorization, and Flask-based web deployment.

### 🧩 Problem Statement

Traditional chatbots often rely on fixed responses without understanding user sentiment or conversational context.

Basic rule-based systems can:

- Fail to understand user emotions
- Generate repetitive responses
- Lack contextual awareness
- Provide poor conversational experience

This project solves these challenges using NLP preprocessing and machine learning-based sentiment analysis.

### 🚀 Key Features
#### 1. Real-Time Sentiment Analysis

Analyzes user input and predicts sentiment dynamically during conversations.

#### 2. NLP-Based Text Preprocessing

Implements:

- Tokenization
- Stopword Removal
- Lemmatization
- Stemming
- Text Cleaning

for improved prediction accuracy.

#### 3. Machine Learning Classification

Uses trained ML models with vectorization techniques to classify text into:

- Positive
- Neutral
- Negative

#### 4. Large Dataset Training

The chatbot model was trained on:

- 84K+ English sentiment records
- Multiple sentiment categories
- Structured NLP datasets

#### 5. Machine Learning Model Performance

Implemented and evaluated multiple machine learning algorithms for sentiment classification:

- Naive Bayes achieved ~70% accuracy
- Support Vector Machine (SVM) achieved ~72% accuracy
- Logistic Regression achieved ~74% accuracy

using NLP preprocessing, feature extraction, and N-Gram vectorization techniques.

#### 6. Context-Aware Response Generation

Generates different chatbot responses based on detected sentiment.

#### 7. Flask Web Integration

Provides an interactive chatbot interface using Flask backend integration.

#### 8. Vectorization & Model Serialization

Uses:

- N-Gram Vectorization
- TF-IDF/BOW Models
- Pickle Serialization

for efficient inference and deployment.

---

### ⚙️ Workflow Architecture
1. User enters message through chatbot UI
2. Input text is preprocessed using NLP pipeline
3. Cleaned text is transformed using vectorizer
4. ML sentiment model predicts sentiment class
5. Context-aware response is generated
6. Flask backend returns chatbot response in real time

---

### 🛠️ Tech Stack
1. Python
2. Flask
3. NLTK
4. Scikit-learn
5. Pickle Serialization
6. HTML/CSS
7. NLP & Sentiment Analysis

---

### 💼 Use Cases
1. AI Chatbot Systems
2. Sentiment Analysis Applications
3. Customer Interaction Automation
4. Conversational AI Systems
5. NLP Learning & Research Projects

---

### 📚 Learning Outcomes

This project helped in gaining practical experience with:

1. Natural Language Processing workflows
2. Sentiment analysis model training
3. Text preprocessing techniques
4. Flask web application development
5. Vectorization techniques like N-Gram and TF-IDF
6. Machine Learning model integration

---

### 🔮 Future Improvements
1. Integration of larger multilingual datasets
2. Improved dataset balancing and training accuracy
3. Deep Learning and Transformer-based NLP models
4. Voice-enabled chatbot interaction
5. Emotion intensity detection
6. Chat memory and conversational history support

---

## 📂 Repository Contents
1. app.py Flask application
2. NLP preprocessing notebooks
3. Trained ML models (.pkl)
4. Vectorizer files
5. English dataset CSV files
6. HTML/CSS frontend files
7. Input and output screenshots
