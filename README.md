# 📧 Spam email Detection using Logistic Regression

This project is a simple Machine Learning model that classifies email messages as **Spam (0)** or **Ham (1)** using **TF-IDF** and **Logistic Regression**.

## 🚀 Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy


## 🧠 Model Training Steps
1. Clean and preprocess the dataset  
2. Convert text into numerical features using **TfidfVectorizer**  
3. Split data into training and testing sets  
4. Train Logistic Regression  
5. Evaluate model accuracy  
6. Predict new email messages  

## 🧪 Example Prediction

```python
input_mail = ["Hey, your appointment is confirmed for tomorrow."]
input_data_features = feature_extraction.transform(input_mail)
prediction = model.predict(input_data_features)

if prediction[0] == 1:
    print("Ham (Not Spam)")
else:
    print("Spam")
