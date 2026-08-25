Tripnexa AI is a full-stack Generative AI travel planning platform that creates personalized, budget-aware, and intelligent travel itineraries based on a user's destination, travel dates, budget, interests, preferences, and number of travelers.

It combines GenAI, RAG, AI agents, recommendation systems, route optimization, weather intelligence, and modern web technologies to provide an end-to-end travel planning experience.

✨ Features
🤖 AI-Powered Itinerary Generation
🗺️ Smart Route & Activity Planning
💰 Budget-Aware Trip Planning
🌦️ Weather-Aware Recommendations
🏨 Accommodation Recommendations
🍴 Restaurant & Food Recommendations
🚗 Transportation Suggestions
💬 AI Travel Assistant / Chatbot
🧠 RAG-Based Travel Knowledge
🤝 Multi-Agent AI Architecture
🔄 Dynamic Itinerary Modification
📊 Trip Budget Breakdown
📍 Location & Distance Intelligence
📄 Itinerary Export
🔐 User Authentication
📱 Responsive Modern UI
🎯 Problem Statement

Planning a trip manually requires searching across multiple platforms for destinations, attractions, hotels, restaurants, transportation, weather, and costs.

Voyentra AI brings these activities into a single intelligent platform.

Instead of searching:

"Best places to visit"

"Best restaurants"

"How much will my trip cost?"

"What should I do on Day 2?"

Users can simply tell Voyentra AI:

"Plan a 4-day budget trip to Hyderabad for two people interested in history, food, and photography."

The AI generates a personalized itinerary based on those requirements.

🧠 How It Works
                    USER
                      │
                      ▼
              Trip Preferences
                      │
                      ▼
              Voyentra AI Engine
                      │
       ┌──────────────┼──────────────┐
       ▼              ▼              ▼
 Destination      Activity        Budget
    Agent           Agent          Agent
       │              │              │
       └──────────────┼──────────────┘
                      ▼
                Weather Agent
                      │
                      ▼
              Route Optimization
                      │
                      ▼
              Itinerary Agent
                      │
                      ▼
             Personalized Trip
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
     Web Dashboard            AI Chat
🤖 AI Architecture

Voyentra AI uses specialized agents for different travel-planning tasks.

Destination Agent

Analyzes the destination and identifies relevant:

Attractions
Tourist spots
Local experiences
Neighborhoods
Cultural locations
Activity Agent

Recommends activities based on:

User interests
Duration
Budget
Location
Activity type
Budget Agent

Calculates and optimizes:

Accommodation
Food
Transportation
Activities
Miscellaneous expenses
Weather Agent

Analyzes weather conditions and recommends alternatives when outdoor activities may not be suitable.

Route Agent

Optimizes the order of activities to reduce unnecessary travel.

Itinerary Agent

Combines all recommendations and generates the final day-by-day itinerary.

Travel Assistant

Allows users to modify their itinerary using natural language.

Example:

User:
Make Day 2 cheaper.

AI:
I've replaced two paid activities with
lower-cost alternatives and reduced the
estimated Day 2 cost.
🔎 RAG Architecture

Voyentra AI uses Retrieval-Augmented Generation (RAG) to provide more reliable travel information.

Travel Knowledge Base
        │
        ▼
Document Processing
        │
        ▼
Chunking
        │
        ▼
Embeddings
        │
        ▼
Vector Database
        │
        ▼
Semantic Search
        │
        ▼
Relevant Context
        │
        ▼
LLM
        │
        ▼
Grounded Response

The knowledge base can contain:

Destination guides
Tourist attractions
Cultural information
Transportation information
Local travel tips
Safety information
Food information
🛠️ Technology Stack
Frontend
React.js
TypeScript
Vite
Tailwind CSS
React Router
Axios
TanStack Query
Lucide React
Recharts
Backend
Python
FastAPI
Pydantic
SQLAlchemy
REST APIs
AI / GenAI
Large Language Models
LangChain / LlamaIndex
RAG
Embeddings
Vector Search
AI Agents
Structured LLM Output
Database
PostgreSQL
Redis
Vector Database / pgvector
APIs
Maps & Places API
Weather API
Hotel API
Currency Exchange API
DevOps
Docker
Git
GitHub
CI/CD
Cloud Deployment
📂 Project Structure
voyentra-ai/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── hooks/
│   │   └── utils/
│   └── package.json
│
├── backend/
│   ├── app/
│   │   ├── api/
│   │   ├── agents/
│   │   ├── models/
│   │   ├── schemas/
│   │   ├── services/
│   │   ├── rag/
│   │   ├── database/
│   │   └── utils/
│   │
│   └── requirements.txt
│
├── data/
│   ├── destinations/
│   ├── attractions/
│   └── travel_guides/
│
├── tests/
│
├── docker-compose.yml
├── .env.example
└── README.md
🚀 Example Use Case
User Input
Destination: Hyderabad
Duration: 3 Days
Travelers: 2
Budget: ₹15,000
Interests:
- History
- Food
- Photography

