# 🛡️ Phishing Website Detection using Machine Learning

This is a Flask-based web application that predicts whether a given URL is **phishing** or **legitimate** using a trained machine learning model. The prediction is based on a set of handcrafted features extracted from the URL and its metadata.

---

## 🚀 Features

- 🌐 Web-based interface to input URLs
- 🧠 Machine learning model trained on 30+ URL features
- ⚙️ Flask backend with HTML, CSS frontend
- 📊 Probability-based prediction output (Safe / Unsafe)
- 🎨 Responsive and stylish UI

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/phishing-url-detector.git
cd phishing-url-detector

🧪 How It Works
Input: Enter a URL into the form.

Feature Extraction: The FeatureExtraction class extracts 30 features related to domain, structure, metadata, etc.

Prediction: The model classifies the URL as safe or unsafe based on these features.

Output: The app shows the probability and a message like "Website is 85% safe" or "Website is 72% unsafe".

✅ Sample Test URL
Use the following to test the app:

bash
Copy
Edit
https://caniphish.com/free-phishing-test/phishing-website-templates#signupForm
