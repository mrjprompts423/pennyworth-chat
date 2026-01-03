# Pennyworth — AI Portfolio Chatbot (Python)

Pennyworth is a Python-based portfolio chatbot that introduces **Gary L. Jones** to potential employers.  
It answers questions about background, work history, interview availability, and professional links through a clean conversational interface.

This project demonstrates real-world chatbot design, modular Python architecture, and live deployment.

---

## 🚀 Features

- Conversational portfolio assistant
- Rule-based intent routing (clear, testable logic)
- Streamlit chat UI
- Resume-driven responses
- Interview scheduling via Cal.com
- LinkedIn integration
- Hosted on Hugging Face Spaces
- Embedded into a Wix website

---

## 🧠 Tech Stack

- **Python 3**
- **Streamlit**
- Modular conversation logic
- Hugging Face Spaces (deployment)
- Wix (iframe embed)

---

## 📂 Project Structure
pennyworth-chat/
├─ app.py
├─ requirements.txt
├─ README.md
├─ LICENSE
├─ pennyworth/
│ ├─ init.py
│ ├─ knowledge_base.py
│ └─ logic.py
└─ assets/
└─ pennyworthbetapic.png

---

## ▶️ Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
