
## **Overview**

eduWave is a groundbreaking educational platform that seamlessly integrates technology with mindfulness to transform the learning experience. Our goal is to empower educators with tools for designing engaging courses while offering students personalized study environments that enhance focus and retention. With features like distraction-free learning modes and gamification, eduWave fosters an environment that nurtures both academic and personal growth. Be part of the future of education with eduWave.

```
Experience eduWave at: https://edu-wave.vercel.app
```

## **Key Features**

### **For Educators:**

1. **Student Administration:**
   - Generate and manage student accounts.
   - Oversee student profiles and activity.

2. **Task Coordination:**
   - Maintain to-do lists for academic tasks and deadlines.
   - Configure alerts and notifications for upcoming events.

3. **Resource Distribution:**
   - Provide students with access to essential learning materials.
   - Upload documents, multimedia files, and external links effortlessly.

4. **Interactive Teaching:**
   - Conduct live classes with video conferencing tools.
   - Facilitate real-time discussions, Q&A sessions, and engaging lectures.

5. **Student Assessment & Analytics:**
   - Develop quizzes, tests, and various assessments.
   - Monitor and analyze student performance with detailed reports.

6. **Student Engagement & Motivation:**
   - Implement leaderboards to encourage friendly competition.
   - Acknowledge student accomplishments with public recognition.

### **For Students:**

1. **Task Planning & Organization:**
   - Track assignments and deadlines efficiently.
   - Create and manage personal study schedules.

2. **Custom Learning Journeys:**
   - Discover tailored learning paths based on academic interests.
   - Access curated study resources.

3. **Collaborative Whiteboard:**
   - Engage with an interactive digital canvas for brainstorming and project work.
   - Collaborate with peers and teachers effectively.

4. **Practice & Evaluation:**
   - Take quizzes and self-assessments for progress tracking.
   - Get instant feedback and insights on performance.

5. **Subject Performance Insights:**
   - Analyze detailed reports on academic strengths and areas of improvement.

6. **AI-powered Study Assistant:**
   - Leverage ChatAI for instant references and explanations.
   - Obtain quick answers, definitions, and helpful study tips.

7. **Progress & Motivation:**
   - Compete on leaderboards to track academic performance.

## **Getting Started**

**Clone the repository:**
```
git clone https://github.com/suraj719/eduWave.git
```

**Create a `.env` file in the root directory and include the following configuration:**
```
REACT_APP_BACKEND_URL = "http://localhost:5001"
REACT_APP_CHAT_API_KEY = "open ai api key"
REACT_APP_API_KEY = "firebase config"
REACT_APP_AUTH_DOMAIN = "firebase config"
REACT_APP_PROJECT_ID = "firebase config"
REACT_APP_STORAGE_BUCKET = "firebase config"
REACT_APP_MESSAGING_SENDER_ID = "firebase config"
REACT_APP_APP_ID = "firebase config"
```

**Additionally, create another `.env` file inside the `server` directory with the following details:**
```
MONGO_URL = ""
jwt_secret = ""
clientId = "GCP client ID"
clientSecret = "GCP client secret"
refreshToken = "OAuth refresh token"
```

### **Install Dependencies & Run the Application**

**Install the required dependencies for both the frontend and backend:**
```
npm install
npm start
```
```
cd server
npm install
npm start
```
```
Now, access the application at: http://localhost:3000
```
```
Backend APIs are available at: http://localhost:5001
```

