# Financial-News-Simplifier
inNews AI is an AI-powered web application designed to make complex financial news simple, clear, and easy to understand. The platform helps students, beginners, retail investors, and professionals quickly understand financial events without requiring advanced financial knowledge.  

Readme
📰 FinNews AI — Financial News Simplifier

FinNews AI is a full-stack AI-powered web application that simplifies complex financial news.

It uses NewsAPI to retrieve the latest financial news from multiple sources.

The application uses Groq's Llama 3.3 70B model to analyze and simplify financial articles.

The goal is to make financial information easier to understand for beginners, students, and general readers.

✨ Features
📰 Fetch latest financial news
🤖 AI-powered news simplification
🧠 Powered by Groq Llama 3.3 70B
🔎 Search financial news
📂 Browse news by categories
💡 Explain complex financial terms
📱 Responsive interface
⚡ Fast API-powered backend
🔐 Secure API key management
❌ Proper error handling
⏳ Loading states and animations
🌐 Full-stack single application
🎯 Objective

Financial news often contains complex terminology and market jargon.

FinNews AI converts this complicated information into concise and beginner-friendly explanations.

Users can understand important financial events without reading lengthy or highly technical articles.

🛠️ Tech Stack
Frontend
HTML5
CSS3
JavaScript
Backend
Python
FastAPI
REST APIs
AI
Groq API
Llama 3.3 70B
News Data
NewsAPI
Tools
Git
GitHub
VS Code
🏗️ Architecture
User
  ↓
FinNews AI Interface
  ↓
FastAPI Backend
  ↓
NewsAPI
  ↓
Financial News
  ↓
Groq Llama 3.3 70B
  ↓
Simplified Summary
  ↓
Frontend
  ↓
User
📁 Project Structure
finnews-ai/
│
├── app/
│   ├── main.py
│   ├── services/
│   │   ├── news_api.py
│   │   └── ai_service.py
│   ├── models/
│   │   └── schemas.py
│   ├── templates/
│   │   └── index.html
│   └── static/
│       ├── css/
│       │   └── style.css
│       └── js/
│           └── script.js
│
├── .env
├── .gitignore
├── requirements.txt
└── README.md
🔄 How It Works
The user opens FinNews AI.
The user clicks Fetch & Simplify.
FastAPI receives the request.
The backend requests financial news from NewsAPI.
News articles are retrieved.
Article information is processed by the backend.
Relevant content is sent to Groq.
Llama 3.3 70B analyzes the content.
The AI generates a simplified explanation.
FastAPI sends the result back to the frontend.
The simplified news is displayed to the user.
🤖 AI Capabilities

The AI can:

Identify the main event.
Simplify financial terminology.
Summarize important information.
Explain difficult concepts.
Present information in beginner-friendly language.
Preserve important facts from the article.

The AI is designed to avoid unsupported information and fabricated facts.

🔌 API Endpoints
GET /

Checks the application status.

GET /health

Checks backend health.

GET /news

Fetches the latest financial news.

POST /simplify

Generates an AI-powered simplified summary.

POST /explain

Provides a simple explanation of a financial term.

🔐 Environment Variables

Create a .env file:

NEWS_API_KEY=your_newsapi_key
GROQ_API_KEY=your_groq_api_key

API keys should never be exposed in frontend JavaScript.

The .env file should also be added to .gitignore.

🚀 Installation

Clone the repository:

git clone <repository-url>

Move into the project directory:

cd finnews-ai

Install dependencies:

pip install -r requirements.txt

Create your .env file and add the required API keys.

▶️ Run the Application

Start the FastAPI server:

uvicorn app.main:app --reload

Open the application in your browser through the local server address.

🎨 Design

FinNews AI uses a Midnight Plum × Electric Violet visual theme.

The interface combines:

Dark editorial design
Glassmorphism
Electric violet accents
Neon pink highlights
Soft lavender elements
Smooth animations
Responsive layouts

The design is inspired by modern AI and financial intelligence platforms.

⚠️ Disclaimer

FinNews AI provides simplified financial information for educational and informational purposes only.

It does not provide personalized financial advice, investment recommendations, or guaranteed market predictions.

Users should verify important information using the original news source.

🔮 Future Improvements
User authentication
Personalized news feeds
Saved articles
News sentiment analysis
Market trend visualization
More AI explanation modes
Multiple language support
Database integration
User reading history
Advanced financial topic filtering
👩‍💻 Skills Demonstrated
Python
FastAPI
REST API Development
JavaScript
HTML5
CSS3
Generative AI
LLM Integration
API Integration
Environment Variables
Git & GitHub
Responsive Web Development
📌 Project Status

Status: Active Development

FinNews AI demonstrates how Generative AI and real-time financial data can be combined to make complex financial information more accessible.

📄 License

This project is created for educational and development purposes
