## 🚀 AI Fast Resume & Career Architect
**AI Fast Resume** is a next-generation career acceleration platform powered by **Google Gemini 3 Pro & Flash**. It goes beyond simple resume editing by offering a full suite of AI-driven tools: ATS optimization, multimodal portfolio generation, strategic career path prediction, and real-time voice/video mock interviews.

![alt text](https://img.shields.io/badge/license-MIT-blue.svg)

![alt text](https://img.shields.io/badge/React-19-61dafb.svg)

![alt text](https://img.shields.io/badge/TypeScript-5.0-blue.svg)

![alt text](https://img.shields.io/badge/AI-Google%20Gemini-8e44ad.svg)

## ✨ Key Features
**1. 📄 Intelligent Resume Optimizer**
- **ATS Analysis**: Scans your resume against a target Job Description (JD) to calculate a match score based on Core Skills, STAR method usage, and Industry Relevance.
- **Deep Parsing**: Extracts experience, volunteer work, and projects from PDF or DOCX files.
- **WYSIWYG Editor**: A fully interactive resume builder with drag-and-drop sections, live text editing, and instant PDF export.
- **Dynamic Templates**: Switch between 5+ professional layouts (Minimalist, Creative, Academic, Grid, Professional) and custom color themes instantly.

**2. 🎨 AI Portfolio Generator**
- **Multimodal Analysis**: Upload images, videos, audio files, or documents. The AI analyzes the content (e.g., visual style, audio composition) and auto-generates professional descriptions and competency tags.
- **Instant Website**: Generates a fully responsive, static HTML portfolio website based on your assets.
- **One-Click Deploy**: Downloads a deploy-ready .zip bundle optimized for Netlify/Vercel or previews the site instantly in the browser.

**3. 🔮 Career Path Predictor**
- **Trajectory Modeling**: Analyzes your project history and skills to predict 3 distinct career paths (e.g., Specialist vs. Managerial).
- **Gap Analysis**: Identifies specific skill gaps between your current state and your target role.
- **Strategy Reports**: Generates downloadable PDF strategy documents including interview prep, portfolio advice, and salary projections.

**4. 🎤 AI Mock Interview Lab**
- **Real-time Simulation**: Conducts voice-to-voice interviews using browser Speech Recognition and Synthesis.
- **Vision Analysis**: (Optional) Uses the camera to analyze facial expressions (confidence, eye contact) during the interview.
- **Performance Reports**: Generates a harsh, detailed scorecard after the session, highlighting transcript strengths, weaknesses, and improvement areas.

**🛠️ Tech Stack**
- **Frontend**: React 19, TypeScript, Tailwind CSS
- **AI Core**: @google/genai SDK (Models: gemini-3-flash-preview)
- **Document Handling**:
   - html2pdf.js (High-fidelity PDF generation)
   - mammoth.js (DOCX parsing)
   - jszip (Portfolio bundling)
- **Browser APIs**: Web Speech API (Recognition/Synthesis), MediaStream API, AudioContext.

## 🚀 Try Demo
https://fastresume-jane-zhang-220567865154.us-west1.run.app

## 📖 Usage Guide
**1. Resume Builder**:
   - Paste a Job Description.
   - Upload your existing PDF/DOCX resume.
   - Click "Optimize".
   - Review the score, select valid experiences, and enter the Editor to customize the layout.
**2. Portfolio AI**:
   - Switch to the "Portfolio AI" tab.
   - Drag and drop project files (Images, MP4s, PDFs).
   - Let AI generate titles and summaries.
   - Select a design system (Pop, Retro, Studio, etc.) and download the website bundle.
**3. Career Path**:
   - Switch to "Career Path".
   - The AI will map your trajectory based on your loaded resume and portfolio items.
   - Click "View Strategy" on a path to generate a PDF roadmap.
**4. Mock Interview**:
   - Switch to "Interview".
   - Select mode (Voice, Text, or Face).
   - The AI Recruiter (Olivia or James) will conduct the interview based on the JD context.

## 🤝 Contributing
Contributions are welcome! Please follow these steps:
1. Fork the project.
2. Create your feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## ⚠️ Disclaimer
This application uses Artificial Intelligence to generate content. While it strives for accuracy, always review generated resumes, cover letters, and career advice before submitting them to employers. The AI Career Coach provides suggestions, not professional financial or legal career counseling.
