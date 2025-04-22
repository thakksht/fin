# 💸 Finandle – AI-Powered Personal Finance Dashboard

**Finandle** is a secure and intelligent personal finance management platform built with ReactJS, Flask, PostgreSQL, and AI-enhanced features. It helps users track their income and expenses, visualize financial habits, and receive actionable insights with the help of machine learning.

---

## 🚀 Tech Stack

- **Frontend:** React.js (TailwindCSS + Recharts)
- **Backend:** Flask (Python)
- **Database:** PostgreSQL
- **AI/Machine Learning:** Scikit-learn, Transformers (for chatbot & NLP)
- **Hosting:** Cloudflare Pages / Cloudflare Workers / R2 (optional object storage)

---

## 🎯 Features

### ✅ MVP Features
- [ ] User Authentication (JWT-based login & signup)
- [ ] Add / Edit / Delete Income & Expenses
- [ ] Categorize Transactions
- [ ] View Monthly and Yearly Financial Summary
- [ ] Pie Chart for Spending Distribution
- [ ] Bar/Line Graph for Trends

---

### 🤖 AI-Powered Features
- [ ] Smart Transaction Categorization (NLP)
- [ ] Budget Forecasting (Regression/Time Series)
- [ ] AI Chat Assistant for Financial Queries
- [ ] Personalized Saving Tips (GPT/TextGen)
- [ ] Overspending Alerts and Insights

---

### 🛠️ Utility Features
- [ ] Import Bank Statement (CSV)
- [ ] Export Reports (PDF)
- [ ] Email Summaries (Weekly/Monthly)
- [ ] Dark Mode Toggle
- [ ] Profile Management
- [ ] Attach Receipt Upload (Optional OCR for parsing)

---

### 🔐 Security
- [ ] Password Hashing using Bcrypt
- [ ] Input Validation (Frontend + Backend)
- [ ] SQL Injection Protection
- [ ] Rate Limiting for API Routes

---

### 🌐 Hosting & Deployment
- [ ] Deploy React Frontend to Cloudflare Pages
- [ ] Host Flask Backend on Render/Cloudflare Workers
- [ ] Set Up PostgreSQL with Supabase/Neon.tech
- [ ] Domain Setup and HTTPS (Cloudflare DNS)

---

### More Features
- [ ] Mobile App with React Native
- [ ] Gamification (Savings Streaks, Achievements)
- [ ] QR Scanner for Bills (OCR)
- [ ] Financial Goal Tracker
- [ ] Multi-Currency & Internationalization Support

## 📁 Project Structure

```bash
finandle/
├── client/              # React Frontend
│   └── src/
│       ├── components/
│       ├── pages/
│       └── assets/
├── server/              # Flask Backend
│   ├── app/
│   │   ├── routes/
│   │   ├── models/
│   │   ├── services/
│   │   └── ai/
│   └── run.py
├── db/                  # SQL scripts and migrations
├── README.md
└── .env.example
