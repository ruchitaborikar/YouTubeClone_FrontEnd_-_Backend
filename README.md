YouTube Clone

🚀 This project is a YouTube Clone built using MongoDB, Express.js, React.js, and Node.js (MERN stack). It allows users to upload, view, and interact with videos, simulating core features of YouTube.

Features

✅ User authentication (signup, login, logout)
✅ Video upload and playback functionality
✅ Like, dislike, and comment system
✅ User profile management
✅ Search functionality for videos

Project Setup

Backend Setup

📥 Clone the repository:

git clone <repository_url>
cd youtube-clone

📦 Install dependencies:

npm install

⚙️ Configure environment variables:
Create a .env file in the root directory and add the following:

MONGO_URI=<your_mongo_db_connection_string>
JWT_SECRET=<your_jwt_secret>
PORT=2222

▶️ Start the backend server:

npm start

Frontend Setup

📂 Navigate to the frontend directory:

cd client

📦 Install dependencies:

npm install

▶️ Start the React application:

npm run dev

Flow of Running the Application

▶️ Start the backend server:

npm start

▶️ Start the frontend application:

cd client
npm run dev

Usage

🌐 Access the application at http://localhost:2222

🔐 Register a new account or log in with existing credentials.

📹 Upload videos, browse content, and interact with other videos using like, dislike, and comment features.

Technologies Used

🖥️ Frontend: React.js, React Router, Axios
🛠️ Backend: Node.js, Express.js, MongoDB
🔒 Authentication: JWT (JSON Web Tokens)
🗄️ Database: MongoDB (MongoDB Atlas or local instance)

Future Improvements

📌 Implement subscription functionality
🎨 Improve UI design and responsiveness
📈 Add video recommendations and trending sections

License

📜 This project is open-source and available under the MIT License.

