# 👋 Hi, I'm Igor

I am a dual-degree student focused on the intersection of **Applied Computer Science** and **Finance & Accounting**.  

📫 **Reach me at:** [igor.wroblewski.contact@gmail.com](mailto:igor.wroblewski.contact@gmail.com)

---

### 🎓 Education
- **B.Eng. Applied Computer Science** (2nd Year)  
  *University of National Education Commission, Krakow (UKEN)*
- **B.Sc. Finance and Accounting** (1st Year)  
  *Krakow University of Economics (UEK / CUE)*
  
### 🛠 Technical Skills
* **Programming:** Python (Fundamental knowledge).
* **Web Development:** Django, with basic familiarity of HTML, CSS, and TailwindCSS.

### 🌱 Currently Learning
- **Agentic Workflows:** Using AI agents to build awesome projects in an extremely short time—mainly exploring Klio Code (VS Code extension) and Open Interpreter (CLI). At the moment, DeepSeek-V4-Flash is my absolute favorite low-cost model.
 
### 🗣 Languages
- **Polish:** Native.
- **English:** **High B2 / Near-C1** (Scored 179/190 according to Cambridge English Scale).
- **Spanish:** **Passive B1/B2 Fluency**. Strong listening comprehension; I can follow complex content like *Spicy4tuna* or some *Histocast* episodes, though I am still adapting to diverse regional accents.

---

### 💼 Experience

#### **Solo Founder & Developer** | *WycenToSam*
  *07.2026 – Present*

  *   **Status:** Live at [wycentosam.pl](https://wycentosam.pl) – commercial micro-SaaS in production
  *   **Extensive AI-Driven Workflow:** Nearly the entire codebase – backend, frontend, and test suite – was generated via
  intensive AI pair-programming (agentic workflow). Built end-to-end using AI agents, shipped from concept to live
  deployment
  *   **Tech Stack:** Django, Python, Tailwind CSS, JavaScript, Deepgram API, OpenAI API
  *   **Key Features & Responsibilities:**
      *   Built a speech-to-text pipeline using Deepgram API, processing natural-language descriptions of construction
      work into structured JSON schemas via OpenAI
      *   Implemented the full user journey: free estimate generation → account creation → subscription checkout, with a
      clean, no-distraction UI focused on a single CTA

#### **Web Developer** | *WTYMRAZEM Foundation*
  *07.2026 – Present*

  *   **Status:** Live at [wtymrazem.pl](https://wtymrazem.pl)
  *   **Extensive AI-Driven Workflow:** Designed and built a fully functional, responsive website for an NGO focused on
  mental health and well-being. The entire platform was delivered via an extensive AI-driven workflow, shipping the core
  architecture, design, and features in a matter of days
  *   **Tech Stack:** WordPress, Tailwind CSS, AI Agents
  *   **Key Features & Responsibilities:**
      *   Built a multi-page architecture with mobile responsiveness and a dark/light mode toggle
      *   Developed custom UI layouts utilizing TailwindCSS within a WordPress environment
      *   Implemented job application and contact forms routed via IPAM

---

### 🔬 Academic Research & Publications
*I have submitted two scientific papers that will be published as chapters in an upcoming university volume.*

#### **1. AI and Computer Vision in CAPTCHA Verification Tests** *(Submitted)*
A comparative analysis testing the vulnerability and performance of modern AI models against text-based CAPTCHA systems.
*   **Research Scope:** The project involved developing a custom text-based CAPTCHA implementation written primarily in Python. 
*   **Dataset:** The models were tested on 1000 images per category across three distinct types of CAPTCHAs: a custom implementation, an open-source implementation, and a Kaggle dataset.
*   **Methodology:** The experiment benchmarked five AI models (gemini-2.5-flash, grok-4.3, claude-sonnet-4-6, gpt-5.1-2025-11-13, and Qwen3.5-397B-A17B) alongside a human control sample.
*   **Evaluation:** The Levenshtein distance was utilized to calculate the difference between the fully correct answer and the response provided by the models or humans.

#### **2. Analysis of Selected Multimodal AI Models Against Manipulation Under Progressive Input Data Degradation** *(Submitted)*
A co-authored paper exploring the boundaries and vulnerabilities of Vision-Language Models (VLMs) and OCR systems when subjected to visual distortions.
*   **Tech Stack:** The local testing environment was containerized using Docker and utilized physical GPU acceleration. 
*   **Methodology:** The research evaluated four highly optimized open-source models (GLM-OCR, Ministral 3 8B, Qwen2.5-VL, TranslateGemma 12B) and one commercial model (Gemini-2.5-flash).
*   **Research Scope:** The experiment analyzed a custom graphical dataset containing text, which was programmatically degraded using five types of distortions (including Gaussian blur, salt and pepper noise, and compression) across a progressive 20-level intensity scale.
*   **Evaluation:** The accuracy of the models' predictions compared to the original expected strings was verified by calculating the Levenshtein distance.

---

### 🚀 Featured Projects
#### **Homework Class**
A web-based application designed to mimic the student-teacher relationship.
- **Tech Stack:** Python, Django, PostgreSQL (ORM), Cloud Storage (Cloudinary), TailwindCSS.
- **Key Features:**
    - **Role-Based Access Control (RBAC):** Distinct user permissions for students and teachers.
    - **Assignment-Class System:** Students can join desired classes via code and submit assignments, which are then graded by a teacher.
    - **File Upload:** Students can upload their assignments, which are then stored in the cloud.
    - **CRUD:** Teachers can create and edit both assignments and classes.
 
🌐 **Live Demo:** [Click here to view](https://homeworkclass.up.railway.app/)  
*Feel free to explore using the test accounts below:*
* **Teacher Login:** `Teacher` / `TeacherDemo123`
* **Student Login:** `Student` / `StudentDemo123`


#### **Flashcards**
A simple web application to learn via flashcards.
- **Tech Stack:** Python, Django, PostgreSQL (ORM), TailwindCSS.
- **Key Features:**
    - **Custom CAPTCHA For Registration:** While creating an account users have to solve a CAPTCHA.
    - **CRUD for Decks and Cards:** Users can both create and edit decks and cards.
 
🌐 **Live Demo:** [Click here to view](https://flashcardsapp.up.railway.app/)
