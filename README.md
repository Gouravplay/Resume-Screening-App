# 📄 Resume Screening App

An AI-powered **Resume Category Prediction** tool built with **Streamlit**, powered by **machine learning** and capable of extracting and analyzing resumes in `.pdf`, `.docx`, or `.txt` formats.

---

## 🔍 Features

- 📂 Upload resumes in PDF, DOCX, or TXT formats
- 🧹 Automatic resume text cleaning and processing
- 🧠 Predicts resume category using a pre-trained ML model
- 📊 Interactive UI built with Streamlit
- 💼 Supports multi-format resume extraction and classification

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| `Streamlit` | Frontend web UI |
| `scikit-learn` | Model training & prediction |
| `python-docx` | Extract text from DOCX files |
| `PyPDF2` | Extract text from PDF files |
| `pickle` | Load pre-trained models and vectorizers |

---

## 🚀 How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/your-username/Resume-Screening-App.git
cd Resume-Screening-App

# 2. (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run app.py

resume-screening-app/
├── app.py                  # Main Streamlit app
├── clf.pkl                 # Trained SVM model
├── tfidf.pkl               # TF-IDF vectorizer
├── encoder.pkl             # Label encoder
├── requirements.txt        # Python dependencies
├── README.md               # Project overview

streamlit
scikit-learn
python-docx
PyPDF2

🧠 Model Training
The classifier model (clf.pkl) was trained using TF-IDF vectorization on cleaned resume texts, then classified using a Support Vector Machine (SVM). Label encoding was used for mapping job categories.

Due to GitHub's file size limits, model files over 100MB are handled using Git LFS or external hosting.


🌐 Live Demo
🚀 Check out the live app here: [Resume Screening App on Streamlit](https://huggingface.co/spaces/GouravPlay/Resume_Screening_App)

📬 Contact
Gourav Goutam Pradhan
📧 Email: ggpgoutam2624@gmail.com
🔗 GitHub: @Gouravplay
