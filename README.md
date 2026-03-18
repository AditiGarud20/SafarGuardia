🚆 SafarGuardia: Women’s Safety in Mumbai Locals

A specialized web-based safety prototype designed for women commuters in Mumbai. Developed as part of the Smart India Hackathon (SIH), this platform focuses on real-time crowd analytics and community-driven safety alerts within the Mumbai Local train network.

📌 Project Overview

SafarGuardia is a safety-focused prototype aimed at addressing real-world challenges faced by women during local train travel, such as late-night commuting and isolated compartments. Built using a modern Vite + React (TypeScript) frontend and a Python (Flask) + MongoDB backend, the system integrates intelligent analytics with practical safety tools. 

🎯 Project Objective

The primary objective of SafarGuardia is to enable predictive safety awareness.By providing station safety indices and AI-driven crowd analysis
Women commuters can make informed travel decisions, avoid unsafe conditions and instantly connect with authorities when required.

🛠️ Technologies Used

Frontend: Vite, React, TypeScript

Logic: JavaScript (ES6+)

Backend & Database: Python (Flask), MongoDB

Data Processing: Pandas

Computer Vision: YOLO (You Only Look Once) for crowd detection and analysis

Version Control: Git & GitHub

🌟 Key Features & Innovation

Station-wise Crowd Prediction: A Color-coded safety index:
(🟢 Safe,
🟡 Moderate,🔴 Unsafe)
that helps users plan safer routes, especially during late hours

Compartment Analysis: Users can upload coach images, An AI-based logic analyzes crowd density. Also suggests actions like “Request Constable” for deserted compartments

Community Feedback Portal: Women-only platform for reporting issues. Upvote/downvote system ensures authenticity and spam detection and auto-filtering

Aadhaar-based Verification (Simulated): Secure onboarding concept, Ensures a trusted, women-focused community

🛡️ Standard Safety Features

One-Tap SOS Alert – Instant emergency trigger

Guardian Updates – Real-time alerts to trusted contacts

Nearby Safe Spots – Police stations & hospitals map

Fake Call Feature – Simulated incoming call for safety deterrence

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
