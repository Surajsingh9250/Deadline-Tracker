📅 Deadline Tracker – AI-Powered Productivity Assistant

Deadline Tracker is an AI-powered application designed to help users organize tasks, manage deadlines, and avoid missing important submissions or activities. It uses Google Gemini AI to generate helpful deadline summaries and integrates WhatsApp messaging through Twilio for sharing reminders and updates.

✨ Features

- 🤖 AI-Powered Assistant: Uses Google Gemini AI to understand user queries and provide helpful responses.
- 📅 Deadline Management: Helps users organize tasks and keep track of important deadlines.
- 💬 WhatsApp Integration: Supports sending deadline summaries through WhatsApp using Twilio.
- 📝 AI-Generated Summaries: Generates concise summaries to help users review upcoming tasks.
- 🖥️ Interactive Interface: Built using Streamlit for a simple and user-friendly experience.

🛠️ Technologies Used

- Python
- Streamlit
- Google Gemini API
- Twilio WhatsApp API
- Git and GitHub

⚙️ Installation and Setup

1. Clone the repository

git clone https://github.com/Surajsingh9250/Deadline-Tracker.git
cd Deadline-Tracker

2. Create a virtual environment

python -m venv venv

Activate it on Windows:

venv\Scripts\activate

3. Install dependencies

pip install -r requirements.txt

4. Configure API keys

Create a ".streamlit/secrets.toml" file and add your own API credentials:

GEMINI_API_KEY = "your_gemini_api_key"
TWILIO_ACCOUNT_SID = "your_twilio_account_sid"
TWILIO_AUTH_TOKEN = "your_twilio_auth_token"

Never upload real API keys or credentials to GitHub.

5. Run the application

streamlit run app.py

🔐 Security

Keep all API keys and credentials private. Store them in Streamlit secrets and ensure that secret files are excluded from version control.

🚀 Deployment

The application can be deployed using Streamlit Community Cloud by connecting the GitHub repository and configuring the required secrets.

👨‍💻 Developer

Suraj Singh

GitHub: "Surajsingh9250" (https://github.com/Surajsingh9250)

📄 License

This project is developed for educational and learning purposes.