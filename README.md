# Project Specification: Code Explainer AI
**Developed By:** Smeara  
**Project Goal:** To make programming education more accessible by helping users understand code faster through AI-powered explanations, learning assistance, and intelligent code analysis.

---

## 💡 System Overview & Problem Statement
Many students, beginner developers, and software engineering bootcamp learners struggle to grasp complex code structures, unfamiliar syntax, and advanced programming logic. Searching through dense, fragmented documentation is time-consuming and overwhelming. 

**Code Explainer AI** addresses this challenge by providing instant, educational, AI-generated explanations and logic breakdowns for multi-language code snippets.

---

## 🖥️ Core Screens Architecture
The application layout features a clean Single-Page Application (SPA) view-switching system consisting of the following 4 core screens:

1. **Home Screen**: Handles project introduction, programming language selection, code input area, and the analyze trigger button.
2. **Code Analysis Screen**: Displays code processing status and active analysis progress animations.
3. **Results Screen**: Displays the Code Summary, Line-by-Line Explanation, Logic Breakdown, Improvement Suggestions, and Error Detection Insights.
4. **About Screen**: Displays the comprehensive Project Overview, Features, Technology Stack, and Developer Information.

---

## 📊 Core Data Model (Entity: CodeSnippet)
The system structures and maps incoming code snippets using these exact data parameters:

* `snippet_id` (String) - Unique programmatic tracking identification string.
* `programming_language` (String) - Selected evaluation language (Python, Java, JavaScript, C++, C#, PHP).
* `code_content` (Text) - Raw source code content string pasted by the user.
* `explanation` (Text) - High-level functional summary and system purpose summary.
* `analysis_result` (Text) - Detailed internal mechanics and line-by-line code logic.
* `suggestions` (Text) - Code quality enhancement tips and optimization recommendations.
* `errors_detected` (Text) - Syntactic flaws, logical exceptions, or clean status reports.
* `uploaded_date` (DateTime) - Accurate system timestamp of the submission request.
* `user_id` (String) - Developer profile identification tracking key.

---

## 🛠️ Technology Pipeline Architecture
* **Frontend UI Layer:** Responsive Semantic Web Core Layout (HTML5, Modern CSS3, Native ES6 JavaScript Rendering).
* **Backend Processing Layer:** Node.js Environment utilizing the Express.js Framework.
* **Database & Storage Layer:** Supabase Platform infrastructure managed by a PostgreSQL cloud instance.
* **Cognitive Intelligence Engine:** Hybrid AI API orchestrations via OpenAI API and Gemini API pathways.

---

## ⚙️ Core System Workflow
1. User uploads or pastes source code snippet into the canvas area.
2. User selects their target programming language from the dropdown menu.
3. User triggers the AI Analysis Engine.
4. System switches view to the Code Analysis Screen showing current progress status.
5. AI processes expressions, variable allocations, conditional statements, and loops.
6. System renders details dynamically inside the structured Results Screen dashboard.
