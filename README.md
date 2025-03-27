# PrepWise - Your AI-Powered Interview Coach 🚀

<div align="center">
   <img src="/public/logo.svg" alt="PrepWise Logo" width="40"/>
   <h3>Master Your Job Interviews with AI-Driven Practice & Feedback</h3>
</div>

---

## 🌟 Overview

PrepWise is your ultimate companion for interview preparation, blending cutting-edge AI technology with personalized feedback to help you shine in your next job interview. With real-time voice interactions and detailed performance analysis, PrepWise ensures you're always one step ahead.

---

## ✨ Key Features

- 🎙️ **AI Voice Interviews**: Engage in lifelike, real-time voice interviews with an AI interviewer.
- 🧠 **Smart Feedback**: Receive in-depth performance analysis powered by Google's Gemini-2.0-Flash model.
- 🔄 **Diverse Interview Formats**: Practice Technical, Behavioral, or Mixed interviews tailored to your needs.
- 🛠️ **Tech Stack Customization**: Get questions designed specifically for your technology stack.
- 📊 **Performance Insights**: Track your progress with detailed scoring and actionable improvement suggestions.
- 🔒 **Secure & Personalized**: Enjoy a safe and tailored experience with user authentication.

---

## 🛠️ Tech Stack

- **Frontend**: Next.js 15, React 19, TailwindCSS
- **Backend**: Firebase (Authentication & Firestore)
- **AI/ML**: 
  - Google Gemini-2.0-Flash Model
  - VAPI Voice Agent
- **Authentication**: Firebase Auth
- **Storage**: Firebase Firestore

---

## 🚀 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone [repository-url]
   cd prepwise
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   ```bash
   # Create .env.local with the following keys:
   NEXT_PUBLIC_VAPI_WEB_TOKEN=
   NEXT_PUBLIC_VAPI_WORKFLOW_ID=

   GOOGLE_GENERATIVE_AI_API_KEY=

   NEXT_PUBLIC_BASE_URL=

   NEXT_PUBLIC_FIREBASE_API_KEY=
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
   NEXT_PUBLIC_FIREBASE_APP_ID=

   FIREBASE_PROJECT_ID=
   FIREBASE_CLIENT_EMAIL=
   FIREBASE_PRIVATE_KEY=
   ```

4. **Run the Development Server**:
   ```bash
   npm run dev
   ```

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

---

## 🤝 Contributors

- **Core Development Team**: Building the foundation of PrepWise.
- **VAPI Integration Support**: Enhancing voice interaction capabilities.
- **Google Gemini Model Team**: Powering intelligent feedback generation.

---

## 🙌 Acknowledgments

- **VAPI**: For enabling seamless voice interaction.
- **Google**: For the Gemini AI model that powers our feedback system.
- **Firebase**: For providing a robust backend infrastructure.

---

Ready to ace your next interview? PrepWise has got your back! 💼✨
