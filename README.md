# 📄 AI-Powered Resume Screener

The **AI-Powered Resume Screener** helps you match your resume with job descriptions using advanced AI-based analysis. It calculates a **Similarity Score** and provides detailed feedback to improve your resume, increasing your chances of landing your dream job.

A strong resume isn't just about listing skills – it's about how well your resume matches the job description. This AI tool ensures that your resume highlights the right **skills** and **experiences** to make you a perfect fit for the job!

---

## 📌 Overview

This tool uses natural language processing and machine learning to evaluate how well your resume matches a specific job description.

---

## 🌟 Key Features

✅ AI-based analysis for accurate feedback  
✅ Detailed similarity score to evaluate alignment with job requirements  
✅ Resume and job description comparison using advanced NLP techniques  
✅ User-friendly interface built with Streamlit or Gradio  
✅ Works with all types of resumes and job descriptions  
✅ Option to download results for future reference  
✅ Actionable suggestions to improve your resume based on the similarity score  

---

## 🔍 How It Works

1. **Upload or Paste Your Resume** – Provide your resume in `.pdf`, `.txt`, or plain text format  
2. **Upload or Paste Job Description** – Provide the job description similarly in `.pdf`, `.txt`, or plain text  
3. **Enter Your Email and CGPA** – This helps personalize the feedback and simulate sending results  
4. **Click “🔍 Match Resume”** – The AI analyzes your resume and computes a similarity score  
5. **Get Feedback & Results** – You'll receive:
   - 📈 Similarity Score  
   - 📋 Final Decision (Shortlisted / Not Shortlisted)  
   - 🎓 Entered CGPA  
   - 📨 Email Status (simulated)  
   - 📝 Extracted Resume Text  
   - 📌 Extracted JD Text  

---

## 💻 Technologies Used

- Python 3.10+  
- Gradio or Streamlit (UI)  
- spaCy (`en_core_web_sm`)  
- scikit-learn (TF-IDF + cosine similarity)  
- PyMuPDF (`fitz`) for PDF parsing  
- FPDF (PDF result generation)  
- `smtplib` for Gmail-based email simulation  
- `email.mime` modules for formatting  

---

## 📂 File Upload Support

- `.pdf` and `.txt` files are supported for both Resume and Job Description.

---

## 📬 Output Sections

| Section                 | Description                                               |
|------------------------|-----------------------------------------------------------|
| 📈 Similarity Score     | Float (0 to 1) indicating textual alignment               |
| 📋 Final Decision       | Whether the candidate is shortlisted                     |
| 🎓 Entered CGPA         | Shown for transparency in final decision                 |
| 📨 Email Status         | Indicates if simulated email was "sent"                  |
| 📝 Extracted Resume     | Raw text pulled from resume file                         |
| 📌 Extracted JD         | Raw text pulled from job description                     |

---

## 🚩 Future Improvements

✨ Improve NLP model accuracy with fine-tuning  
✨ Add support for multiple languages  
✨ Introduce AI-generated suggestions for improving resume content  
✨ Include keyword-based analysis to highlight missing skills  
✨ Allow saving multiple results for better comparison  

---

## 🤝 Contributing

We welcome your contributions! Follow these steps to get started:

```bash
# 1. Fork the repository

# 2. Clone your fork and create a new branch
git checkout -b feature/your-feature

# 3. Make your changes and commit
git commit -m "Add your feature"

# 4. Push to your forked repo
git push origin feature/your-feature

# 5. Create a Pull Request 🎉
