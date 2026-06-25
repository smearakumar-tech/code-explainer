# Project Specification: Code Explainer AI
**Developed By:** Smeara  
**Project Goal:** To make programming education more accessible by helping users understand code faster through AI-powered explanations, learning assistance, and intelligent code analysis.

---

## 💡 System Overview & Problem Statement
Many students, beginner developers, and software engineering bootcamp learners struggle to grasp complex code structures, unfamiliar syntax, and advanced programming logic. Searching through dense, fragmented documentation is time-consuming and overwhelming. 

**Code Explainer AI** addresses this challenge by providing instant, educational, AI-generated explanations and logic breakdowns for multi-language code snippets.

---

## 🖥️ Core Screens Architecture
The application is structured into 4 foundational screens built explicitly into the interface:

1. **Home Screen**: Features a project introduction, programming language selection selection box, a code input canvas area, and the action analyze button.
2. **Code Analysis Screen**: Displays the current code processing status and active analysis progress tracking metrics.
3. **Results Screen**: Displays the Code Summary, Line-by-Line Explanation, Logic Breakdown, Improvement Suggestions, and Error Detection Insights.
4. **About Screen**: Displays the comprehensive Project Overview, Features list, Technology Stack details, and Developer Information.

---

## 📊 Core Data Model (Entity: CodeSnippet)
The application handles code management utilizing these exact structured schema fields:
- `snippet_id` (String) - Unique programmatic tracking identification string.
- `programming_language` (String) - Selected evaluation language (Python, Java, JavaScript, C++, C#, PHP).
- `code_content` (Text) - Raw source code content string pasted by the user.
- `explanation` (Text) - High-level functional summary and system purpose summary.
- `analysis_result` (Text) - Detailed internal mechanics and line-by-line code logic.
- `suggestions` (Text) - Code quality enhancement tips and optimization recommendations.
- `errors_detected` (Text) - Syntactic flaws, logical exceptions, or clean status reports.
- `uploaded_date` (DateTime) - Accurate system timestamp of the submission request.
- `user_id` (String) - Developer profile identification tracking key.

---

## 🛠️ Technology Pipeline Architecture
- **Frontend Layer:** Responsive Web Application (HTML5, Modern CSS3, Native ES6 JavaScript).
- **Backend Layers:** Node.js Ecosystem with Express.js Framework platforms.
- **Database Architecture:** Supabase Cloud Infrastructure powered by PostgreSQL instances.
- **AI Integration Engine:** OpenAI API Configurations and Gemini API Web Pipeline access ports.
