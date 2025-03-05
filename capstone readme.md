
# YatriBot

An AI-powered travel assistant that helps users explore destinations, book travel services, and engage in interactive quizzes. The chatbot provides real-time recommendations, travel tips, and booking support, making trip planning seamless and engaging.


## Features

✔️ AI-powered travel chatbot for flight, hotel, and rental car assistance.

✔️ City Explorer to find top landmarks using Google Maps API.

✔️ Gamification with quizzes on travel trivia and a dynamic leaderboard.

✔️ Firestore database for storing scores and user rankings.

✔️ Secure API integration using environment variables.


## Technologies Used


Frontend: Streamlit (Python)

Backend: Firebase Firestore

AI Model: Hugging Face Mixtral-8x7B-Instruct

APIs: Google Maps API, Hugging Face Inference API

Authentication & Security: Environment variables for API key protection.
## Installation Instructions

1.Clone the repository:

git clone https://github.com/SrivarReddy/Capstone-year-2.git  

cd Capstone-year-2  

2. Install dependencies:

pip install -r requirements.txt  

3. Set up Firebase:

Download your Firebase serviceAccountKey.json file.

Place it in the root directory of the project.

4. Create a .env file in the root directory and add your API keys:

HF_API_TOKEN
GOOGLE_MAPS_API_KEY  

5. Run the application 

streamlit run app.py  

## Usage Instructions

Chatbot: Ask travel-related queries to get AI-powered recommendations.

City Explorer: Enter a city name to see top landmarks and participate in a travel quiz.

Leaderboard: View top-scoring users and track your own progress.
## Acknowledgments

Hugging Face for the Mixtral-8x7B AI model

Google Maps API for location-based services

Firebase Firestore for database management

Open-source contributors for making AI-driven projects accessible.

Our CRS mentor Bhanu Ma'am and our coordinator Aruna ma'am for the guidance and support. 




## Screenshots

![YatraBot](https://github.com/SrivarReddy/Capstone-year-2/blob/ac7a79e461bf9d08126ab7de73cdda7b845882ae/image_2025-03-03_114254813.png)

