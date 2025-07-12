# Nutrimate: FoodRx HealthBot 🍎🤖  
**Your Personalized Health & Nutrition Chatbot**

Nutrimate is a Flutter-based mobile app designed to empower users managing chronic conditions and food insecurity with personalized nutrition guidance. Combining AI chatbot interaction, diet education, and smart health tips, Nutrimate helps you make better food choices every day.

---

## ✨ Features

- 🍽️ **Personalized Nutrition Assistance**  
  Ask about foods, diet plans (DASH, MyPlate), or medical nutrition, and get reliable answers from a knowledge-grounded AI chatbot powered by Dialogflow CX.

- 🥗 **Health-Aware Recommendations**  
  Receive curated articles and daily nutrition tips tailored to your medical profile.

- 📱 **Minimalist Cross-Platform UI**  
  Smooth, intuitive interface built with Flutter for both Android and iOS.

- 🔒 **Secure Authentication & API Access**  
  User data is protected using Google OAuth2 and service account authentication.

---

## 🛠️ Tech Stack & Architecture

- **Frontend:** Flutter  
- **AI Chatbot:** Google Dialogflow CX  
- **Backend:** Node.js  
- **Database:** MongoDB Atlas  
- **Auth:** Google OAuth (Service Account)  
- **Design:** Figma  

The app follows a modular, feature-first architecture for easy maintenance and scalability.

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (version >=3.0.0 <4.0.0)  
- Node.js & npm  
- Android/iOS device or emulator  
- Access to:  
  - MongoDB Atlas cluster  
  - Dialogflow CX agent  
  - Google Cloud service account JSON key

### Installation Steps

1. **Clone the repository**  
```bash
git clone https://github.com/<your-username>/nutrimate-foodrx-healthbot.git
cd nutrimate-foodrx-healthbot
````

2. **Install dependencies**

```bash
flutter pub get
```

3. **Configure environment variables**
   Create a `.env` file in the project root and add:

```env
MONGODB_URI="your-mongodb-connection-string"
DIALOGFLOW_PROJECT_ID="your-gcp-project-id"
DIALOGFLOW_AGENT_ID="your-dialogflow-agent-id"
DIALOGFLOW_LOCATION="global"
DIALOGFLOW_LANGUAGE_CODE="en"
```

> ⚠️ `.env` is ignored by git. Never commit this file.

4. **Add Dialogflow service account key**
   Place your Google Cloud service account JSON file inside the `assets/` folder as `dialogflow_auth.json`. This file authenticates the chatbot.

> ⚠️ Also gitignored — keep it private.

5. **Run the app**

```bash
flutter run
```

---

## 📚 Documentation & Demo

* See our detailed [Project Wiki](#) for architecture and feature walkthroughs.
* Watch the demo video showcasing the full app experience.

---

## 🙌 Contributing

We welcome contributions! To contribute:

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/your-feature-name`)
3. Make your changes and commit (`git commit -m "Add your message"`)
4. Push the branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request

Please write clean, well-commented code and follow existing patterns.

---

## 🧭 Future Plans

* Pantry & food inventory management
* AI-driven recipe recommendations based on health profile and pantry
* Progress dashboards for daily/weekly tracking
* Improved AI conversation session continuity

---

## 📖 References

* NIH DASH Plan
* MyPlate Guidelines
* CDC Nutrition Recommendations
