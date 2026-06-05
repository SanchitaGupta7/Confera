# 🎥 Confera — Zoom Clone (Real-Time Video Conferencing App)

![React](https://img.shields.io/badge/Frontend-React-blue?logo=react)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green?logo=node.js)
![Express](https://img.shields.io/badge/Framework-Express-black?logo=express)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen?logo=mongodb)
![WebRTC](https://img.shields.io/badge/WebRTC-Real--Time-orange)
![Socket.IO](https://img.shields.io/badge/Realtime-Socket.IO-black?logo=socket.io)
![JWT](https://img.shields.io/badge/Auth-JWT-red)
![Deployment](https://img.shields.io/badge/Deployed-Render-purple)

---

### 🔗 Live Links

- 🌐 **Frontend:** https://conferafrontend-9maa.onrender.com  
- ⚙️ **Backend:** https://conferabackend-0hnt.onrender.com  
- 📂 **GitHub:** https://github.com/SanchitaGupta7/Confera  

---
## ✨ Features

### 🎥 Real-Time Video Calling
- Peer-to-peer video communication using WebRTC
- Multi-user video conferencing support
- Low-latency audio/video streaming

---

### 💬 Real-Time Chat
- Instant messaging inside meeting rooms
- Powered by Socket.IO
- Broadcast messages to all participants

---

### 🖥️ Screen Sharing
- Share entire screen or application window
- Seamless switching between camera and screen stream

---

### 🎛️ Media Controls
- Toggle camera ON/OFF
- Mute/Unmute microphone
- End call anytime

---

### 🏠 Room-Based Meetings
- Join meetings using a Room ID (URL-based system)
- Each room maintains independent session
- Dynamic peer-to-peer connection setup

---

### 🔐 Authentication System
- User registration and login system
- JWT-based authentication
- Protected routes for secure access
- Token stored in localStorage

---

### 📜 Meeting History (NEW ⭐)
- Stores user meeting activity in backend
- Users can view previously joined meetings
- Fetch activity via API:
  - `get_all_activity`
  - `add_to_activity`
- Builds personal meeting history dashboard

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router
- Material UI
- Axios

### Backend
- Node.js
- Express.js
- Socket.IO

### Database
- MongoDB

### Real-Time Communication
- WebRTC (Peer-to-Peer media streaming)
- STUN Server
- Socket.IO (Signaling + Chat)

### Authentication
- JWT (JSON Web Tokens)

### Deployment
- Frontend: Render
- Backend: Render

---

## ⚙️ How It Works

1. User registers / logs in
2. JWT token stored in browser
3. User joins or creates a meeting room
4. Socket.IO connects all users in same room
5. WebRTC establishes peer-to-peer connections
6. SDP offer/answer exchanged via signaling server
7. ICE candidates shared for connectivity
8. Live video/audio streaming begins
9. Chat messages flow in real-time
10. Meeting activity is stored in user history

---

## 📦 Installation & Setup

### 1️⃣ Clone Repository

``` bash
git clone https://github.com/SanchitaGupta7/Confera.git
cd Confera
```

------------------------------------------------------------------------

### 2️⃣ Install Dependencies

#### Backend

``` bash
cd backend
npm install
```

#### Frontend

``` bash
cd frontend
npm install
```

------------------------------------------------------------------------

### 3️⃣ Environment Variables

Create a `.env` file in the backend folder:

``` env
MONGO_URL=your_mongodb_connection_string
```

------------------------------------------------------------------------

### 4️⃣ Run Project

#### Start Backend

``` bash
cd backend
npm run dev
```

#### Start Frontend

``` bash
cd frontend
npm start
```

------------------------------------------------------------------------

## 📡 Key Learnings

-   Built real-time WebRTC communication system
-   Implemented Socket.IO signaling architecture
-   Designed room-based conferencing system
-   Managed media streams dynamically
-   Integrated authentication using JWT
-   Built user meeting history tracking system
-   Handled screen sharing and device control
-   Understood SDP/ICE negotiation flow

------------------------------------------------------------------------

## 🚀 Future Improvements

-   🎥 Meeting recording feature
-   🔔 Real-time notifications
-   🧑‍🤝‍🧑 Participant controls (mute/remove users)
-   🌙 Dark mode UI
-   📱 Mobile optimization
-   🗂️ Persistent chat storage in MongoDB
-   🔐 OAuth (Google/GitHub login)
-   📊 Analytics dashboard for meetings

---
