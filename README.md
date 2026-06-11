

```markdown
<div align="center">

  <!-- Animated Banner -->
  <img src="https://capsule-render.vercel.app/api?text=Placement%20RAG%20Assistant&animation=fadeIn&type=waving&color=0:0f172a,100:1e293b&height=250&section=header&fontSize=60&fontColor=38bdf8&fontAlignY=35" alt="Banner" />

  <!-- Typing Animation -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=38bdf8&center=true&vCenter=true&multiline=true&width=940&height=80&lines=Backend+AI+Engineer+%7C+Full+Stack+Developer;Machine+Learning+Enthusiast+%7C+AWS+%7C+Generative+AI;Building+Intelligent+Systems+for+Placement+Preparation" alt="Typing Animation" />
  </a>
  
  <br/>
  <br/>

  <!-- Badges -->
  <img src="https://komarev.com/ghpvc/?username=Rohit-Pawar&style=for-the-badge&color=0f172a&label=PROFILE+VIEWS" alt="Profile Views" />
  <img src="https://img.shields.io/badge/Status-Production_Ready-success?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
  <img src="https://img.shields.io/badge/Platform-AWS%20%7C%20Render-blue?style=for-the-badge" alt="Platform" />

</div>

---

<br/>
<div align="center">

## 📖 About The Project

</div>

<div align="justify" style="max-width: 900px; margin: 0 auto; padding: 0 20px; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #cbd5e1;">

The **Placement RAG Assistant** is an advanced Retrieval-Augmented Generation (RAG) platform designed to bridge the gap between study materials and effective interview preparation.

Developed by **Rohit Pawar**, an AI/ML and Backend Engineering enthusiast, this project aims to solve the common problem students face: scattered information. By leveraging Generative AI and Vector Databases, this application allows users to upload documents (PDFs, TXT, DOCX) and ask context-aware questions, receive real-time feedback on their resumes, and practice with mock interviews.

It integrates **FastAPI** for robust backend performance, **LangChain** for logic, **Google Gemini** for intelligence, and **FAISS** for semantic search.

</div>

<br/>
<div align="center">

## ✨ Key Features

*   🤖 **AI Chat Assistant:** Context-aware RAG pipeline that answers questions based on your uploaded study notes and documents.
*   📄 **Resume Analyzer:** ATS (Applicant Tracking System) scoring, skill extraction, and actionable improvement suggestions.
*   🎤 **Mock Interview System:** Generates role-specific technical and HR questions to help you prepare.
*   ☁️ **Document Management:** Ingests and indexes files using Vector Embeddings for fast retrieval.
*   🎨 **Modern UI:** A Glassmorphism user interface built with vanilla HTML/CSS/JS.

</div>

<br/>
<div align="center">

## 🛠 Tech Stack

### Backend
<br/>
<img src="https://skillicons.dev/icons?i=python,fastapi,langchain,postgresql,docker,git" alt="Backend" />

### AI & Database
<br/>
<img src="https://skillicons.dev/icons?i=googlecloud,faiss,tensorflow,numpy,pandas" alt="AI/DB" />

### Frontend
<br/>
<img src="https://skillicons.dev/icons?i=html,css,javascript,vscode" alt="Frontend" />

### DevOps & Cloud
<br/>
<img src="https://skillicons.dev/icons?i=aws,nginx,githubactions,linux,bash" alt="DevOps" />

</div>

<br/>
<div align="center">

## 📸 Project Screenshots

*(Add images of your project here)*

![Alt Text](https://via.placeholder.com/400x250?text=Chat+Interface)
![Alt Text](https://via.placeholder.com/400x250?text=Dashboard)
![Alt Text](https://via.placeholder.com/400x250?text=Resume+Analyzer)

</div>

<br/>
<div align="center">

## 🚀 Installation & Setup

### Option 1: Docker (Recommended)

This is the easiest way to run the full stack.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Rohit-Pawar/placement-rag-assistant.git
    cd placement-rag-assistant/backend
    ```

2.  **Environment Variables:**
    Create a `.env` file in the `backend` folder:
    ```ini
    GOOGLE_API_KEY=your_google_gemini_api_key
    DATABASE_URL=postgresql+asyncpg://postgres:password@db:5432/placement_db
    SECRET_KEY=your_secret_key
    ```

3.  **Run:**
    ```bash
    docker-compose up --build
    ```

### Option 2: Local Development

1.  **Dependencies:**
    ```bash
    cd backend
    pip install -r requirements.txt
    pip install "bcrypt<4.0.0" # Required for Windows compatibility
    pip install aiosqlite
    ```

2.  **Database:**
    Update `.env` for local SQLite:
    ```ini
    DATABASE_URL=sqlite+aiosqlite:///./placement.db
    ```

3.  **Create User:**
    ```bash
    python -c "from app.core.database import SessionLocal; from app.models.models import User; from app.core.security import get_password_hash; db = SessionLocal(); u = User(full_name='Demo', email='demo@user.com', password_hash=get_password_hash('password')); db.add(u); db.commit(); print('User Created!'); db.close()"
    ```

