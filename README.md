🩺 Diabetes Prediction & Health Dashboard
A React-based web application that helps users monitor vital health metrics and get diabetes risk insights using simple condition-based logic. Supports manual data entry and smartwatch integration (Fitbit/Google Fit).

📌 Features
🚀 Real-time diabetes risk estimation

📊 Tracks glucose, blood pressure, sleep, steps, and weight

⌚ Smartwatch support via Fitbit/Google Fit APIs

🧠 Condition-based logic for risk levels (Low/Medium/High)

📈 Visual charts for health trends

💡 Personalized lifestyle tips

📱 Mobile-friendly responsive design

🛠 Tech Stack
Layer	Technology
Frontend	React.js, TypeScript
Styling	Tailwind CSS
Backend API	Node.js / FastAPI (optional)
Auth & Sync	OAuth2, Fitbit/Google Fit
Database	Firebase Firestore

📷 Screenshots
(Add images or GIFs of your app interface here)

Login/Register screen

Dashboard with health cards

Risk prediction result

Graphs showing trends

⚙️ How It Works
User enters data manually or connects smartwatch

Logic evaluates health input to assign a risk category

Dashboard displays metrics, graphs, and lifestyle tips

Data is stored and visualized over time

📈 Risk Logic (Example)
js
Copy
Edit
if (glucose > 150 || bp > 140) {
  risk = "High";
} else if (glucose > 110 || bp > 120) {
  risk = "Medium";
} else {
  risk = "Low";
}
🔒 Authentication
Google OAuth for sign-in

Fitbit/Google Fit API for syncing health data

🧪 Future Enhancements
Add ML model for smarter predictions

Push alerts for abnormal values

Nutrition and meal tracking

Apple HealthKit integration

📚 References
Fitbit Web API

Google Fit API

Tailwind CSS

React.js

