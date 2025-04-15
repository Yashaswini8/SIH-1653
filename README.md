# Smart India Hackathon Workshop
# Date:15.04.2025
## Register Number:212224220123
## Name:YASHASWINI S
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post

## Problem Creater's Organization
Ministry of defence

## Idea
A web-based simulation platform that replicates real-life boardroom interviews using AI. It dynamically generates questions based on candidate expertise, evaluates response relevance, and scores both candidate answers and interviewer question quality. The system ensures unbiased, data-driven assessments for recruitment and promotions, offering a seamless, immersive interview experience with analytics and performance reports for informed decision-making.

## Proposed Solution / Architecture Diagram

We propose an AI-powered, web-based simulation platform that replicates a real-world boardroom interview environment to streamline recruitment and promotion processes within DRDO. This platform integrates cutting-edge technologies like **natural language processing (NLP)**, **adaptive machine learning**, **bias detection algorithms**, and **real-time video intelligence** to deliver a fair, dynamic, and immersive interview experience for both candidates and panel members.

The system intelligently generates interview questions tailored to a candidate’s area of expertise, experience level, and the job role. Leveraging NLP models like **BERT and GPT fine-tunes**, it constructs domain-specific, context-aware questions in stages: ice-breakers, technical, managerial, and scenario-based. It adapts in real-time, meaning follow-up questions evolve based on the depth and relevance of the candidate’s previous answers.

Candidate responses are semantically analyzed and graded instantly, producing a **Response Relevance Score** and **Confidence Score** using AI algorithms. Parallelly, the system evaluates interviewer input for relevance and fairness, alerting for repetitive, biased, or out-of-domain questioning.

A **virtual interview room** with WebRTC enables real-time audio-video interaction, supported by a chat assistant, shared whiteboard, and optional AI interview co-pilot that suggests better phrasing or re-questions in case of ambiguity.

The platform includes a powerful analytics dashboard for final scoring, performance heatmaps, and bias diagnostics. It generates an automated, human-verifiable **Candidate Suitability Report**, ensuring decisions are data-backed and justifiable.

Future-forward features include optional **emotion detection**, **multi-language support**, and **gamified technical tasks**. This solution redefines traditional interviews by making them intelligent, equitable, and insight-driven — a perfect match for DRDO’s high-stakes scientific recruitment landscape.

---
![image](https://github.com/user-attachments/assets/f70b5c66-d6de-4944-a1be-2461cfec56de)



## Use Cases
Smart Recruitment Panels

AI-curated interviews tailor questions to candidate expertise, ensuring focused evaluation.

Promotion Evaluation Boards

Techno-managerial assessments simulate real scenarios to judge leadership readiness.

Bias-Free Interviewing

System flags biased or irrelevant questions, promoting fairness and objectivity.

Candidate Readiness Testing

Mock interviews with AI scoring help candidates prepare for high-stakes interviews.

Data-Driven Selection

Detailed performance analytics guide panel decisions with transparent, quantifiable insights.

Interviewer Performance Review

Tracks and improves interviewer effectiveness through behavior and bias analytics.


## Technology Stack
🧑‍💻 Frontend
React.js – Interactive UI and component-based architecture

Tailwind CSS – Rapid and responsive styling

Redux / Context API – State management

WebRTC / Jitsi – Real-time video and audio communication

Socket.IO – Real-time chat and event handling

🛠️ Backend
Node.js + Express.js – RESTful API handling and server logic

Python (Flask) – Microservices for AI/NLP operations

JWT / OAuth2 – Secure user authentication and role-based access

🧠 AI / NLP Engine
spaCy / Transformers (BERT, RoBERTa) – Text similarity and response analysis

OpenAI GPT (optional/future) – Advanced dynamic question generation

Scikit-learn / TensorFlow – Scoring models and bias detection algorithms

🗃️ Database
PostgreSQL – Structured data (users, questions, scores, logs)

MongoDB – Unstructured/interview data or session logs

Redis – Caching for real-time performance

📊 Analytics & Visualization
Grafana / Chart.js – Performance dashboards

Elasticsearch – Log and search management for interview insights

☁️ DevOps & Deployment
Docker + Docker Compose – Containerization

Kubernetes (Optional) – Scalable orchestration

AWS / Azure / GCP – Cloud hosting & video services

## Dependencies
The Web-Based Selector-Applicant Simulation Software relies on a robust set of modern dependencies across its frontend, backend, and AI layers to deliver a seamless, intelligent, and scalable interview experience. On the frontend, the application uses React.js for building a responsive and modular interface, with Tailwind CSS for rapid UI styling and responsiveness. React Router DOM handles page navigation, while Axios enables smooth communication with backend APIs. Socket.IO Client supports real-time chat and notifications, and WebRTC (or Jitsi) is used for secure video and audio streaming during live interviews. For data visualization, tools like Chart.js or Recharts are used, while Formik and Yup simplify form creation and validation. Rich text input for interview notes or dynamic question creation is managed using React Quill.

The backend is built on Node.js with Express.js as the primary web framework, offering RESTful API services. JWT (JSON Web Token) ensures secure user authentication and session handling. Bcrypt is used to encrypt passwords before storing them, while Multer handles file uploads such as resumes or images. CORS and Helmet provide security for HTTP requests and API access. Depending on the database choice, Mongoose (for MongoDB) or Sequelize (for PostgreSQL) is used for seamless database operations. Socket.IO on the server handles live events, including chat and system notifications. Dotenv manages environment variables securely.

For AI and NLP, a dedicated Python-based microservice is developed using Flask, integrated with advanced NLP libraries such as spaCy, Transformers, and Sentence Transformers for question generation and response evaluation. Scikit-learn, NLTK, NumPy, and Pandas support semantic analysis and scoring algorithms. The app also uses Redis for session caching and Docker for containerized deployment. Nginx acts as a reverse proxy, while GitHub Actions or Jenkins powers CI/CD automation.



