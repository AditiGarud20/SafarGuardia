# SafarGuardia
SafarGuardia is a web-based safety platform for women traveling in the Mumbai Local Train. Developed for the Smart India Hackathon, it uses AI-powered crowd analysis via YOLO (You Only Look Once) to provide safety insights, alerts, and guidance for safer commuting in Mumbai.
🚆 SafarGuardia: Women’s Safety in Mumbai Locals

A specialized web-based safety prototype designed for women commuters in Mumbai. Developed as part of the Smart India Hackathon (SIH), this platform focuses on real-time crowd analytics and community-driven safety alerts within the Mumbai Local train network.

📌 Project Overview

SafarGuardia is a safety-focused prototype aimed at addressing real-world challenges faced by women during local train travel, such as late-night commuting and isolated compartments.

Built using a modern Vite + React (TypeScript) frontend and a Python (Flask) + MongoDB backend, the system integrates intelligent analytics with practical safety tools. It introduces innovative features like:

Compartment crowd density analysis

Station-wise safety indexing

Community-verified safety alerts

🎯 Project Objective

The primary objective of SafarGuardia is to enable predictive safety awareness.

By providing:

Station safety indices

AI-driven crowd analysis

Women commuters can:

Make informed travel decisions

Avoid unsafe conditions

Instantly connect with authorities when required

🛠️ Technologies Used

Frontend

Vite

React

TypeScript

Logic

JavaScript (ES6+)

Backend & Database

Python (Flask)

MongoDB

Data Processing

Pandas

Computer Vision

YOLO (You Only Look Once) for crowd detection and analysis

Version Control

Git & GitHub

🌟 Key Features & Innovation
🚀 Unique SIH Features

📊 Station-wise Crowd Prediction

Color-coded safety index:

🟢 Safe

🟡 Moderate

🔴 Unsafe

Helps users plan safer routes, especially during late hours

📸 Compartment Analysis

Users upload coach images

AI-based logic analyzes crowd density

Suggests actions like “Request Constable” for deserted compartments

👩‍💬 Community Feedback Portal

Women-only platform for reporting issues

Upvote/downvote system ensures authenticity

Spam detection and auto-filtering

🪪 Aadhaar-based Verification (Simulated)

Secure onboarding concept

Ensures a trusted, women-focused community

🛡️ Standard Safety Features

🚨 One-Tap SOS Alert – Instant emergency trigger

📲 Guardian Updates – Real-time alerts to trusted contacts

🗺️ Nearby Safe Spots – Police stations & hospitals map

📞 Fake Call Feature – Simulated incoming call for safety deterrence

🗂️ Project Structure
/
├── src/                # React components (Dashboard, ProfilePage)
├── main.py             # Flask API Entry Point (Port 5001)
├── index.html
├── connect_mongo.py    # MongoDB connection & logging
├── mongo_events.py     # Safety event handling
├── vite.config.ts      # Frontend configuration
├── package.json        # Node.js dependencies
└── README.md           # Documentation
▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/SafarGuardia.git
2️⃣ Frontend Setup
npm install
npm run dev
3️⃣ Backend Setup
pip install flask pandas pymongo ultralytics
python main.py

📍 Backend runs at:
http://127.0.0.1:5001

🚀 Future Enhancements

🎥 Live CCTV Integration
Connect YOLO with real-time railway camera feeds

👮 RPF Dashboard
Dedicated interface for Railway Protection Force monitoring

🌐 Multilingual Support
Expand accessibility with Marathi & Hindi

📄 Conclusion

SafarGuardia transforms women’s safety from reactive response to proactive prevention.

By combining:

AI-powered crowd analytics

Community-driven insights

the platform identifies potential risks before they escalate.

This prototype acts as a scalable bridge between commuters and authorities like the Railway Protection Force (RPF), demonstrating how technology can create a safer, more confident travel experience for women in Mumbai’s local train network.
