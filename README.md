# IIT-Admission-Agent
🎓 IIT Admission Agent (RAG-Based AI)

An AI-powered assistant that simplifies the admission process for IITs using IBM Watsonx.ai and Retrieval-Augmented Generation (RAG).
Students can ask natural language questions about courses, eligibility, fees, deadlines, and receive accurate answers grounded in official IIT admission documents.

📌 Features

Document-Aware Q&A – Answers based on real IIT admission brochures (JEE Advanced, Ph.D., M.Tech, etc.)
LLM-Powered (Granite) – Uses IBM’s Granite 13B Chat model
RAG Architecture – Retrieval-Augmented Generation ensures accuracy
Institute-Wide Support – Built to scale across multiple IITs
Real-Time Interaction – Instant, reliable responses
Built on IBM Cloud – Fully integrated with Watsonx.ai services

🛠️ Technologies Used

IBM Watsonx.ai Studio
IBM Granite Foundation Model (13B Chat)
Retrieval-Augmented Generation (RAG)
LangGraph + ReAct architecture
Vector Index (Document Search)
Python (for document preprocessing)
IBM Cloud Lite Services

🗃️ Project Structure

README.md – Project summary
ppt/ – Final presentation
docs/ – Official admission PDFs (e.g., JEE Advanced brochure, IIT Delhi Ph.D. brochure)
screenshots/ – UI & output examples
prompts/ – Prompt and system instruction files
config/ – Agent tool settings and logic

🧪 Sample Questions to Ask the Agent

What is the eligibility criteria for B.Tech in IITs?
How do I apply for admission through JEE Advanced?
What is the tuition fee for undergraduate programs?
Are there scholarships available at IITs?
What documents are needed during the application process?

🚀 How It Works

Upload official IIT admission brochures into a Watsonx Vector Index
Agent retrieves the most relevant chunks based on user queries
Granite LLM generates accurate responses using retrieved info
LangGraph + ReAct structure handles reasoning and tool usage

📸 Screenshots (to be added in your GitHub repo)

Chat interface with queries
Agent response examples
Watsonx configuration views

🧾 IBM Cloud Services Used

IBM Watsonx.ai Studio
IBM Granite Foundation Model
Watsonx Document Search / Vector Index
IBM Cloud Agent Lab
IBM Cloud Object Storage (optional)

🧠 Future Scope

Expand support to state-level and private institutions
Add multilingual capabilities (Hindi, Tamil, etc.)
Integrate with real-time application tracking systems
Enable voice-based interaction
Personalize responses based on student profiles

🙌 Acknowledgments

Created during IBM AI Internship 2025 using Watsonx.ai and IBM Cloud services.
Thanks to IBM mentors and the Watsonx community for support and guidance.

