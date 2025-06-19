# 📄 AI-Powered Resume Screener

The **AI-Powered Resume Screener** is an intelligent tool designed to bridge the gap between your resume and your dream job. By leveraging Natural Language Processing and machine learning, it evaluates how well your resume aligns with a given job description and provides actionable, data-backed suggestions for improvement.

---

## 🎯 Purpose

A successful resume isn’t just about listing qualifications — it’s about **proving you're the right fit**. This tool quantifies that fit using smart algorithms and offers personalized tips to help you stand out.

---

## 📌 At a Glance

- ✅ **AI-based Resume & JD Matching**
- ✅ **Numerical Similarity Score (0.0–1.0)**
- ✅ **spaCy-based NLP Parsing**
- ✅ **Minimal UI with Streamlit or Gradio**
- ✅ **.pdf and .txt File Support**
- ✅ **Downloadable Feedback**
- ✅ **Optional Email Summary**
- ✅ **Academic CGPA Context Option**

---

## 🔍 Step-by-Step Usage

1. **Upload Your Resume** (`.pdf`, `.txt`, or plain text)
2. **Upload the Job Description** (same formats supported)
3. **Enter Your Email & CGPA** (optional)
4. **Click “🔍 Match Resume”**
5. **Receive a Detailed Report**:
   - 📈 **Similarity Score**
   - 📋 **Final Decision**
   - 🎓 **Your CGPA**
   - 📨 **Email Confirmation**
   - 📝 **Parsed Resume Text**
   - 📌 **Parsed JD Content**

---

## 🎥 Demo

🚧 _Coming Soon_: Real-time demo video showing how the AI Screener works!

---

## 💻 Built With

- **Python 3.10+**
- [Gradio](https://gradio.app) or [Streamlit](https://streamlit.io)
- [spaCy](https://spacy.io) (`en_core_web_sm`)
- `scikit-learn` (TF-IDF + Cosine Similarity)
- `PyMuPDF (fitz)` for PDF parsing
- `FPDF` for result report generation
- `smtplib` + `email.mime` for email summaries

---

## 📂 File Support

| Format | Use Case                   |
|--------|----------------------------|
| `.pdf` | Resume & Job Description   |
| `.txt` | Resume & Job Description   |

---

## 📬 Output Breakdown

| Section            | Description                                          |
|--------------------|------------------------------------------------------|
| 📈 Similarity Score | Numeric value showing content alignment              |
| 📋 Final Decision   | Indicates if the resume qualifies                    |
| 🎓 CGPA             | Academic reference provided by user                 |
| 📨 Email Status     | Sent/not sent summary confirmation                   |
| 📝 Resume Extract   | Parsed plain text from uploaded resume               |
| 📌 JD Extract       | Parsed plain text from uploaded job description      |

---

## 🚀 What’s Coming Next?

- ✨ Enhanced NLP with contextual embeddings
- 🌍 Multilingual Resume & JD support
- 🎯 Smart skill gap identification
- 💡 Highlighting missing key terms
- 🕒 Comparison history tracking

---

## 🤝 Contributing

We welcome ideas and collaboration!

```bash
# 1. Fork the repository

# 2. Clone your fork and create a feature branch
git checkout -b your-feature-branch

# 3. Commit your changes
git commit -m "✨ Add [feature name]"

# 4. Push the branch to your fork
git push origin your-feature-branch
```
 Open a Pull Request** — we’ll review it ASAP 🎉


---

### 👩‍💻 Developed by **Prapti Mishra**
