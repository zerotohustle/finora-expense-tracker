# Finora – Secure AI-Powered Expense Tracker

**Finora** is a smart, privacy-first personal finance tracker that helps users automatically log and manage their expenses using multiple input methods:
- 📩 Gmail e-receipts
- 📱 SMS bank alerts (Android only)
- 📷 Camera receipt capture (OCR)
- 📄 PDF uploads

## 🚀 Features

- ✨ Clean, intuitive UI (built with FlutterFlow)
- 🔐 Secure authentication (Firebase Auth + MFA)
- 🧠 AI-driven insights and predictive spending analysis
- 📊 Custom dashboards and budget tracking
- 🏆 Gamified experience and community tips
- 🔒 Full transparency and encrypted storage

## 🔧 Tech Stack

| Layer       | Tool                     |
|-------------|--------------------------|
| Frontend    | FlutterFlow              |
| Backend     | Firebase (Firestore + Auth + Storage + Functions) |
| OCR         | Google Vision API / Tesseract |
| Email Parse | Gmail API via Make / Functions |
| Storage     | Firebase Secure Storage  |
| Deployment  | GitHub + Firebase Hosting (optional) |

## 📁 Project Structure

```shell
/finora-expense-tracker
├── README.md
├── LICENSE
├── .gitignore
├── /flutterflow         # FlutterFlow export
├── /functions           # Firebase Cloud Functions (Gmail/SMS/OCR)
├── /security            # Firestore/Storage rules
├── /design              # Figma or Canva mockups
└── .github/workflows    # (Optional) CI/CD actions
