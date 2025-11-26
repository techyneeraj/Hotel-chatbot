🏨 Hotel Recommendation Chatbot
A Conversational Hotel Search Assistant Powered by NLP & Booking.com API
📌 Overview

The Hotel Recommendation Chatbot is an intelligent conversational system designed to help users find hotels across India through simple, natural-language queries.
Users can type messages like:

“Find me hotels in Mumbai under ₹3000 for 2 nights starting Friday.”

The chatbot automatically extracts the city, budget, dates, and preferences, then fetches real-time hotel data using the Booking.com API (via RapidAPI) and returns the best available options.

This project demonstrates practical integration of NLP + REST APIs + Python + Flask to create a real-world hotel discovery solution.

🚀 Features
🔍 Natural Language Query Understanding

Extracts city, check-in/check-out dates, budget range, and guest preferences.

Recognizes travel-related phrases such as “next weekend”, “under 2000”, or “3-night stay”.

🏨 Real-Time Hotel Search

Uses the Booking.com API through RapidAPI.

Fetches live pricing, availability, reviews, and property details.

🧠 Intelligent Recommendation Engine

Filters hotels by:
✔ Budget
✔ Location relevance
✔ Hotel rating
✔ Availability

Ranks recommendations using custom scoring logic.

🌍 Pan-India Coverage

Supports major cities, including:
Delhi, Mumbai, Bengaluru, Chennai, Hyderabad, Kolkata, Pune, Goa, Jaipur, and more.

💬 Chat-Style Interface

Built with Flask, simulating a real-time messaging experience.

Clean and simple UI for smooth user interaction.

🔐 Secure API Usage

Uses environment variables to safely store API keys.

Prevents issues like 401 unauthorized errors.