Travel Style: Budget
AI Output
Day 1 – Historic Hyderabad

09:00 AM
Charminar

11:00 AM
Chowmahalla Palace

01:00 PM
Local Lunch

03:00 PM
Laad Bazaar

06:00 PM
Evening Photography


Day 2 – Forts & Culture

09:00 AM
Golconda Fort

12:30 PM
Lunch

02:00 PM
Qutb Shahi Tombs

05:00 PM
Hussain Sagar


Day 3 – Museums & Food

09:30 AM
Salar Jung Museum

01:00 PM
Lunch

03:00 PM
Local Food Experience

06:00 PM
Necklace Road
💰 Budget Optimization

Voyentra AI automatically estimates trip expenses.

Example:

Total Budget: ₹15,000

Accommodation    ₹5,000
Food             ₹3,000
Transportation   ₹2,500
Activities       ₹2,000
Miscellaneous    ₹1,000
-------------------------
Total            ₹13,500

If the estimated cost exceeds the user's budget, the AI can suggest cheaper alternatives.

🌦️ Weather-Aware Planning

Voyentra AI can adapt an itinerary according to weather conditions.

Example:

Weather Forecast
       │
       ▼
Rain Probability: 80%
       │
       ▼
Outdoor Activity
       │
       ▼
Alternative Activity
       │
       ▼
Indoor Attraction

This allows the itinerary to dynamically adapt to changing conditions.

💬 AI Travel Assistant

Users can interact with their itinerary using natural language.

Examples:

"Make my trip cheaper."

"Add more historical places."

"Remove museums."

"Suggest vegetarian restaurants."

"Give me more photography locations."

"Reduce travel time between activities."

"Make Day 3 more relaxing."

"Add a shopping experience."

"Change my hotel budget to ₹3,000."

The AI updates the itinerary while maintaining the user's original preferences.

🔐 Security

The application follows secure development practices:

JWT authentication
Password hashing
Environment variables
API key protection
Input validation
Rate limiting
Authorization
LLM output validation
Error handling
Secure API communication

Never commit .env files or API keys to GitHub.

⚙️ Installation
1. Clone the repository
git clone https://github.com/YOUR_USERNAME/voyentra-ai.git

cd voyentra-ai
2. Backend setup
cd backend

python -m venv venv

Activate the virtual environment.

Windows:

venv\Scripts\activate

Linux/macOS:

source venv/bin/activate

Install dependencies:

pip install -r requirements.txt
3. Environment variables

Create a .env file:

DATABASE_URL=
REDIS_URL=

LLM_API_KEY=

WEATHER_API_KEY=
MAPS_API_KEY=
HOTEL_API_KEY=

JWT_SECRET=
4. Start backend
uvicorn app.main:app --reload

Backend:

http://localhost:8000

API documentation:

http://localhost:8000/docs
5. Frontend
cd frontend

npm install

npm run dev

Frontend:

http://localhost:5173
🐳 Docker

Run the complete application using:

docker compose up --build

Services:

Frontend
Backend
PostgreSQL
Redis
🧪 Testing

Run backend tests:

pytest

Run frontend tests:

npm test
🔮 Future Enhancements
✈️ Flight booking integration
🏨 Real-time hotel booking
🎫 Activity ticket booking
💳 Expense tracking
👥 Group trip planning
📱 Mobile application
🗣️ Voice-based travel assistant
🌐 Multi-language support
📸 AI-powered destination recognition
🧳 AI packing assistant
🆘 Emergency travel assistant
🧠 Long-term personalized travel preferences
🗺️ Advanced route optimization
🔔 Real-time travel alerts
📊 Key AI Concepts Demonstrated

This project demonstrates practical implementation of:

Generative AI
Large Language Models
Retrieval-Augmented Generation
Prompt Engineering
AI Agents
Multi-Agent Systems
Semantic Search
Vector Databases
Embeddings
Recommendation Systems
Structured LLM Outputs
REST API Integration
AI Workflow Orchestration
Context Management
Dynamic Replanning
👨‍💻 Portfolio Value

Voyentra AI demonstrates the ability to build an end-to-end AI product rather than a simple chatbot.

Skills demonstrated
Python
FastAPI
React
TypeScript
PostgreSQL
REST APIs
Generative AI
RAG
LLMs
AI Agents
Vector Search
Prompt Engineering
External API Integration
Docker
Cloud Deployment
⭐ Project Goal

The goal of Voyentra AI is to make travel planning personalized, intelligent, adaptive, and effortless by combining modern AI technologies with real-world travel data.

Plan less. Explore more. Travel smarter with Voyentra AI. 🌍✨

📄 License

This project is licensed under the MIT License.

GitHub Repository Description
