📘 AI-Powered MCQ Generator  
🧠 Turn your documents into intelligent quizzes instantly!

📖 Overview

This project is a Python-based application that uses **LangChain** and **Groq’s LLaMA-3 model** to automatically generate high-quality **multiple-choice questions (MCQs)** from any `.docx`, `.pdf`, or `.txt` file. With the click of a button or a single command, users can convert academic content into structured assessments. The tool supports multiple file types, offers customizable question counts, and outputs the results in clean `.txt` and `.pdf` formats — all stored in an organized `results/` folder.

Whether you're a teacher preparing quizzes, a student practicing concepts, or a content creator building educational tools, this generator streamlines your workflow and saves hours of manual effort.

## 🔧 Key Features

- 📄 supports multiple input formats: `.pdf`, `.docx`, `.txt`
- 🤖 AI-generated questions using LLaMA-3.3-70B from Groq
- 🎯 Customizable question count — define how many MCQs to create
- 📊 Dual output formats: text and PDF
- 📁 Results automatically saved in a clean `results/` folder
- 🧠 Designed with prompt engineering best practices
- 🔒 Keeps your files local; only sends minimal text to Groq API
- 💬 Clear and human-readable MCQ formatting

🚀 How It Works

1. 📂 You place your input file (PDF, DOCX, or TXT) in the project directory.
2. 📄 The script extracts text content from the file using `pdfplumber`, `docx`, or file reading.
3. 🤖 The extracted content is passed into a **LangChain prompt template**, powered by the **Groq API** using the **LLaMA-3.3-70B** model.
4. ✍️ The model returns structured MCQs in the desired format.
5. 📁 The generated MCQs are saved both as:
   - A `.txt` file for review or further editing
   - A `.pdf` file for printing, sharing, or uploading

🎯 Why It’s Useful

- 🧑‍🏫 Educators can quickly convert lectures and handouts into assessments  
- 📚 Students can test themselves on reading materials or notes  
- 🏫 Training institutes can scale assessment generation across modules  
- ⏱️ Saves time — no more writing questions manually  
- ⚡ Powered by state-of-the-art LLMs, ensuring relevance and clarity  
- 🔁 Can be extended into a full-fledged educational quiz platform

  ![Screenshot 2025-06-16 192852](https://github.com/user-attachments/assets/a86c6c38-2e8a-4387-b7f7-83c9e8a05668)
  ![Screenshot 2025-06-16 192837](https://github.com/user-attachments/assets/d47223fd-9d67-4cab-9b04-8f4d503093bb)
  



🛠️ Installation

1️⃣ Clone the repository:
bash
git clone https://github.com/your-username/ai-mcq-generator.git
cd ai-mcq-generator


Replace your Groq API key in the script

ai-mcq-generator/
│
├── your_script.py               # Main Python script
├── requirements.txt             # Dependencies
├── results/                     # Output folder
│   ├── generated_mcqs_*.txt
│   └── generated_mcqs_*.pdf
└── README.md

📎 Requirements
Python 3.7+

LangChain

Groq (API access)

pdfplumber

python-docx

fpdf

🤝 Acknowledgments
LangChain

Groq AI

pdfplumber

python-docx

fpdf2

📄 License
This project is licensed under the MIT License. Feel free to use, modify, and share with credit.

🔥 Unlock the power of AI to generate questions in seconds, not hours.

