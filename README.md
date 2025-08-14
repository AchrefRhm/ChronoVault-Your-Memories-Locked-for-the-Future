ChronoVault

⏳ Digital Time Capsule for Your Memories 💌

ChronoVault is a futuristic MERN Stack application that lets you lock your memories and revisit them in the future — like sending a letter to your future self 🚀🧠. Preserve your thoughts, messages, and moments securely and experience the joy of unlocking them later.

🚀 Live Demo

Frontend (Vercel): chrono-vault-one.vercel.app

Backend API (Render): chrono-vault-9mfd.onrender.com

🛠️ Tech Stack

Frontend: ⚛️ React + Vite

Backend: 🌐 Node.js + Express

Database: 🍃 MongoDB Atlas

Hosting: ☁️ Render (Backend) + ⚡ Vercel (Frontend)

Auth: 🔑 JWT-based authentication

📦 Features

📝 Create memory capsules with a title, message, and unlock date

🔐 Lock capsules until a future date

🔓 Capsules automatically unlock and reveal messages when the date arrives

🌈 Beautiful, responsive UI for all devices

🧾 Secure user authentication with JWT

🧠 Folder Structure
DIGITAL 
├── client      # React Frontend
│   ├── public
│   ├── src
│   └── package.json
├── server      # Node + Express Backend
│   ├── routes
│   ├── models
│   ├── config
│   ├── .env
│   └── server.js
└── dist        # Optional build folder

📁 Environment Variables

Create a .env file in the /server folder:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000

💡 Future Plans

📩 Email reminders when capsules unlock

🔒 Capsule encryption for privacy and security

🌙 Dark Mode toggle

🧠 AI-generated memory suggestions

📱 PWA support for mobile devices

📬 Connect

Built with ❤️ by Achref Rhouma
⭐ Give it a star if it helped you or inspired you!
