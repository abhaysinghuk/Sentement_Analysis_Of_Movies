# Sentement_Analysis_Of_Movies

# Sentiment Analysis Project...

This project focuses on analyzing text data to determine whether the sentiment expressed is positive, negative, or neutral. The goal is to understand how raw text can be processed and used to train machine learning models for classification.

---

## Project Flow (Simple Understanding)

Raw Text Data  
        ↓  
Data Cleaning  
        ↓  
Text Preprocessing  
        ↓  
Convert Text to Numbers  
        ↓  
Train Machine Learning Models  
        ↓  
Evaluate Performance  
        ↓  
Select Best Model  

---

## Step-by-Step Explanation

### 1. Data Collection
Text data with sentiment labels (positive, negative, neutral) was used as input for the model.

---

### 2. Data Cleaning

- Removed unnecessary columns  
- Renamed columns for clarity  
- Handled missing values  

This step ensures the data is usable and consistent.

---

### 3. Text Preprocessing

Each sentence was cleaned using:

- Convert text to lowercase  
- Remove punctuation and special characters  
- Tokenize text into words  
- Remove stopwords  
- Apply stemming  

This step reduces noise and keeps only meaningful words.

---

### 4. Feature Engineering

Text data was converted into numerical format using:

- Bag of Words  
- TF-IDF Vectorization  

This allows machine learning models to understand the text.

---

## How Text Becomes Numbers (Simple View)

"I love this product"  
        ↓  
["love", "product"]  
        ↓  
[0, 1, 0, 2, ...]  

---

### 5. Model Building

Different machine learning algorithms were applied:

- Naive Bayes  
- Logistic Regression  
- Support Vector Machine  
- Decision Tree  
- Random Forest  

Each model was trained using the processed data.

---

### 6. Model Evaluation

Models were evaluated using:

- Accuracy  
- Precision  
- Confusion Matrix  

Precision was important to correctly identify sentiment without mistakes.

---

## How Model Decides (Simple View)

Input: "This product is amazing"  
        ↓  
Processed Text  
        ↓  
Model Prediction  
        ↓  
Output: Positive  

---

### 7. Model Selection

The best model was selected based on performance metrics such as accuracy and precision.

---

### 8. Model Saving

The final model and vectorizer were saved using pickle for future use without retraining.

---

## Key Learnings

- Importance of cleaning text data  
- Role of preprocessing in NLP  
- How text is converted into numbers  
- Comparison of different machine learning models  
- Understanding evaluation metrics  

---

## Future Improvements

- Use deep learning models for better accuracy  
- Deploy the model using FastAPI  
- Build a user interface for real-time analysis  

---

## Author

Abhay Singh  ----> https://www.linkedin.com/in/abhaysinghuk/
