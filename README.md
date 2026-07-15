# 🌤️ Clima – AI Weather Assistant

Clima is an AI-powered weather application built with **React**, **TypeScript**, **Vite**, and the **Google Gemini API**. Rather than simply displaying weather information, Clima acts as an intelligent assistant by providing personalized recommendations, AI-generated daily briefings, travel and activity planning, and an interactive weather chat experience.

---

## ✨ Features

- 🌦️ **Real-Time Weather Dashboard**
  - Current temperature
  - Humidity
  - Wind speed
  - Air pressure
  - Visibility
  - UV Index
  - Weather conditions

- 🤖 **AI Weather Assistant**
  - Ask weather-related questions in natural language.
  - Receive personalized responses powered by Google Gemini AI.

- 📰 **AI Daily Briefing**
  - Generates a smart morning/evening weather summary.
  - Highlights important weather events.
  - Provides clothing and activity recommendations.

- 🧳 **AI Activity Planner**
  - Suggests suitable outdoor and indoor activities.
  - Packing recommendations.
  - Weather-based travel advice.

- 🗺️ **Interactive Weather Map**
  - Visual representation of weather conditions.
  - Easy-to-understand interface.

- 📊 **Historical Weather Analytics**
  - Weather trends.
  - Historical comparisons.
  - Data visualization.

- ⚙️ **Custom User Preferences**
  - Preferred units
  - Personalized weather recommendations
  - AI response customization

- 💬 **Interactive AI Chat Panel**
  - Conversational weather assistant
  - Follow-up questions
  - Context-aware responses

---

## 🛠️ Tech Stack

### Frontend
- React 19
- TypeScript
- Vite
- Tailwind CSS
- Lucide React Icons
- Recharts
- Motion

### Backend
- Node.js
- Express


---

## 📁 Project Structure

```
clima/
│
├── src/
│   ├── components/
│   │   ├── AIChatPanel.tsx
│   │   ├── AIPlanner.tsx
│   │   ├── DailyBriefing.tsx
│   │   ├── HistoricalAnalytics.tsx
│   │   ├── InteractiveMap.tsx
│   │   ├── PreferencesModal.tsx
│   │   ├── WeatherDashboard.tsx
│   │   └── WeatherIcon.tsx
│   │
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.css
│   └── types.ts
│
├── server.ts
├── package.json
├── vite.config.ts
└── README.md
```

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/clima.git
cd clima
```

### Install dependencies

```bash
npm install
```

### Create environment variables

Create a `.env.local` file:

```env
GEMINI_API_KEY=YOUR_API_KEY
```

You can obtain a Gemini API key from Google AI Studio.

---

## ▶️ Running the Project

Start the development server:

```bash
npm run dev
```

Build the application:

```bash
npm run build
```

Start the production server:

```bash
npm start
```

---

## 📦 Dependencies

Major packages used:

- React
- TypeScript
- Vite
- Express
- Tailwind CSS
- Google Gemini SDK
- Recharts
- Lucide React
- Motion

---

## 🎯 Future Improvements

- Live weather API integration
- GPS location detection
- Multi-day weather forecasting
- Severe weather alerts
- Voice assistant improvements
- Weather notifications
- Mobile application
- Offline caching
- Dark/Light theme switching

---

## 👨‍💻 Author

Developed as an AI-powered weather assistant project using modern web technologies.

---

## 📄 License

This project is available for educational and personal use.
