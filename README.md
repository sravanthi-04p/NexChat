cat > README.md << 'EOF'
# 💬 NexChat — Real-time Chat Application

A full-stack real-time chat application built with React, Node.js, Express, Socket.io and SQLite.

## 🚀 Features
- 🔐 User Authentication with JWT & bcrypt
- 💬 Real-time messaging with Socket.io
- 🏠 Multiple Chat Rooms — General, Random, Tech
- 🟢 Online / Offline User Status
- 📜 Message History stored in SQLite database
- ⌨️ Typing Indicators
- 😊 Emoji Picker
- 👍 Likes and Reactions on messages
- 🌙 Dark Mode
- 🚪 Logout

## 🛠️ Tech Stack

### Frontend
- React.js
- CSS
- Socket.io-client
- UUID

### Backend
- Node.js
- Express.js
- Socket.io
- JWT (jsonwebtoken)
- bcryptjs

### Database
- SQLite (better-sqlite3)

## ⚙️ Installation & Setup

1. Clone the repository
git clone https://github.com/sravanthi-04p/NexChat.git
cd NexChat

2. Run Backend
cd server
npm install
node index.js

3. Run Frontend
cd ../chat-app
npm install
npm start

4. Open browser at http://localhost:3000

## 👩‍💻 Author
**Sravanthi Porandla**
GitHub: https://github.com/sravanthi-04p
EOF
git add README.md
git commit -m "add README file"
git push
