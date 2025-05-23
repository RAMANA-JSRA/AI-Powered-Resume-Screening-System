# 🤖 AI-Powered Resume Screening System with ATS Integration

An intelligent resume analyzer built using Python, Streamlit, NLP, and AI that automatically extracts resume data, scores candidates, recommends improvements, detects teaching eligibility, and matches resumes with job descriptions using Google Gemini.

![Screenshot](./screenshots/ai_resume_interface.png)

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributors](#contributors)
- [License](#license)

---

## 💡 About the Project

The AI-Powered Resume Screening System is designed to assist recruiters and students by providing smart resume analysis. The system reads PDF resumes, parses essential details, evaluates skill fit for industry roles, and offers personalized recommendations and job matching.

Whether you're a recruiter looking to shortlist candidates or a student wanting to improve your resume, this tool empowers decision-making with AI-driven insights.

---

## 🚀 Key Features

- 📄 Resume Upload & PDF Preview
- 🔍 Resume Parsing using NLP (Skills, Email, Contact, Degree, CGPA)
- 📈 Resume Scoring based on matched keywords
- 🎯 Job Role Prediction (Web Dev, Data Science, etc.)
- 🎓 Teaching Eligibility Detection for Ph.D./M.Tech candidates
- 🤖 ATS Job Description Matching using Google Gemini AI
- 📋 Admin Dashboard with full analytics
- 📥 Export Results to Excel
- 🌐 User Geolocation Tracking
- 🔐 Admin/User Mode Separation

---

## 🛠️ Technologies Used

| Category         | Tech/Library                          |
|------------------|----------------------------------------|
| Frontend         | Streamlit, HTML/CSS                   |
| Backend          | Python, MySQL                         |
| Resume Parsing   | PyMuPDF, `re`, spaCy, NLTK            |
| AI/LLM Integration | Google Gemini (via genai)            |
| Visualization    | Plotly, Streamlit Charts              |
| Data Export      | Pandas, openpyxl                      |
| Authentication   | Streamlit session state               |
| Hosting          | Streamlit Cloud / Local Server        |

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-resume-screening-system.git
cd ai-resume-screening-system
