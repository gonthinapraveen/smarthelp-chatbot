# 🤖 SmartHelp AI – Chatbot Deployment with Dialogflow & Firebase

SmartHelp AI is a cloud-powered chatbot built using **Dialogflow Messenger** and deployed with **Firebase Hosting**. It's designed to provide 24/7 customer support and can be easily embedded into any website.

---

## 🚀 Features

- Built with Google Dialogflow
- Answers FAQs and tracks inquiries
- Web-friendly UI via Dialogflow Messenger
- Firebase Hosting for instant deployment
- Lightweight, fast, and mobile-ready

---

## 🧰 Tech Stack

| Tech         | Usage                                |
|--------------|--------------------------------------|
| Dialogflow    | Chatbot creation (NLP & intents)    |
| Firebase      | Hosting static chatbot front-end    |
| HTML/CSS      | UI for the chatbot landing page     |
| Git & GitHub  | Source control and version tracking |

---

## ⚙️ Setup Instructions

### ✅ Prerequisites

- Node.js & Firebase CLI installed
- Git installed
- Google account with Dialogflow + Firebase access

### 🔧 Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/gonthinapraveen/smarthelp-chatbot.git
   cd smarthelp-chatbot 2. Replace Agent ID in index.html
Get your agent ID from Dialogflow → Integrations → Dialogflow Messenger.

html
Copy
Edit
<df-messenger
  intent="WELCOME"
  chat-title="SmartHelp AI"
  agent-id="your-agent-id-here"
  language-code="en">
</df-messenger> 3. Connect to Firebase
bash
Copy
Edit
firebase login
firebase init
firebase deployYour chatbot will now be live at:
🌐 https://my-smart-help-bot.web.app/

🌐 Live Demo
🔗 Click to View SmartHelp AI

✅ Example Use Cases
Order tracking

General FAQs

Feedback or contact automation

Event info or rental support🛠️ Future Enhancements
📈 Integrate with Firestore to log conversations

🌍 Support multi-language responses

🎯 Add intent-based follow-up and context

📤 Email notifications via webhooks

📝 License
This project is licensed under the MIT License

🙌 Credits
Google Dialogflow

Firebase Hosting

Icons by Lucide & Google Fonts






