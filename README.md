# ⚖️ Legal Document Summarizer  

**AI-Powered Legal Document Summarization**  

> “Making legal understanding faster, simpler, and multilingual.”  

---

## 🧩 Overview  

**Legal Document Summarizer** is an AI-powered web app that helps users upload legal documents (**PDF**, **DOCX**, or **TXT**) and instantly receive concise summaries in multiple languages — **English**, **Hindi**, and **Kannada**.  

It uses **Google’s Gemini 2.0 Flash Exp** model to generate fast, accurate, and professional summaries.  
The app includes **dark mode**, **text-to-speech**, and **real-time error handling** for a smooth user experience.  

---

## 🚨 Problem Statement  

Legal documents like contracts, judgments, and policies are **long, complex, and time-consuming** to read.  
Understanding key points requires significant time and legal knowledge — making it difficult for:  

- 👩‍🎓 Students preparing case summaries  
- ⚖️ Lawyers handling multiple documents daily  
- 🏠 Citizens interpreting agreements or tenders  

💡 **Goal:** Create an AI-based tool that summarizes legal documents quickly, clearly, and in multiple languages.  

---

## 🌟 Innovation & Creativity  

Our solution stands out through:  

- ⚡ **Gemini 2.0 Flash Exp** — Google’s latest fast and multilingual model  
- 🧠 **AI-based Legal Summarization** — Designed specifically for legal documents  
- 🌐 **Multilingual Support** — English, Hindi, and Kannada summaries  
- 🗣️ **Text-to-Speech Playback** — Listen to summaries in real-time  
- 🌙 **Modern UI** — Responsive design with dark/light theme toggle  

---

## ⚙️ Technical Implementation  

### 🧠 Architecture Workflow  
1. User uploads a **PDF**, **DOCX**, or **TXT** file.  
2. **Flask backend** validates and securely stores it.  
3. The app extracts text using:  
   - `PyPDF2` for PDF files  
   - `python-docx` for Word files  
   - Native reading for TXT files  
4. Extracted text is sent to **Google Gemini AI** (via `google-generativeai`).  
5. AI generates a **structured summary** in the selected language.  
6. The **frontend** displays the summary, with an option to **listen via text-to-speech**.  

---

### 🧩 Tech Stack  

| Layer | Technology |
|-------|-------------|
| Frontend | HTML, CSS, Vanilla JavaScript |
| Backend | Flask (Python) |
| AI Model | Google Gemini 2.0 Flash Exp |
| File Handling | PyPDF2, python-docx |
| Styling | CSS Custom Properties (Dark/Light mode) |
| Audio | Browser’s Web Speech API |
| Deployment | Localhost (Flask server on port 5000) |

---

## 🧪 Execution & Functionality  

### 🚀 How It Works  

```bash
# Step 1: Run the app
python main.py

# Step 2: Open the local URL
http://127.0.0.1:5000

# Step 3: Upload a document and get your AI-generated summary
```
## 📄 Key Features

- **Upload & Summarize** PDFs, DOCX, or TXT files  
- **Choose Summary Language**: English, Hindi, Kannada  
- **Real-time Summary Display**  
- **Text-to-Speech**: Listen to summaries  
- **Dark/Light Mode Toggle**  
- **Secure File Handling & Cleanup**

---

## 📈 Impact & Scalability

### 🎯 Impact
- Saves hours of manual reading and summarization  
- Helps users understand legal documents faster  
- Makes legal information more accessible and multilingual  

### 📊 Scalability
- Add more languages (Tamil, Telugu, Marathi)  
- Extend summarization to case law databases or policy archives  
- Create a mobile version using the same backend API  

---

## 🧠 Example Use Cases
- Summarizing Supreme Court judgments for study  
- Understanding contract or property clauses  
- Reviewing policy or compliance documents  

---

## 🛡️ Security Measures

- ✅ File validation with allowed extensions (`.pdf`, `.docx`, `.txt`)  
- ✅ Safe filenames using `secure_filename()`  
- ✅ File size limit (16 MB)  
- ✅ Automatic deletion after summarization  
- ✅ Environment-based API key protection  

## 🧭 Future Enhancements

- 🧾 Keyword extraction and legal term tagging  
- 💬 “Ask Questions” chat feature  
- 📱 Mobile and desktop versions  
- 📊 Analytics for law firms  

## 🏁 Conclusion

The **Legal Document Summarizer** bridges the gap between law and technology, helping users save time, gain clarity, and make informed decisions. Fast, secure, and multilingual—legal document analysis has never been easier.

