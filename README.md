# Job-Nest-Job-Portal-Project
JobNest is a modern and easy-to-use job portal that connects job seekers with employers. The platform has an easy-to-use interface that lets candidates sign up, make profiles, look at job listings, and apply for jobs that fit their skills and interests. Employers, on the other hand, can use a streamlined dashboard to post job openings, manage applications, and look for possible candidates. JobNest's main goal is to make the hiring process faster, easier, and less stressful for everyone involved. JobNest wants to make hiring easier by giving you better access to job opportunities and making them easier to find. It does this by letting you filter jobs, match profiles, and track applications. JobNest helps you move forward in your career, whether you're just starting out or have been working for a while.


**HOW TO RUN THE PROJECT:**

**1. Prerequisites**

Ensure the following are installed on your system:

Node.js (v18.x or later)

npm

MongoDB (local or Atlas)

Cloudinary


**2. Backend Setup (Express.js + MongoDB)**

**1.
Install dependencies:**

npm install

**2.
Configure environment variables:**

Create a .env file in the server/ directory with the following:
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

**3.
Start the backend server:**

npm run dev

The server will run on http://localhost:5000

**3. Frontend Setup (React + Vite)**

**1.
Navigate to the client directory:**
cd ../frontend

**2.
Install dependencies:**
npm install

**3.
Start the frontend server:**
npm run dev
The React app will run on http://localhost:5173

**4. Connecting Frontend to Backend**
Make sure the frontend is set to connect to the backend API by updating the base URL in the .env file (or API service file):
VITE_API_URL=http://localhost:5000/api

**5. MongoDB Atlas Setup**
If you are not using a local MongoDB instance:
•
Create an account on MongoDB Atlas
•
Create a new cluster and database
•
Whitelist your IP and get the connection string
•
Replace MONGO_URI in .env with the new connection string.
