# Smart India Hackathon Workshop
# Date:26.09.2025
## Register Number:25013033
## Name:SARATHI M
## Problem Title
Smart Crop Advisory System for Small and Marginal Farmers

## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.
Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
Multilingual, AI-based mobile app or chatbot with voice support for low-literate users.
Soil health recommendations and fertilizer guidance based on soil tests and crop history.
Weather-based alerts and predictive insights (disease/pest risk windows).
Pest and disease detection via user-uploaded images (ML model inference).
Market price tracking and simple decision support for when to sell.
Offline-first design with data sync when connectivity is restored; SMS alerts as a fallback.
Feedback loop and usage analytics for continuous improvement.

## Technical Approach
Frontend: Flutter (Android & iOS)
Backend: Node.js with Express
Database: Firebase / MongoDB (user profiles, logs, model metadata)
ML models: TensorFlow / TensorFlow Lite (pest/disease image detection)
APIs & Services: OpenWeather API (weather), Google Translate (optional), Android TTS / platform TTS for voice
Deployment: Docker for backend; Firebase hosting or cloud VM for APIs

## Feasibility and Viability
Feasibility: The system is implementable with existing open-source frameworks and mobile hardware.
Challenges: Low internet availability in rural areas, variability of local crops and languages, collection of labeled datasets for local pests/diseases.
Mitigations: Offline-first design, SMS fallback, crowd-sourcing labeled images paired with expert validation, incremental rollout starting with a few high-priority crops/regions.

## Impact and Benefits
Potential yield increase (estimated 20–30% in pilot regions).
Reduced chemical overuse and improved environmental outcomes.
Economic uplift for small/marginal farmers and increased resilience to climate variability.

## Research and References
<img width="3251" height="2318" alt="image" src="https://github.com/user-attachments/assets/31eb1b38-0343-4cb1-bbe1-70a4aa78df0e" />

NABARD Report, 2022: 86% of Indian farmers are small or marginal.
FAO studies on ICT for agriculture.
OpenWeather API documentation.
PlantVillage dataset for plant disease imagery.
