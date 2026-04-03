🧠 Job Analyzer

An AI-powered project that uses Google Gemini to analyze a company’s website and its careers page, providing structured insights about the company and relevant job opportunities.

---

🚀 Features

🌐 Scrapes the company website

🏢 Extracts a clear company overview

💼 Fetches job postings from the careers page

🎯 Filters roles based on a user-specified domain (e.g., AI, ML)

🧾 Generates a structured and professional summary

---

🛠️ Technologies Used

Programming Language: Python 3.x

Large Language Model: Google Gemini (gemini-3-flash-preview)

LLM SDK: OpenAI Python SDK (Gemini-compatible API)

Web Scraping: BeautifulSoup4, Requests

Development Environment: Visual Studio Code

---
⚙️ How It Works

1. The user provides a company website URL

2. The system scrapes website content

3. It identifies and extracts the careers page

4. Job listings are collected and processed

5. Gemini analyzes: Company overview, Job descriptions, Relevant roles are filtered based on the selected domain

6. A structured summary is generated and displayed

---

🧩 Technical Implementation

🔹 Architecture
User Input → Web Scraping → Data Processing → Gemini API → Filtered Insights → Output

🔹 Key Components
Web Scraper --> Uses requests + BeautifulSoup to extract website data

LLM Processing --> Gemini API generates summaries and insights

Filtering Logic --> Matches job roles with user-defined domains

Notebook Workflow ---> Implemented step-by-step in code.ipynb

---
🚀 Upgrade (Gradio UI)

This project has been enhanced with a Gradio-based web interface for improved usability and interaction.

---

✨ New Features

🌐 Interactive web UI

⚡ Real-time analysis and results

🎯 Easy input for company URL and domain

---
▶️ Run the Gradio App

    jupyter notebook upgrade_code_with_gradio.ipynb

---

📸 Demo
![App Screenshot](
Job_analyzer.jpeg)

---

💡 Future Improvements

🔍 Advanced job filtering (experience, location, salary)

📊 Dashboard for insights visualization

🤖 Resume matching with job roles

🌍 Support for multiple company comparisons


