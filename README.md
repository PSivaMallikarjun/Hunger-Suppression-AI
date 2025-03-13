# Hunger Suppression AI Agent

## Overview
The Hunger Suppression AI Agent is an AI-powered platform designed to minimize food waste and efficiently distribute surplus food to those in need. The system uses **machine learning, location mapping, and real-time chat interaction** to connect food donors (feeders) with people in need (seekers).

## Features
- **Food Matching System:** Uses AI to match surplus food from donors with nearby hungry individuals.
- **Machine Learning Model:** Predicts hunger levels based on location and food availability.
- **Real-Time Mapping:** Visual representation of food donors and seekers using **Folium**.
- **Chatbot Integration:** Allows users to communicate about food donations.
- **Microservices Architecture:** Ensures scalability and flexibility.
- **Cloud Deployment:** Can be hosted on Azure/AWS.

## Technologies Used
- **Python** (Gradio, Pandas, NumPy, Scikit-learn, Folium)
- **Machine Learning** (Random Forest Classifier for hunger level prediction)
- **Location Mapping** (Folium for GPS-based food distribution visualization)
- **Gradio** (Interactive UI with chatbot functionality)

## How It Works
1. **Food donors (Feeders)** register their location, food type, and quantity.
2. **Hungry individuals (Seekers)** register and specify their location.
3. **AI Model** predicts hunger severity and suggests optimal matches.
4. **Real-time Map** displays food availability and seeker locations.
5. **Users communicate via chatbot** to confirm food pickup/delivery.

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/PSivaMallikarjun/Hunger-Suppression-AI
   cd hunger-ai-gradio
   ```
2. Install dependencies:
   ```bash
   pip install gradio pandas numpy scikit-learn folium
   ```
3. Run the application:
   ```bash
   python hunger_ai.py
   ```

## Usage
- **Run the UI**: Opens a Gradio-based web interface where users can enter their details.
- **Food Matching**: Predicts hunger levels and displays the nearest donor.
- **Live Map**: Displays feeder and seeker locations.
- **Chatbot**: Helps users communicate regarding food pickup.

## Future Enhancements
- **AI-powered route optimization** for faster food delivery.
- **Blockchain integration** for secure donation tracking.
- **Mobile App Development** for broader accessibility.
- **Multi-language support** for a global audience.

## License
This project is licensed under the MIT License.

