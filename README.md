# EZ-Labs-Task
# 📚 Smart Assistant for Research Summarization (GenAI Project)

A GenAI-powered assistant that intelligently reads user-uploaded documents (PDF/TXT), generates concise summaries, answers context-aware questions, and challenges users with logic-based questions — all with justifications from the source.

> Built for EZ’s Data Science Internship Evaluation

---

## 🧠 Key Features

### ✅ Document-Aware Assistant
- Upload PDF or TXT files
- Automatically generate a concise summary (≤150 words)
- Contextual understanding of the document using LLMs (GPT-4 or similar)

### 💬 Interaction Modes
1. **Ask Anything**  
   Ask free-form questions and get document-grounded answers with references.
2. **Challenge Me**  
   - Generates 3 logic-based or comprehension-focused questions from the document.  
   - Evaluates user responses and provides feedback with justification.

### 🧾 Justification & References
Each answer includes:
- Reasoning
- Reference to a paragraph/section in the document (no hallucinations)

---

## 🚀 Tech Stack

| Component       | Technology       |
|----------------|------------------|
| Frontend        | Streamlit        |
| Backend         | Python (OpenAI API) |
| PDF Processing  | PyPDF2, pdfplumber |
| Language Model  | GPT-4 (OpenAI API) |
| Optional Vector Search | FAISS + sentence-transformers |
| Evaluation Logic | Custom LLM prompting |
| Deployment      | Localhost (Streamlit) |

---

## 🏗️ Project Structure

 Future Improvements
Add vector store (FAISS) for better long-doc retrieval

Enable memory (context persistence across sessions)

Deploy to cloud (e.g., Streamlit Cloud or HuggingFace Spaces)

🙋‍♀️ Author
Bhumika Agrawal
Data Science Intern Applicant – 2025
GitHub:https://github.com/BhumikaAgrawal777
