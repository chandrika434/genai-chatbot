# 🤖 GenAI Chatbot

A Generative AI-powered chatbot that lets users interact with an AI model and receive conversational responses through a simple web interface.

## 🌐 Live Demo

Try the deployed application here:

**[Open GenAI Chatbot](https://genai-chatbot-fchab6cmkt2cndyacndvhe.streamlit.app/)**

## ✨ Features

- Interactive AI-powered conversations
- Generative AI integration
- User-friendly chatbot interface
- API-based language model responses
- Cloud deployment with Streamlit Community Cloud

> Available features depend on the implementation in `chatbot.py`.

## 🛠️ Technologies Used

Update this list if your project uses different tools.

- Python
- Streamlit
- Groq API (if configured in the application)
- Large Language Models (LLMs)
- Git and GitHub
- Streamlit Community Cloud

## 📁 Project Structure

```text
GenAI-Chatbot/
├── chatbot.py
├── requirements.txt
├── README.md
├── .gitignore
└── .env                 # Local only; do not commit
```

## ⚙️ Run Locally

### 1. Clone your repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
```

Replace the placeholders with your GitHub username and repository name.

### 2. Create and activate a virtual environment

**Linux / Ubuntu**
```bash
python3 -m venv venv
source venv/bin/activate
```

**Windows**
```powershell
python -m venv venv
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API credentials

If the app uses Groq, create a local `.env` file:

```env
GROQ_API_KEY=your_groq_api_key_here
```

Get your key from the [Groq Console](https://console.groq.com/). Use the variable name expected by your code if it differs.

**Never commit your `.env` file or publish your API key.**

### 5. Start the application

For a Streamlit app:

```bash
streamlit run app.py
```

Then visit `http://localhost:8501` if it does not open automatically.

## 🧠 How It Works

1. The user enters a message in the chatbot interface.
2. The app sends the message to the configured language model.
3. The model generates a response.
4. The response is displayed in the chatbot interface.

The exact flow depends on the code in `app.py`.

## 🔐 Security

- Keep API keys and tokens private.
- Add `.env`, `venv/`, and `.venv/` to `.gitignore`.
- Store deployment credentials in your hosting provider's secrets settings.
- Never include passwords or API keys in screenshots, public commits, or source code.

Example `.gitignore` entries:

```gitignore
.env
venv/
.venv/
__pycache__/
*.py[cod]
.streamlit/secrets.toml
```

## 🚀 Deployment

This project is deployed on Streamlit Community Cloud.

Live application: https://genai-chatbot-fchab6cmkt2cndyacndvhe.streamlit.app/

To update the deployed app, push your latest project changes to the connected GitHub repository and check the deployment logs if the app does not update successfully.

## 🔮 Possible Improvements

- Conversation history
- Streaming responses
- Support for additional language models
- Document-based question answering
- Speech input and output

## 🎓 Learning Outcomes

This project provides practical experience with Generative AI, language-model API integration, Python, application configuration, GitHub version control, and cloud deployment.

## 👩‍💻 Author
Chandrika T
https://github.com/chandrika434
https://www.linkedin.com/in/chandrika-t-975644367




## 📄 License

Add a license if you plan to distribute this project. If no license is specified, all rights remain with the copyright holder.
