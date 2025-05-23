# 🤖 AI-Powered Resume Screening System with ATS Integration

An intelligent resume analyzer built using Python, Streamlit, NLP, and AI that automatically extracts resume data, scores candidates, recommends improvements, detects teaching eligibility, and matches resumes with job descriptions using Google Gemini.

![Screenshot](https://github.com/user-attachments/assets/342f5ce8-c662-416d-94fa-c1af7b5f0034)

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

```

### 2. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```
### 3. Install Requirements

```bash
pip install -r requirements.txt
```
### 4. Start the Streamlit App
```bash
streamlit run App.py
```
### 📷 Screenshots

## Resume Preview!

![Screenshot (525)](https://github.com/user-attachments/assets/342f5ce8-c662-416d-94fa-c1af7b5f0034)
![Screenshot (526)](https://github.com/user-attachments/assets/7f0b190e-ef3a-4b90-9520-153dc4bc3aa0)
![Screenshot (527)](https://github.com/user-attachments/assets/59aeb32b-f53a-49f7-b545-4304fe459fd1)
![Screenshot (528)](https://github.com/user-attachments/assets/b0e45424-c5b7-46af-9c78-8ef04d5f4632)
![Screenshot (529)](https://github.com/user-attachments/assets/e38f9b69-1b6b-4060-b55a-809b55312507)

### Admin Page

![Screenshot (531)](https://github.com/user-attachments/assets/94d0e247-1706-44e8-8f89-1f5d98e77788)

## FeedBack Page

![Screenshot (532)](https://github.com/user-attachments/assets/54737b28-991b-4cc6-8e5a-72e2c61382a7)

## ATS_Gemini

![Screenshot (533)](https://github.com/user-attachments/assets/6b1fde8a-2531-4738-8b63-4ab0cd1094b3)


## 👨‍💻 Contributors

    Ramana J S – @RAMANA-JSRA

    Team Members: Akila Sanjana , Meenatchi Sundaram S 

Developed as a Capstone Project at Vellore Institute of Technology – AP.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📬 Feedback

For suggestions, feel free to open an issue or drop an email [ramana12js@gmail.com].

    “Transforming Resume Analysis through the Power of AI” 💼🤖
    
