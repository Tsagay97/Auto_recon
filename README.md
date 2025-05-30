# 🤖 AI-Powered Reconciliation System

A smart financial reconciliation tool built using rule-based logic and fuzzy matching. This project automates the reconciliation of financial transactions between the Royal Insurance Corporation of Bhutan Limited (RICBL) and the Bank of Bhutan (BOB).

---

## 📂 Features

- 📤 Upload and process BOB and RICBL bank statements in PDF
- 🧼 Clean and format financial data (drop empty columns, normalize amounts, etc.)
- ✅ Perform **exact** matching on transaction amounts
- 🔍 Use **fuzzy matching** to verify policy/account references across banks
- 📊 Visually display matched and unmatched records in a dashboard
- 💬 Floating chatbot button for future AI interactions (planned)

---

## 🛠️ Technologies Used

| Category        | Tool/Library          |
|----------------|-----------------------|
| Language        | Python                |
| Frontend        | Streamlit             |
| Data Handling   | Pandas                |
| PDF Extraction  | pdfplumber            |
| Fuzzy Matching  | FuzzyWuzzy / RapidFuzz|
| Visualization   | Plotly (planned)      |

---

## 📁 Folder Structure

ICT519_RECON/ ├── app/ │ ├── logic/ # Data cleaning, extraction, fuzzy logic │ └── ui/ # Streamlit UI and styling ├── main.py # Main entry point ├── requirements.txt # Python dependencies ├── .gitignore └── README.md