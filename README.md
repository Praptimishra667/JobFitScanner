# 📄 AI-Powered Resume Screener

The **AI-Powered Resume Screener** is an intelligent tool designed to bridge the gap between your resume and the job you're aiming for. By leveraging advanced natural language processing, it evaluates how closely your resume aligns with a job description and provides **data-backed suggestions** to optimize your chances of landing interviews.

> 🎯 A successful resume isn't just about listing qualifications — it's about proving you're the right fit. This AI tool makes that alignment measurable.

---

## 📌 At a Glance

The tool uses a combination of **machine learning**, **TF-IDF scoring**, and **spaCy NLP** to analyze and compare resume content with job descriptions, giving candidates a fair, fast, and insightful evaluation.

---

## 🌟 What Makes It Stand Out?

- ✅ Smart AI-based matching and feedback  
- ✅ Numerical **similarity score** to understand JD alignment  
- ✅ Natural Language Processing (NLP) to parse both documents  
- ✅ Clean, minimal interface powered by Streamlit or Gradio  
- ✅ Accepts `.pdf` and `.txt` formats  
- ✅ Download-ready outputs for personal tracking  
- ✅ Actionable, resume-specific improvement tips  

---

## 🔍 Step-by-Step Usage

1. **Upload Your Resume** – Supported formats: `.pdf`, `.txt`, or plain text  
2. **Upload the Job Description** – Same format rules apply  
3. **Enter Your Email & CGPA** – Used for optional email feedback and academic context  
4. **Click “🔍 Match Resume”** – Our AI will analyze both documents  
5. **Receive Tailored Results**, including:
   - 📈 **Similarity Score**
   - 📋 **Decision Status**
   - 🎓 **Your CGPA**
   - 📨 **Email Confirmation**
   - 📝 **Extracted Resume Text**
   - 📌 **Extracted JD Content**

---

## 🎥 Demo

<!-- Embed or link your demo video here if available -->
*Coming soon: Watch how the AI Screener works in real time!*

---

## 💻 Built With

- **Python 3.10+**  
- **Gradio** or **Streamlit** for the web interface  
- **spaCy** (`en_core_web_sm`) for text processing  
- **scikit-learn** for TF-IDF and cosine similarity  
- **PyMuPDF** (`fitz`) for extracting text from PDFs  
- **FPDF** for generating result PDFs  
- **smtplib** + `email.mime` for sending email summaries  

---

## 📂 File Support

| Format | Usage                  |
|--------|------------------------|
| `.pdf` | Resume and Job Description |
| `.txt` | Resume and Job Description |

---

## 📬 Output Breakdown

| Section              | Description                                          |
|----------------------|------------------------------------------------------|
| 📈 Similarity Score   | Numeric value (0.0–1.0) showing content alignment    |
| 📋 Final Decision     | Whether your resume qualifies for the role          |
| 🎓 Entered CGPA       | Displayed for academic reference                    |
| 📨 Email Status       | Status of result email (if credentials provided)    |
| 📝 Resume Extract     | Parsed plain text from the uploaded resume          |
| 📌 JD Extract         | Parsed plain text from the uploaded job description |

---

## 🚀 What’s Coming Next?

- ✨ Enhanced NLP with contextual embeddings  
- ✨ Multilingual resume and JD support  
- ✨ Intelligent recommendations to add/remove skills  
- ✨ Highlighting of missing key terms in your resume  
- ✨ Session-based comparison history tracking  

---

## 🤝 Contributing

We’re open to ideas and collaboration! Follow the steps below to contribute:

```bash
# 1. Fork the repository

# 2. Clone your fork locally and create a feature branch
git checkout -b your-feature-branch

# 3. Commit your changes
git commit -m "✨ Add [feature name]"

# 4. Push the branch to your fork
git push origin your-feature-branch

# 5. Open a Pull Request — we’ll review it ASAP 🎉
***Developed by Prapti Mishra***



---




