
# FreQ – Previous Year Paper Analyzer

**FreQ** is a web-based tool that allows students to upload previous year exam papers in multiple formats (PDF, JPG, PNG, DOCX) and analyzes the frequency of repeated questions using Natural Language Processing (NLP).  
It's designed to help students prepare smarter by identifying commonly asked questions.

---

## 🚀 Features

- Upload past exam papers (PDF, image, DOCX)  
- Extracts questions using OCR and text parsing  
- NLP-powered clustering of similar questions  
- Displays most frequently asked questions  
- Visualizes question frequency using charts  
- Downloadable PDF reports with analysis

---

## 🧠 AI/NLP Integration

- **OCR**: Converts image/PDF content to text using Tesseract  
- **NLP**: Processes and compares questions using tokenization, stemming, and semantic similarity  
- **Frequency Analysis**: Groups similar questions and counts occurrences across uploads

---

## 💻 Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Python, Flask  
- **Libraries**: Tesseract OCR, spaCy / NLTK, Matplotlib / Chart.js, PyMuPDF  
- **Storage**: Local file handling (can be extended to cloud)

---

## 📂 How to Run Locally

1. Clone the repository  
```bash
git clone https://github.com/Winter-Soldier02/FreQ
cd FreQ
```

2. Create a virtual environment and install dependencies  
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Start the Flask server  
```bash
python app.py
```

4. Open your browser and go to:  
http://localhost:5000

---

## 📷 Screenshots  
(Add screenshots of upload page, chart visualization, and frequency results here.)

---

## 📌 Future Improvements

- Add login/authentication for users  
- Enable cloud storage for files  
- Train a model for more advanced question similarity  
- Integrate GPT-based answer suggestion system

---

## 🙌 Contributions

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.
