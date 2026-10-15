# HireSmart AI – Resume Analyzer 🚀

**HireSmart AI** is an AI-powered resume analysis platform designed to help job seekers evaluate their resumes against job descriptions. It analyzes resume content, identifies relevant skills, calculates a similarity score, and helps candidates understand how well their profiles match a particular job role.

## ✨ Features

- 📄 **Resume Upload:** Upload resumes for automated analysis.
- 🧠 **AI-Powered Analysis:** Extract and analyze important information from resumes.
- 🎯 **Job Description Matching:** Compare resume content with job requirements.
- 📊 **Resume Match Score:** Calculate a similarity score using Natural Language Processing (NLP).
- 🛠️ **Skill Analysis:** Identify relevant skills and keywords.
- 💡 **Improvement Suggestions:** Help candidates identify missing skills and areas for improvement.
- 👨‍💼 **Recruiter Dashboard:** Provide a centralized view for reviewing resume analysis results.

## 🛠️ Tech Stack

- **Frontend:** React.js, Vite, HTML, CSS, JavaScript
- **Backend:** Python, FastAPI
- **Machine Learning / NLP:** Scikit-learn, TF-IDF, Cosine Similarity
- **Database:** MongoDB
- **API Communication:** REST API

## 🏗️ Project Architecture

```text
HireSmart-AI/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── main.py
│   ├── requirements.txt
│   └── venv/
│
├── README.md
└── .gitignore
```

*Note: Update the folder structure to match your actual repository.*

## ⚙️ Installation and Setup

### Prerequisites

Install the following before running the project:

- Python 3.10 or later
- Node.js and npm
- MongoDB
- Git

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd HireSmart-AI
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 2. Set Up the Backend

Open a terminal and navigate to the backend directory:

```bash
cd backend
python -m venv venv
```

Activate the virtual environment on Windows:

```powershell
venv\Scripts\activate
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Start the FastAPI server:

```bash
uvicorn main:app --reload
```

Backend API: `http://127.0.0.1:8000`

Interactive API documentation: `http://127.0.0.1:8000/docs`

### 3. Set Up the Frontend

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

Open the local development URL displayed in your terminal, usually:

`http://localhost:5173`

### 4. Configure MongoDB

Ensure MongoDB is running and configure the database connection using environment variables or your project's configuration file.

Never commit database credentials, API keys, or other secrets to GitHub.

## 🔄 How It Works

1. The user uploads a resume.
2. The backend extracts and processes the resume text.
3. NLP techniques convert resume text into numerical representations.
4. The system compares resume content with the job description using cosine similarity.
5. The application generates a match score and relevant analysis.
6. Results are presented through the user interface for further review.

## 🎯 Project Objectives

- Simplify the resume screening process.
- Help candidates tailor resumes to specific job descriptions.
- Reduce repetitive manual resume comparisons.
- Demonstrate practical applications of AI, NLP, and full-stack development.

## 🔮 Future Enhancements

- Integration with large language models for detailed resume feedback.
- Automatic extraction of education, experience, and contact information.
- Resume ranking for multiple applicants.
- Job recommendation based on candidate skills.
- Downloadable resume analysis reports.
- Secure authentication for recruiters and candidates.
- Cloud deployment for public access.

## 🔐 Privacy and Security

- Process resumes securely.
- Restrict access to uploaded candidate information.
- Avoid exposing personal data in logs or public repositories.
- Configure appropriate file validation and upload limits.

## 👨‍💻 Author

**Sai Rakesh**

B.Tech – Computer Science and Engineering (AI & ML)

## 📜 License

This project can be distributed under the MIT License if you choose to release it under that license. Add a `LICENSE` file to the repository before claiming that it is licensed under MIT.

---

⭐ If you find this project useful, consider starring the repository and sharing your feedback!
