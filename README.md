# 📧 Email Spam Classifier 🔍📨

## 📌 Project Overview
Unwanted spam emails are a common issue in today's digital world. This project focuses on building an **Email Spam Classifier** using **Machine Learning** to accurately differentiate between spam and non-spam (ham) emails. The model is trained on a dataset containing labeled emails and uses **Natural Language Processing (NLP)** techniques to preprocess and classify emails effectively.  

## 📂 Dataset Used
The dataset consists of email texts labeled as either **Spam** or **Ham** (Not Spam).  
- Includes raw email text data  
- Pre-labeled for supervised learning  
- Contains both short and long emails with varied formatting  

## 🛠️ Technologies & Libraries Used
- **Python** – NumPy, Pandas  
- **Natural Language Processing (NLP)** – NLTK  
- **Data Visualization** – Matplotlib, Seaborn  
- **Machine Learning** – Scikit-Learn  
- **Deployment** – Streamlit  

## 🔍 Data Preprocessing
To enhance model accuracy, various preprocessing steps were performed:  
✔️ **Text Cleaning** – Removing special characters, punctuation, and stopwords  
✔️ **Lowercasing** – Converting all text to lowercase  
✔️ **Tokenization** – Splitting text into words  
✔️ **Stemming** – Reducing words to their root form using **Porter Stemmer**  
✔️ **Vectorization** – Using **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert text into numerical features  

## 📊 Machine Learning Models Used
Several models were tested to achieve the best accuracy:  
- **Naive Bayes (Best Performing Model)**  
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  

After evaluation, **Naive Bayes** was found to be the most effective in classifying spam emails with high accuracy.  

## 🚀 Results & Accuracy
✅ High precision and recall for spam detection  
✅ Low false-positive rate  
✅ Effective filtering of unwanted emails  

## 🌐 Web App Deployment with Streamlit  
This project is deployed using **Streamlit**, allowing users to test the classifier via a simple web interface.  

## 🏗️ How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/email-spam-classifier.git

## 📸 Output Screenshots  
**1️⃣ Streamlit App Interface**  
![App UI](screenshots/Email_classifier.png)  

**2️⃣ Example: Spam Email Prediction**  
![Spam Prediction](screenshots/spam_email.png)  

**3️⃣ Example: Ham Email Prediction**  
![Ham Prediction](screenshots/ham_email.png)  
   

   
