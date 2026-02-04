🏋️ GymPro – Full Stack MERN Application

GymPro is a full-stack MERN web application designed for a fitness/gym website.
It provides a modern frontend with a backend API to handle user interactions and securely store contact form submissions in a database.

⸻

🚀 Features
	•	Responsive gym website built with React.js
	•	Contact form to collect Name, Email, and Message
	•	RESTful backend API using Node.js & Express.js
	•	Secure data storage in MongoDB
	•	Frontend–backend integration using Axios
	•	Proper handling of CORS and environment configuration
	•	Clean and scalable project structure

⸻

🛠 Tech Stack

Frontend
	•	React.js
	•	Axios
	•	CSS / Tailwind (if applicable)
	•	React Toastify

Backend
	•	Node.js
	•	Express.js
	•	MongoDB
	•	Mongoose
	•	dotenv

Project Structure

gymPro/
│
├── frontend/
│   ├── src/
│   └── package.json
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── app.js
│   └── package.json

Backend Setup
cd backend
npm install
npm run dev

Create a .env file in the backend folder:
PORT=5001
MONGO_URI=your_mongodb_connection_string

Frontend Setup
cd frontend
npm install
npm run dev

VITE_BACKEND_URL=http://localhost:5001
Submit Contact Form
POST /api/contact
Request Body:
{
  "name": "User Name",
  "email": "user@email.com",
  "message": "Message text"
}

🧠 Key Learnings
	•	Full-stack integration between React and Express
	•	Designing REST APIs with MongoDB persistence
	•	Debugging real-world issues like CORS preflight requests
	•	Managing environment variables for different services
	•	Handling port conflicts and deployment-ready configurations

⸻

📌 Future Improvements
	•	Admin dashboard to view submitted messages
	•	Email notification on form submission
	•	Authentication for admin access
	•	Deployment on cloud platforms

  
  ⭐ If you like this project, feel free to star the repository!
