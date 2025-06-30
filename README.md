# CodeSync - Real-time Collaborative Code Editor

![CodeSync Logo](./frontend/public/code-sync.png)

A modern, real-time collaborative code editor that allows multiple developers to write, edit, and execute code together in the same virtual room.

## ✨ Features

- **Real-time Collaboration**: Multiple users can edit code simultaneously
- **Live Code Execution**: Run code directly in the browser with real-time output
- **Multi-language Support**: JavaScript, Python, Java, and C++
- **Room-based Sessions**: Create and join coding rooms with unique IDs
- **User Presence**: See who's currently in your coding session
- **Modern UI**: Clean, dark theme with responsive design
- **Typing Indicators**: See when others are typing
- **Copy Room ID**: Easy sharing of room links

## 🚀 Tech Stack

### Frontend
- **React** - UI framework
- **Vite** - Build tool and dev server
- **Monaco Editor** - Code editor (VS Code editor)
- **Socket.io Client** - Real-time communication
- **CSS3** - Modern styling with gradients and animations

### Backend
- **Node.js** - Runtime environment
- **Socket.io** - WebSocket communication
- **Express** - Web framework

## 🛠️ Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/nikunjagarwal17/code-sync.git
   cd code-sync
   ```

2. **Install dependencies**
   ```bash
   # Install root dependencies
   npm install

   # Install frontend dependencies
   cd frontend
   npm install

   # Install backend dependencies
   cd ../backend
   npm install
   ```

3. **Start the application**
   
   **Backend (Terminal 1):**
   ```bash
   cd backend
   node index.js
   ```
   
   **Frontend (Terminal 2):**
   ```bash
   cd frontend
   npm run dev
   ```

4. **Access the application**
   - Open your browser and go to `http://localhost:5000`
   - Create a new room or join an existing one
   - Start coding collaboratively!

## 🎯 Usage

1. **Create a Room**: Click "Create New Room" to generate a unique room ID
2. **Join a Room**: Enter a room ID and your username to join an existing session
3. **Code Together**: Write code in the Monaco editor with real-time synchronization
4. **Execute Code**: Use the "Execute" button to run your code and see the output
5. **Share**: Copy the room ID to invite others to your coding session

## 🌟 Screenshots

### Login Page
Modern login interface with dark theme and green accents.

### Editor Interface
- **Sidebar**: Room info, user list, language selector
- **Editor**: Monaco editor with syntax highlighting
- **Console**: Input and output areas for code execution

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the backend directory:
```env
PORT=5000
```

### Supported Languages
- JavaScript (Node.js)
- Python
- Java
- C++

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## 👨‍💻 Author

**Nikunj Agarwal**
- GitHub: [@nikunjagarwal17](https://github.com/nikunjagarwal17)

## 🙏 Acknowledgments

- Monaco Editor for the excellent code editing experience
- Socket.io for real-time communication
- React and Vite for the modern development experience

---

Built with 💙 by [Nikunj Agarwal](https://github.com/nikunjagarwal17)
