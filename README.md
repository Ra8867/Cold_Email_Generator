❄️ Cold Email Generator using LLMs 🚀
This project is an AI-powered Cold Email Generator built using LangChain, Groq, and Streamlit. It helps users quickly craft personalized, professional cold emails tailored to specific roles, skills, and industries.

🔧 Tech Stack:
LangChain – for chaining prompts and managing LLM workflows

Groq API – for high-performance LLM inference (using models like Mixtral)

Streamlit – to build an intuitive and interactive front-end

Python-dotenv – for managing API keys securely

BeautifulSoup (bs4) – for optional web content scraping

FAISS / ChromaDB – for vector-based document search (if used)

✨ Features:
🧠 LLM-based Email Generation: Auto-generates customized cold emails from a few user inputs

✍️ Context-Aware Content: Tailors messaging based on recipient background, skills, or job roles

🌐 Web-based Interface: Built using Streamlit for easy interaction

🔐 Environment-secure Config: Uses .env for managing sensitive keys securely

🧪 (Optional) Document/Job Page Scraping: Extracts relevant info to enhance email personalization


📌 Use Cases:
Job seekers reaching out to recruiters

Freelancers pitching services to potential clients

Startups sending intro emails to investors or collaborators

🚀 How to Run the Cold Email Generator Project
📦  Clone the Repository

 Install Requirements: pip install -r requirements.txt
 
Add your API key(s):
GROQ_API_KEY=your-groq-api-key-here

Run the Streamlit App
streamlit run app/main.py

