🤖 JCS Digitech AI Support Agent
================================

📌 Project Name
---------------
JCS Digitech AI Support Agent

🚀 Short Description
--------------------
An intelligent support chatbot built with LangChain, Streamlit, and OpenAI that answers questions about JCS Digitech's services using real-time web-scraped content.

❓ Motivation / Problem
-----------------------
Clients often have questions about the services offered by JCS Digitech, including website development, SEO, PPC, and more. This project creates a smart AI support agent that automates responses, reducing manual support effort and improving customer experience.

✨ Key Features
--------------
- ✅ Scrapes and embeds real website content from `jcsdigitech.com`
- 💬 Chatbot interface using Streamlit with GPT-4o backend
- 📚 Corrective RAG (Retrieval Augmented Generation) with ChromaDB
- 🔐 Uses `.env` for API key security

📽️ Demo
-------
Live Demo (coming soon): https://share.streamlit.io/your-app-link  
Or run locally:  
`streamlit run app.py`

🧰 Prerequisites
----------------
- Python 3.8+
- OpenAI API Key
- Git (for cloning)
- Virtualenv (recommended)

🛠️ Installation
----------------
```bash
# 1. Clone the repository
git clone https://github.com/your-username/jcs-support-agent.git
cd jcs-support-agent

# 2. Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Add your OpenAI key to a .env file
echo "OPENAI_API_KEY=your_openai_key_here" > .env

# 5. Run the Streamlit app
streamlit run app.py
```

💡 Usage Example
----------------
Once the app is running:
```
🤖 Ask: "What services does JCS Digitech offer?"
🤖 Ask: "How do I get a website developed?"
🤖 Ask: "Tell me about SEO packages"
```

Or interact with the tabs to view static service information and contact details.

⚙️ Configuration
----------------
Environment Variables (stored in `.env`):

```
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

🛣️ Roadmap
-----------
- 🔄 Add conversational memory (long-term history)
- 🌍 Support multilingual queries for global clients
- 📊 Integrate analytics dashboard for query tracking
- 🤖 Deploy as a web widget on the official site
- 🔧 Admin panel to manage and update service info

🤝 Contribution
---------------
Contributions are welcome! Please see the CONTRIBUTING.md for details.

📄 License
----------
This project is licensed under the MIT License — see the LICENSE file for details.

👤 Author & Contact
--------------------
Sharon | JCS Digitech  
📧 info@jcsdigitech.com  
🌐 https://jcsdigitech.com

🙏 Acknowledgements
-------------------
- LangChain (https://www.langchain.com)
- Streamlit (https://streamlit.io)
- OpenAI (https://openai.com)
- BeautifulSoup (https://www.crummy.com/software/BeautifulSoup/)
