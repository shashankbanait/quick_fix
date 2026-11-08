# quick_fix
QuickFix is a home-services app that helps people find and book local professionals for jobs like electrical work, plumbing, carpentry, painting, and home cleaning. Customers can browse services, compare prices and reviews, schedule a booking, and keep track of their requests. Service providers can list what they offer, set their prices and service areas, and manage incoming bookings.

Setup:
1. Install Node.js
   Download Node.js from the official website: https://nodejs.org
   Install Node.js on your system.
   Open a terminal or command prompt.
   Verify that Node.js and npm are installed successfully by running:
   - a) node -v
   - b) npm -v
2. Open the Project
1. Open the project folder in VS Code or your preferred code editor.
2. You will find two main folders:
   - a) backend
   - b) frontend
3. Backend Setup
1. Open a terminal in your project directory.
2. Navigate to the backend folder:
   - a) cd backend
3. Install the backend dependencies:
   - a) npm install
4. Create a new file named .env inside the backend folder.
5. Add the following environment variables to the .env file:
   - a) MONGODB_URI=your_mongodb_connection_string
   - b) JWT_SECRET=your_secret_key
   - c) PORT=5000
   - d) NODE_ENV=development
6. Replace the placeholder values:
   - a) Replace your_mongodb_connection_string with your actual MongoDB connection string.
   - b) Replace your_secret_key with a secure JWT secret key.
7. Start the backend development server:
   - a) npm run dev
8. Once the server starts successfully, the backend should be accessible at:
   - a) http://localhost:5000
4. Frontend Setup
1. Open a new terminal while keeping the backend server running.
2. Navigate to the frontend folder from the project root:
   - a) cd frontend
3. Install the frontend dependencies:
   - a) npm install
4. Start the frontend application:
   - a) npm start
5. Once the application starts successfully, open your browser and navigate to:
   - a) http://localhost:3000
5. Important Notes
1. Make sure the backend server is running before accessing the frontend application.
2. Ensure that the MongoDB connection string in the .env file is correct.
3. If the MongoDB connection fails, verify the following:
   - a) Your MongoDB Atlas connection string.
   - b) Your database username and password.
   - c) Your MongoDB Atlas network access/IP whitelist settings.
4. Keep both terminal windows open while running the application.
5. If you encounter dependency-related issues, try reinstalling the dependencies.
6. Quick Setup Reference
Backend
- a) cd backend
- b) npm install
- c) Create and configure the .env file.
- d) npm run dev
Frontend (in a separate terminal)
- a) cd frontend
- b) npm install
- c) npm start
Application URLs
- a) Backend: http://localhost:5000
- b) Frontend: http://localhost:3000
