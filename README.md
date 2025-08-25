# Translator Chat – Project Presentation  

## 📌 Overview  
This project is a **Translator Chat Application** that allows users to input text in any language and get real-time translations in another language. It also **detects the original language** automatically, making it seamless for multilingual communication.  

## 🎯 Problem It Solves  
Language barriers often prevent smooth communication. This project solves that problem by enabling quick, accurate, and automatic translations in a simple chat interface.  

## ⚙️ Technologies Used  
- **Python** – Core programming language  
- **Flask** – Web framework for the chat interface  
- **Groq API / Translation API** – For language translation & detection  
- **HTML + CSS (Bootstrap)** – For frontend UI styling  
- **python-pptx** – For generating presentation slides  

## 🚧 Challenges Faced  
- Implementing **real-time language detection**  
- Ensuring **accurate translations** for different languages  
- Designing a **user-friendly interface** that’s simple but effective  

## 📂 Files in This Project  
- `app.py` → Main Flask app (chat + translation logic)  
- `templates/` → HTML files for the web UI  
- `static/` → CSS & JS files for styling  
- `make_ppt.py` → Script to auto-generate the PPT presentation  
- `Translator_Chat_Presentation.pptx` → Final presentation file  
- `README.md` → This file  

## ▶️ How to Run  
1. Install dependencies:  
   ```bash
   pip install flask groq python-pptx
   ```
2. Run the web app:  
   ```bash
   python app.py
   ```
   Then open `http://127.0.0.1:5000` in your browser.
