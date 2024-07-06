Chatlogy
Chatlogy is a real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js). This app allows users to communicate with each other through instant messaging in a sleek and user-friendly interface.

Features
Real-time Messaging: Instant communication between users.
User Authentication: Secure login and registration using JWT.
User Profiles: Customizable user profiles with profile pictures.
Group Chats: Create and join group chats.
Search Functionality: Search for users and chat groups.
Notification System: Real-time notifications for new messages and friend requests.
Responsive Design: Fully responsive UI for both desktop and mobile devices.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/chatlogy.git
cd chatlogy
Install server dependencies:

bash
Copy code
cd server
npm install
Install client dependencies:

bash
Copy code
cd ../client
npm install
Create a .env file in the server directory and add the following environment variables:

env
Copy code
PORT=5000
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
Run the server:

bash
Copy code
cd ../server
npm start
Run the client:

bash
Copy code
cd ../client
npm start
Usage
Open your browser and navigate to http://localhost:3000.
Register a new account or log in with existing credentials.
Start chatting with your friends!
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License.

Acknowledgements
MongoDB
Express
React
Node.js
