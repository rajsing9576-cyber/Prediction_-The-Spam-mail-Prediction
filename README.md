Mail Spam Prediction System

A Machine Learning project that classifies email or SMS messages as Spam or Ham (Not Spam) using Natural Language Processing (NLP) and classification algorithms.

📌 Project Overview

The Mail Spam Prediction System analyzes text messages and predicts whether a message is spam or legitimate.
This project uses:

Python
Machine Learning
Natural Language Processing (NLP)
Scikit-learn
TF-IDF Vectorization

The model is trained on labeled spam/ham datasets and can predict new incoming messages.

🚀 Features
Detects spam and non-spam messages
Text preprocessing and cleaning
TF-IDF feature extraction
Machine learning classification
Predictive system for custom input messages
Simple and beginner-friendly project structure
🛠️ Technologies Used
Python
NumPy
Pandas
Scikit-learn
NLTK
Streamlit (Optional for Web App)
📂 Dataset

The dataset contains two columns:

Column	Description
label	Spam or Ham
message	Text message

Example:

label	message
ham	Hey, how are you?
spam	Congratulations! You won a free ticket.
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/mail-spam-prediction.git
2️⃣ Navigate to Project Folder
cd mail-spam-prediction
3️⃣ Install Dependencies
pip install -r requirements.txt
▶️ Run the Project
Run Python File
python spam_prediction.py
Run Streamlit App
streamlit run app.py
🧠 Machine Learning Workflow
Data Collection
Data Preprocessing
Text Cleaning
Feature Extraction using TF-IDF
Train-Test Split
Model Training
Model Evaluation
Prediction System
📊 Algorithms Used
Logistic Regression
Naive Bayes
Support Vector Machine (Optional)
📈 Model Accuracy

The model achieves high accuracy on spam detection depending on the dataset and preprocessing techniques used.

Example:

Training Accuracy : 96%
Testing Accuracy  : 95%
📝 Example Prediction
input_mail = ["Congratulations! You have won a lottery prize"]

prediction = model.predict(feature_extraction.transform(input_mail))

if prediction[0] == 1:
    print("Ham Mail")
else:
    print("Spam Mail")
📷 Project Screenshots

Add screenshots of:

Dataset
Model Training
Prediction Output
Streamlit Web App
📁 Project Structure
mail-spam-prediction/
│
├── spam.csv
├── spam_prediction.py
├── app.py
├── requirements.txt
├── README.md
└── saved_model.sav
🔮 Future Improvements
Deep Learning Integration
Real-time Email Filtering
Web Deployment
Multi-language Spam Detection
Improved NLP preprocessing
👨‍💻 Author

Raj Kumar

GitHub: https://github.com/your-username
LinkedIn: https://linkedin.com/in/your-profile
📜 License

This project is licensed under the MIT License.

⭐ Support

If you like this project, give it a ⭐ on GitHub.
