# **Dyslexi-AI: Early Detection and Therapy with Multi Feature**

## **Overview**

**Dyslexi-AI** is a gamified platform designed to assist in the early detection and therapy for dyslexia. The platform leverages educational games to track a user's progress, adjust difficulty levels dynamically using Q-learning, and provide personalized feedback. It includes various interactive games aimed at improving the skills of dyslexic students, such as the **Phonics Game**, **Rhyme Race**, **Sequence Sorter**, and others, while focusing on learning and cognitive development.

The platform also includes a comprehensive system for tracking user performance, awarding badges, providing a leaderboard, and offering personal dashboards with graphs that show overall improvement across games.

## **Key Features**

- **Q-learning-powered Difficulty Adjustment**: Dynamic difficulty adaptation based on user performance.
- **Multilingual Support**: The platform supports multiple languages (English, Kannada, Hindi) to cater to a diverse user base.
- **Gamification**: Includes badges, points, daily streaks, and weekly challenges to motivate users.
- **User Performance Tracking**: Detailed user dashboards displaying progress, performance, and earned badges.
- **Leaderboard**: Display users' points, accuracy, and rankings across games.
- **Interactive Educational Games**: Games like Phonics, Rhyme Race, and Sequence Sorter are designed to help with dyslexia therapy.

## **Technologies Used**

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js, MongoDB
- **Database**: MongoDB (for storing user stats, points, accuracy, and badges)
- **Game Logic**: Q-learning algorithm for dynamic difficulty adjustment
- **Realtime Data**: Supabase for storing and fetching session data
- **Authentication**: JWT (JSON Web Tokens) for user authentication

## **Project Structure**

```bash
Dyslexi-AI/
│
├── backend/                         # Node.js and Express backend
│   ├── controllers/                 # Controllers for API routes
│   ├── models/                      # Mongoose models for MongoDB
│   ├── routes/                      # API route definitions
│   ├── services/                    # Business logic services (e.g., Q-learning)
│   ├── app.js                       # Express app configuration
│   ├── config.js                    # Environment and database configuration
│
├── frontend/                        # React frontend
│   ├── components/                  # React components (e.g., game UI, user dashboard)
│   ├── pages/                       # Page-level components (e.g., home, profile)
│   ├── App.js                       # Main React component
│   ├── tailwind.config.js            # Tailwind CSS configuration
│   ├── public/                      # Static files
│
├── database/                        # MongoDB database schema and seeding scripts
│
├── README.md                        # Project documentation
└── .gitignore                       # Git ignore file
```
## **How to Run Project Locally**
### 1. Clone the Repository
```bash
git clone https://github.com/Ganapaved/Dyslexia-Buddy.git
cd Dyslexi-AI
```
### 2. Install Dependencies
#### Backend
Navigate to the backend ```directory``` and install the required dependencies.
```bash
cd backend
npm install
```
#### Frontend
Navigate to the ```frontend``` directory and install the required dependencies.
```bash
cd frontend
npm install
```




