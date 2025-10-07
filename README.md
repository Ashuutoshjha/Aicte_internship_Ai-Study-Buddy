# 🧠 AI StudyBuddy — Your Personal Learning Companion  

AI StudyBuddy is an intelligent web-based learning assistant built using **Python** and **Streamlit**.  
It helps students **summarize text, generate notes, and understand complex topics** quickly — making studying smarter, faster, and more interactive.  

---

## 🚀 Features  
- 📚 **Text Summarization:** Upload study material or paste any content, and AI StudyBuddy will generate a concise summary.  
- 🧾 **Smart Notes Generator:** Converts lengthy text into clean, structured notes.  
- 💬 **Interactive Chat:** Ask questions and get AI-powered answers in simple language.  
- 📂 **File Upload Support:** Works with PDFs, Word files, or plain text.  
- 🌙 **Minimal, Modern UI:** Built using **Streamlit**, ensuring a smooth user experience.  
- ⚙️ **Customizable:** Easily extend or modify for various subjects or AI models.  

---

## 🧩 Tech Stack  
- **Frontend/UI:** Streamlit  
- **Backend:** Python  
- **AI Engine:** OpenAI GPT / Transformers  
- **Libraries Used:**  
  - `streamlit`  
  - `openai` / `transformers`  
  - `PyPDF2`  
  - `docx`  
  - `os`, `io`, `re`  

---

## 🧱 Project Structure  
AI-StudyBuddy/
│
├── app.py # Main application file
├── requirements.txt # Dependencies
├── README.md # Project documentation
├── utils/ # Helper functions (summarization, parsing, etc.)
├── assets/ # Icons, images, logo
└── data/ # Sample text or user-uploaded files


---

## ⚡ How to Run Locally  
```bash
# Clone this repository
git clone https://github.com/<your-username>/AI-StudyBuddy.git

# Navigate to the project folder
cd AI-StudyBuddy

# Create a virtual environment
python -m venv venv

# Activate the environment
venv\Scripts\activate     # For Windows
source venv/bin/activate  # For Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
