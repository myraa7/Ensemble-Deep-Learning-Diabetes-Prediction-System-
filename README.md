# Diabetes Prediction System using Machine Learning and Flask

This project is a web-based diabetes prediction system using Deep learning & Machine learning models trained on different datasets. It includes user authentication and model predictions through a Flask-powered frontend.

---

# 🚀 Features

- User Registration with OTP verification
- Login System with SQLite backend
- Predict diabetes from user input using 3 different datasets/models
- Separate result view for each prediction
- Visual insights via comparison graphs (handled in notebooks)

---

# 📁 Project Structure

```
├── app.py                 # Flask framework
├── Data1.ipynb            # Jupyter notebook - dataset 1
├── Data2.ipynb            # Jupyter notebook - dataset 2
├── Data3.ipynb            # Jupyter notebook - dataset 3
├── model_data1.sav        # Saved model 1
├── model_data2.sav        # Saved model 2
├── model_data3.sav        # Saved model 3
├── sample.txt             # Sample datasets (raw form)
├── templates/             # HTML templates
├── signup.db              # SQLite DB for users
├── requirements.txt       # Python dependencies
```

---

# 🛠️ Setup Instructions

1. Clone the repository  
   ```
   git clone <repo_url>
   cd <project_directory>
   ```

2. Install dependencies  
   ```
   pip install -r requirements.txt
   ```

3. Run the Flask App  
   ```
   python app.py
   ```

4. Open browser  
   Navigate to `http://127.0.0.1:5000/`

---

# 📈 Models Used

- ANN
- CNN
- LSTM
- Voting Classifier
- Hybrid CNN+LSTM
- DecisionTree, SVM, and Stack-(ANN, CNN, LSTM)

Each dataset has a unique model with feature selection using ExtraTreesClassifier.

---

# 🧠 Prediction Output

- "The Prediction Indicates That The Person Does/Does Not Have Diabetes"

---

# 🔧 Extension

This project extends the base machine learning approach by incorporating advanced deep learning and ensemble techniques such as:

- Stacked Models: Stack-ANN, Stack-CNN, Stack-LSTM
- Hybrid Models: CNN + LSTM
- Voting Classifier: Combining predictions from Random Forest, Bagging with Extra Trees, and Boosted Decision Trees
- Flask Web Frontend: Developed a user-friendly interface for interacting with the models, including user signup/login via OTP verification.

These additions enhance the model's accuracy and usability beyond the original baseline approach.

---

# 🚀 Future Scope

To further enhance the application, the following features and improvements can be considered:

- 🔹 Deployment: Host the application on platforms like Heroku, AWS, or Azure for public access.
- 🔹 Real-Time Integration: Connect with real-time health tracking devices or APIs.
- 🔹 Mobile Application: Develop an Android/iOS app version using React Native or Flutter.
- 🔹 Advanced Visualizations: Add explainable AI (XAI) tools like SHAP or LIME to interpret predictions.
- 🔹 Modern Frontend Framework: Upgrade UI using React, Vue.js, or Streamlit for better interactivity.
- 🔹 More Datasets: Train and evaluate models on broader and more diverse diabetes datasets.