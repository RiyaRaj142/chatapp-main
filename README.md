Prerequisites
Ensure you have the following installed on your system:
Node.js (v16 or higher recommended)
npm or yarn
MongoDB
Getting Started
1. Clone the Repository
git clone https://github.com/your-username/chat-app.git
cd chat-app
2. Set Up the Server
1. Navigate to the server directory.
cd server
2. Install dependencies:
npm install
3. Create an .env file in the server directory and configure the following variables:
PORT-5000
MONGO_URI=mongodb://localhost:27017/chat-app
JWT_SECRET your_jwt_secret_key
4. Start the server:
npm start
The server should now be running at http://localhost:5000.
3. Set Up the Client
1. Navigate to the client directory:
2. cd client
3. Install dependencies:
   npm install
4. Create a env file in the client directory and configure the following variables
VITE_API_URL=http://localhost:5000
5. Start the client
    npm run dev
The client should now be running at http://localhost:5173 (default Vite port).
![WhatsApp Image 2025-01-12 at 20 53 15_7837cf00](https://github.com/user-attachments/assets/5e9f6854-7395-422a-b3e5-b027cc38cca2)

