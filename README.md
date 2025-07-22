# 📧 Email & SMS Spam Classifier

A simple and fast web app that classifies your message as **Spam** or **Not Spam** using machine learning.

🔗 [Live Demo](https://email-spam-classifier-sms-spam-classifier-xursftokpdenkygtwdkl.streamlit.app/)

---

## 🚀 What it Does

- Enter any email or SMS message.
- The model analyzes it using text processing + machine learning.
- Instantly tells you if it’s **SPAM** or **NOT SPAM**.

---

## 🛠️ Built With

- Python
- Scikit-learn
- NLTK (for text preprocessing)
- Streamlit (for the web interface)
- Pickle (for model loading)

---

## 📦 Run it Locally

```bash
# Clone the repo
git clone https://github.com/pantpujan017/spam-classifier.git
cd spam-classifier

# Set up virtual environment
python -m venv venv
venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
