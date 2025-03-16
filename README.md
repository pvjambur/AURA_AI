# AURA_AI
Automated User Risk Assesment

## Comprehensive Project Description: AURA - Privacy-first AI-driven Online Proctoring System

### 1. Project Overview
Online examinations currently face significant challenges due to privacy concerns, scalability issues, and high false-positive rates associated with traditional proctoring methods involving continuous audio and video surveillance. AURA addresses these gaps by offering a privacy-first, non-intrusive solution that leverages agent-based behavioral analytics, dynamic risk scoring, and AI-driven anomaly detection to ensure exam integrity seamlessly.

### 2. Gap Analysis
Traditional proctoring approaches rely heavily on constant surveillance via webcam, microphone, and screen recording. These methods often misinterpret normal behaviors such as brief eye movements, ambient noises, or minor distractions as cheating, causing undue stress for students and administrative overhead for institutions. Additionally, such methods suffer from scalability constraints, especially when deployed for large-scale assessments.

### 3. Literature Review
The literature highlights consistent privacy concerns with invasive proctoring technologies. Research indicates students experience heightened anxiety, mistrust towards institutions, and diminished exam performance under surveillance-intensive conditions. Further, literature suggests a strong need for alternative, scalable, and privacy-respecting solutions, emphasizing the potential of AI-driven behavioral analytics and anomaly detection to revolutionize digital assessments.

### 4. Methodology

AURA's implementation involves several key stages:

- **Data Collection & Behavioral Monitoring**: Capturing non-invasive behavioral signals such as keyboard dynamics, mouse interactions, window focus changes, and IP address stability.
- **Agent-based Behavioral Analytics**: Deploying CrewAI and LangChain-based AI agents that continuously analyze behavioral patterns in real-time.
- **Real-time Anomaly Detection**: Using FastAPI and Flask-based Python APIs, behavioral data streams are evaluated instantly to detect anomalies indicative of potential cheating.
- **Dynamic Risk Scoring**: AI algorithms continuously update risk scores, adapting the system’s responses dynamically based on behavioral deviations.
- **Reporting & Feedback**: Comprehensive session summaries, including JSON and PDF reports, enriched by graphical analytics (charts depicting trends and risk breakdowns).

### 5. Results
AURA successfully demonstrates the capability to significantly reduce false positives by accurately distinguishing genuine anomalies from normal test-taking behaviors. Students reported increased comfort and reduced anxiety due to non-invasive monitoring. Educational institutions saw reduced administrative burden and better scalability, resulting in enhanced trust and acceptance of online assessments.

### 6. Technical Stack
- **Frontend**: React.js, Tailwind CSS
- **Backend**: MERN Stack (MongoDB, Express.js, React, Node.js), Flask, FastAPI
- **AI Integration**: CrewAI, LangChain, Hugging Face
- **Workflow Automation**: n8n
- **Deployment & Infrastructure**: Docker, Kubernetes, AWS, GCP, Azure
- **Security & Authentication**: JWT, OAuth
- **Caching & Performance**: Redis
- **CI/CD & DevOps**: GitHub Actions
- **Reporting**: jsPDF, Chart.js, FPDF, matplotlib

### 7. Use Cases
- University-level online assessments
- Professional certification exams
- Corporate training evaluations
- Remote job assessments
- Competitive entrance exams

### 8. Implementation Steps (Step-by-step)
1. **Requirement Analysis**: Identified key issues with existing proctoring tools.
2. **Design and Architecture**: Defined an agent-based, privacy-first monitoring framework.
3. **Frontend Development**: Built a secure React UI with multilingual support and speech synthesis.
4. **Backend & AI Module Development**: Established MERN-based API services and integrated AI agents (CrewAI).
5. **Integration & Automation**: Connected modules via n8n for seamless workflow automation.
6. **Deployment & Testing**: Containerized and deployed the solution on cloud services, utilizing CI/CD for continuous updates.
7. **Evaluation & Feedback**: Conducted pilot testing, gathering user feedback for continuous improvement.

### 9. Supplementary Materials
- Demonstration and explanatory videos highlighting user interactions, system response to anomalies, and reporting features.
- Graphical analysis of real-time risk trends captured during user sessions.
- Detailed documentation and user manuals to guide system administrators and end-users.

---

## Steps to Implement 

### 1. Clone to Repository
```
git clone
```

