# Chat-Bot
# 🤖 Smart Document Chatbot with LangChain & Gemini

A powerful conversational chatbot that can:
- Answer user queries from uploaded documents (PDFs)
- Collect user details like **name, phone number, email**
- Book appointments using natural language date input (e.g., "next Monday")
- Validate user inputs (email, phone)
- Use **LangChain Agents + Tools** to integrate document retrieval and conversational forms
- Powered by **Google Gemini (Generative AI)** for natural responses

---
## 🔍 Features

- 📄 **Document-based QA**: Ask questions about the contents of any uploaded document
- 💬 **Conversational Form**: Collects and validates user details interactively
- 📅 **Date Parsing**: Understands natural language like “next Friday” or “in 3 days”
- 🔐 **Input Validation**: Ensures proper email and phone number formats
- 🔗 **LangChain Agents + Tools** for modular and dynamic workflows
- ☁️ **Gemini (Google Generative AI)** as LLM backend
---

## 🛠️ Tech Stack

| Tool           | Usage                              |
|----------------|-------------------------------------|
| Python 3.9+    | Base programming language           |
| LangChain      | Chain, Agent, Tools management      |
| Gemini         | LLM for generating answers          |
| FAISS          | Vector store for retrieval          |
| PyPDF          | PDF text extraction                 |
| Dateparser     | Natural language date conversion    |

---
## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
2. Install Requirements
Run in Jupyter or terminal:

