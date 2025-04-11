# 📰 Fake News Detection App

This project is a **Fake News Detection System** that uses **Natural Language Processing (NLP)** and a **Logistic Regression model** to classify news articles as **Real** or **Fake**. It includes a web-based UI built with **Streamlit** for easy user interaction.

---

## 📌 Features

- Cleans and preprocesses text data (removes punctuation, URLs, HTML tags, etc.)
- Trains a Logistic Regression classifier using TF-IDF features
- Saves and loads models using `joblib`
- Provides a simple and intuitive web app to detect fake news

---

## 📁 Dataset

We use two datasets:
- `Fake.csv` — containing fake news articles
- `True.csv` — containing real news articles

Each dataset is labeled:
- `0` = Fake news
- `1` = Real news

---

## 🔧 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/fake-news-detector.git
cd fake-news-detector
2. Install dependencies
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install required packages:

bash
Copy
Edit
pip install -r requirements.txt
If you don't have a requirements.txt, use:

bash
Copy
Edit
pip install pandas scikit-learn joblib streamlit
🚀 How to Run
1. Train the Model (optional)
If you're running for the first time or updating the model:

bash
Copy
Edit
python your_script_name.py
This will:

Train the model

Save vectorizer.jb and lr_model.jb

2. Run the Streamlit App
bash
Copy
Edit
streamlit run your_script_name.py
Replace your_script_name.py with the name of your Streamlit script (e.g., app.py).

🧪 Example
Paste a news article into the textbox and click Check News. The app will tell you if it's Real or Fake.

📦 Project Structure
graphql
Copy
Edit
fake-news-detector/
│
├── Fake.csv
├── True.csv
├── vectorizer.jb         # Saved TF-IDF Vectorizer
├── lr_model.jb           # Saved Logistic Regression model
├── your_script_name.py   # Your full training + Streamlit code
└── README.md
🤝 Contributing
Pull requests and suggestions are welcome. For major changes, please open an issue first to discuss.

📄 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Scikit-learn

Pandas

Streamlit

python
Copy
Edit

Let me know your script filename if you'd like me to update `your_script_name.py` to match it — or if you'd like me to generate the `requirements.txt` file too!
