# Mini Uber Backend 🚖

A simplified backend API for a ride-hailing application built with **Node.js**, **Express**, **MongoDB**, and **JWT authentication**.

## 🔧 Tech Stack

- Node.js
- Express.js
- MongoDB + Mongoose
- JWT for Authentication
- Dotenv for env management
- Nodemon for development

## 📁 Folder Structure

mini-uber-backend/
├── controllers/
├── models/
├── routes/
├── middleware/
├── utils/
├── .env
├── .gitignore
├── server.js
├── package.json

markdown
Copy
Edit

## 🚀 How to Run

1. Clone the repo  
   `git clone https://github.com/aanya-jain-tech/mini-uber-backend.git`

2. Install dependencies  
   `npm install`

3. Create a `.env` file with:
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret

markdown
Copy
Edit

4. Start the server  
`npm run dev`

## 📬 API Endpoints

### POST `/api/auth/register`  
Registers a new user and returns a token.

## 🙌 Author

**Aanya Jain**  
[GitHub](https://github.com/aanya-jain-tech)