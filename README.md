
# 📄 ElevateU+ – AI-Powered Resume Parser & Career Assistant

**ElevateU+** is an AI-driven Resume Parser and Career Assistant built during **HackHound 3.0**. It helps users analyze their resumes using Generative AI and receive career-focused insights, including:

- ✅ ATS (Applicant Tracking System) Compatibility Score  
- ✅ Skill Extraction & Skill Gap Analysis  
- ✅ Job Role & Career Recommendations  
- ✅ Personalized Course Suggestions  
- ✅ AI Chatbot for Career Guidance  

> This project combines resume parsing, NLP, and AI integrations to deliver a smarter, more interactive job-seeking experience.

---

## 🚀 Features

- **Resume Parsing** – Extracts key information like name, skills, experience, and education from uploaded resumes.  
- **ATS Compatibility Check** – Evaluates whether the resume passes industry-standard screening tools.  
- **Skill Gap Analysis** – Detects missing or underrepresented skills based on job market expectations.  
- **Job Role Suggestions** – Recommends suitable job profiles based on parsed resume content.  
- **Personalized Course Recommendations** – Leverages Generative AI to suggest upskilling opportunities.  
- **AI Career Assistant (Chatbot)** – Enables career-focused conversations and suggestions using OpenAI’s API.  

---

## 🛠️ Tech Stack

| Layer      | Tech Used                                |
|------------|-------------------------------------------|
| Frontend   | React.js (UI/UX)                         |
| Backend    | Node.js, Express.js                     |
| Database   | MongoDB (for storing user/resume data)  |
| AI/NLP     | OpenAI API (GPT), PDF parsers, NLP libs |
| Auth       | JWT-based authentication                |

---

## 📂 Folder Structure

```

ElevateUplus/
├── backend/
│   ├── routes/
│   ├── utils/
│   ├── config.js
│   └── server.js
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── App.js
│   └── index.js
│
└── README.md

````

---

## 🔧 Installation & Setup

> Make sure you have Node.js, npm, and MongoDB installed.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Neetworm/ElevateUplus.git
cd ElevateUplus
````

### 2️⃣ Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd ../frontend
npm install
```

### 3️⃣ Setup Environment Variables

In the `backend/` folder, create a `.env` file and add:

```env
OPENAI_API_KEY=your_openai_api_key
MONGO_URI=your_mongodb_connection_uri
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the Application

#### Backend

```bash
cd backend
npm start
```

#### Frontend

```bash
cd ../frontend
npm start
```

---

## 📜 How to Use

1. Upload a resume (PDF or DOCX format).
2. The backend parses the resume to extract relevant details.
3. The AI model analyzes the data and returns:

   * ATS compatibility score
   * Skill gaps and recommendations
   * Matching job roles
   * Relevant online courses
4. Use the chatbot for real-time, personalized career guidance.

---

## 🌱 Future Enhancements

* 🌐 OAuth login (Google/LinkedIn)
* 📊 Admin/user dashboard with resume insights
* 🤖 Custom-trained AI model for career counseling
* 📄 Resume builder with ATS optimization
* 🔎 Live job listing APIs (LinkedIn, Indeed)

---

## 🤝 Team Acknowledgment

This project was originally developed during **HackHound 3.0** in collaboration with teammates.

**Original GitHub Repo**: [hardik5harma/elevateuplus](https://github.com/hardik5harma/elevateuplus)

This version is maintained independently under my profile for personal demonstration, future enhancements, and open-source contributions.

---

## 🧑‍💻 Contributions

Contributions are welcome!
Feel free to fork the repo, raise issues, or submit pull requests.

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

**Garvit Ghai**
📧 [garvitghai880@gmail.com](mailto:garvitghai880@gmail.com)
🔗 GitHub: [Neetworm](https://github.com/Neetworm)

⭐ Star this repo if you found it useful!

```
