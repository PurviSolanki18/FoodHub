Project Setup Instructions
Prerequisites

Node.js (v14 or higher)
MongoDB (v4.4 or higher)
Git
npm (Node Package Manager)

Step 1: Initial Setup
 Clone the repository
git clone https://github.com/Purvisolanki/FoodHub.git

# Navigate to project directory
cd FoodHub

# Install dependencies
npm install


Step 2 : Environment Configuration
Create a .env file in the root directory with the following variables:
PORT=3000
MONGODB_URI=mongodb://localhost:27017/foodhub
JWT_SECRET=your_jwt_secret_key

Step 3: Database Setup

Start MongoDB service on your machine
The application will automatically create required collections:

users
foods
orders



Step 4: Running the Application
bashCopy# Start the server in development mode
npm run dev

# Or start in production mode
npm start