4.  **Run:**
    ```bash
    python -m app.main
    ```

</div>

<br/>
<div align="center">

## 👨‍💻 Author & Developer

</div>

<div align="justify" style="max-width: 800px; margin: 0 auto; padding: 0 20px; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #cbd5e1;">

<strong>Rohit Pawar</strong> is a Computer Science undergraduate specializing in AI/ML, Backend Engineering, and Cloud Technologies. With hands-on experience in **Python, FastAPI, AWS**, and **Generative AI**, he builds intelligent systems that solve real-world problems.

**Connect:**
*   📍 **Location:** Nashik, Maharashtra, India
*   📧 **Email:** pawarrohit.x@gmail.com
*   🔗 **LinkedIn:** [linkedin.com/in/rohitpawar](https://linkedin.com/in/rohitpawar-54132a246)
*   🐙 **GitHub:** [Rohit-Pawar](https://github.com/Rohit-Pawar)

</div>

<br/>
<div align="center">

## 🎓 Certifications & Achievements

</div>

<div align="center">
  <!-- Tech Stack Icons used as Badges -->
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 10px; max-width: 800px;">
    <div class="glass-panel" style="background: rgba(30, 41, 59, 0.5); padding: 10px; border-radius: 8px;">
      <strong>CSS3</strong>
      <div style="font-size: 12px; color: #94a3b8;">Styling and Responsive Web Design</div>
    </div>
    <div class="glass-panel" style="background: rgba(30, 41, 59, 0.5); padding: 10px; border-radius: 8px;">
      <strong>Python Programming</strong>
      <div style="font-size: 12px; color: #94a3b8;">Introduction to Programming</div>
    </div>
    <div class="glass-panel" style="background: rgba(30, 41, 59, 0.5); padding: 10px; border-radius: 8px;">
      <strong>AI Adventure</strong>
      <div style="font-size: 12px; color: #94a3b8;">Artificial Intelligence</div>
    </div>
    <div class="glass-panel" style="background: rgba(30, 41, 59, 0.5); padding: 10px; border-radius: 8px;">
      <strong>1-Week AI Training</strong>
      <div style="font-size: 12px; color: #94a3b8;">Intensive Bootcamp</div>
    </div>
  </div>
</div>

<div align="center" style="margin-top: 20px;">
  <img src="https://img.shields.io/badge/Hackathons-10%2B-8b5cf6?style=for-the-badge" alt="Hackathons">
  <img src="https://img.shields.io/badge/Placement_Coordinator-Leadership-0ea5e9?style=for-the-badge" alt="Coordinator">
  <img src="https://img.shields.io/badge/Top_Performer-Department-10b981?style=for-the-badge" alt="Top Performer">
</div>

<br/>
<div align="center">

## 🔗 Quick Links

</div>

<div align="center">
  <a href="https://github.com/Rohit-Pawar" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://linkedin.com/in/rohitpawar" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:pawarrohit.x@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</div>

<br/>
<div align="center">

## 📊 GitHub Analytics

</div>

<div align="center">
  <img width="49.5%" src="https://github-readme-stats.vercel.app/api?username=Rohit-Pawar&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0f172a&title_color=38bdf8&icon_color=38bdf8&text_color=cbd5e1" alt="GitHub Stats" />
  <img width="49.5%" src="https://github-readme-streak-stats.herokuapp.com/?user=Rohit-Pawar&theme=midnight-purple&hide_border=true&background=0f172a&stroke=38bdf8&ring=38bdf8&fire=38bdf8&currStreakNum=cbd5e1&sideNums=cbd5e1" alt="GitHub Streak" />
</div>

<br/>

<!-- Activity Graph -->
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Rohit-Pawar&theme=midnight-purple&bg_color=0f172a&color=38bdf8&line=38bdf8&point=ffffff&hide_border=true" alt="Activity Graph" />
</div>

<br/>
<div align="center">

## 🐍 Contribution Snake

</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/Rohit-Pawar/Rohit-Pawar/output/github-contribution-grid-snake.svg" alt="Snake Animation" />
</div>

<br/>
<div align="center">

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

</div>

<br/>
<div align="center">

  <img src="https://capsule-render.vercel.app/api?section=footer&type=waving&color=0:0f172a,100:1e293b&height=100" alt="Footer" />

</div>
```

### CSS Style for Glassmorphism (Optional Add-on)

The certifications section above uses a class `glass-panel`. To make it look good (since we don't have a separate CSS file here), add this style block at the top of your `README.md` file to ensure the cards look nice if Markdown HTML is rendered:

```html
<style>
.glass-panel {
  background: rgba(30, 41, 59, 0.5); 
  backdrop-filter: blur(10px); 
  border: 1px solid rgba(255, 255, 255, 0.1); 
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
}
</style>
```
