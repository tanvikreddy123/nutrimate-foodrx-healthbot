Nutrimate: FoodRx HealthBot 🍽️🤖
Your Personalized Nutrition Companion, Powered by AI

Nutrimate-FoodRx-HealthBot is a smart, mobile-first health assistant designed to help users navigate food insecurity and chronic illness through intelligent, evidence-based nutrition support. Built with Flutter and integrated with Google Dialogflow CX, it delivers tailored food guidance, educational content, and empathetic AI conversations — all grounded in trusted dietary sources like the DASH plan and MyPlate.

🌟 Features
🍏 Personalized Chatbot Support
Engage with a conversational agent trained on medically accurate content (NIH, MyPlate, DASH). Receive real-time answers to health and diet-related questions.

🧠 Knowledge-Based Conversations
Responses come from a curated document-backed knowledge base, not generic LLMs — ensuring precision, trust, and clarity.

🎯 Health-Aware Tips & Articles
Users receive custom dietary advice and educational tips filtered by their personal health conditions and preferences.

🖼️ Minimal UI with Seamless Navigation
Built using Flutter for cross-platform compatibility and designed in Figma, the interface is clean, accessible, and optimized for mobile UX.

🔐 Secure & Scalable Architecture
All interactions are authenticated using Google Cloud service accounts. Modular backend services ensure scalability and future expansion (e.g., recipe planning, inventory tracking).

🛠️ Tech Stack
Layer	Technology
Frontend	Flutter
AI Chatbot	Dialogflow CX (Google Cloud)
Backend	Node.js
Database	MongoDB Atlas
Design	Figma
Auth	Google OAuth (Service Account)

🚀 Getting Started
1. Prerequisites
Flutter SDK (3.x or higher)

Node.js & npm

Android/iOS emulator or physical device

Access to:

MongoDB Atlas instance

Dialogflow CX agent & service account

2. Clone the Repository
bash
Copy
Edit
git clone https://github.com/<your-username>/nutrimate-foodrx-healthbot.git
cd nutrimate-foodrx-healthbot
3. Install Flutter Dependencies
bash
Copy
Edit
flutter pub get
4. Set Up Backend & Auth
Place your dialogflow_auth.json in a secure location (e.g., assets/)

Configure your .env file (excluded from version control):

ini
Copy
Edit
# MongoDB
MONGODB_URI="your_mongo_uri"

# Dialogflow CX
DIALOGFLOW_PROJECT_ID="your_project_id"
DIALOGFLOW_AGENT_ID="your_agent_id"
DIALOGFLOW_LOCATION="global"
DIALOGFLOW_LANGUAGE_CODE="en"
☑️ Note: Never commit .env files or service account keys to your repo.

5. Run the App
bash
Copy
Edit
flutter run
🎥 Demo
Watch the app in action:
🔗 Demo Video Link

Screens include:

Health-focused onboarding

Real-time chatbot interactions

Article suggestions based on user profile

Secure fallback handling for out-of-scope queries

🧪 Testing
✅ Functional testing on iOS/Android emulators

✅ Chatbot response validation (relevance + fallback)

✅ Secure authentication flows (OAuth, token scope)

✅ UX validation through prototyping & emulator review

👨‍💻 Contributors
Name	Contribution Area
Tanvik Reddy Kotha	Chatbot UI, Dialogflow CX integration, Auth & APIs
Anika Anjum	Knowledge base training, fallback design, CX flows
Jay Hiteshkumar Jariwala	Login & dashboard UI, educational module dev

🧭 Future Directions
📦 Pantry & food inventory tracking

🧑‍🍳 Recipe recommendation system based on health profiles

📊 Nutrition/hydration analytics with daily goals

🔄 Session memory for more natural AI conversations

🧪 Research publication & real-world deployment opportunities

📚 References
NIH DASH Plan

MyPlate by USDA

CDC Nutrition Guidelines

🙌 Get Involved
We welcome feedback and collaboration! Feel free to open an issue or fork the repo to start contributing.
