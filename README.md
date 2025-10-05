[README.md](https://github.com/user-attachments/files/22710986/README.md)
# UniCrossed

**A Complete Social Networking Platform for University Students**  
UniCrossed connects university students through networking, enabling knowledge sharing, real-time communication, and academic collaboration.

---

## Table of Contents  
- [About](#about)  
- [Features](#features)  
- [Technologies](#technologies)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation)  
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)  
- [Development Team](#development-team)
- [Testing](#testing)
- [License](#license)  
- [Contact](#contact)  

---

## About  
UniCrossed is a comprehensive social networking platform designed specifically for university students. The platform facilitates meaningful connections between students across different universities, enabling them to share knowledge, collaborate on projects, participate in group discussions, and build lasting academic and professional relationships.

The application combines modern web technologies with real-time communication features, providing an intuitive and engaging user experience that makes academic networking as simple as swiping through profiles.

---

## Features  

### 🎓 **Core Social Features**
- **Profile-based networking** with swipe functionality (Tinder-like interface)
- **Smart user recommendations** based on academic interests
- **Real-time matching system** for study partnerships
- **Interactive user cards** with comprehensive profile information

### 💬 **Real-time Communication**
- **Direct messaging** with Socket.IO integration
- **Group chat functionality** for study groups
- **AI-powered chatbot** (Sophia) with human-like responses
- **Message history** and conversation management
- **Online/offline status indicators**
- **Typing indicators** and message delivery confirmations

### 🔧 **User Management**
- **Comprehensive user profiles** with customizable settings
- **Profile photo upload** and management
- **Academic interests** and course information
- **Privacy settings** and account configuration
- **User authentication** and session management

### 📊 **Analytics & Insights**
- **Performance dashboard** with user activity metrics
- **Interaction statistics** (likes, comments, matches)
- **Activity summaries** and engagement tracking
- **Data visualization** for user analytics

### 🎨 **User Interface**
- **Responsive design** for all device sizes
- **Professional loading animations** with progress indicators
- **Floating action menus** with intuitive navigation
- **Dark/light theme support**
- **Custom animations** and smooth transitions

---

## Technologies  

### **Frontend**
- **HTML5** - Semantic markup and structure
- **CSS3** - Advanced styling with animations and responsive design
- **JavaScript (ES6+)** - Interactive functionality and DOM manipulation
- **Font Awesome 6.5.0** - Professional icon library

### **Backend**
- **Node.js (>=14.0.0)** - Server runtime environment
- **Express.js 5.1.0** - Web application framework
- **Socket.IO 4.8.1** - Real-time bidirectional event-based communication

### **Additional Libraries**
- **CORS 2.8.5** - Cross-origin resource sharing
- **Vite 7.0.0** - Build tool and development server (for chat module)

### **Development Tools**
- **PowerShell scripts** - Automated server startup
- **Static file serving** - Multi-directory asset management
- **Video background support** - Enhanced visual experience

---

## Prerequisites  
- **Node.js** version 14.0.0 or higher
- **npm** (comes with Node.js installation)
- **Modern web browser** with JavaScript enabled
- **Internet connection** for external CDN resources

---

## Installation  

### **1. Clone the repository**
```bash
git clone https://github.com/yourusername/unicrossed.git
cd unicrossed
```

### **2. Install main dependencies**
```bash
npm install
```

### **3. Install chat module dependencies**
```bash
cd Direct
npm install
cd ..
```

### **4. Start the server**
```bash
# Option 1: Use the main server (recommended)
npm start

# Option 2: Use PowerShell script (Windows)
./start-server.ps1

# Option 3: Manual start
node server.js
```

The application will be available at:
- **Main site**: http://localhost:3000
- **Direct chat**: http://localhost:3000/chat
- **User profiles**: http://localhost:3000/confi/user-profile.html

---

## Usage  

### **Getting Started**
1. Open your web browser and navigate to `http://localhost:3000`
2. The application will redirect you to the main social interface
3. Browse through user profiles using the swipe interface
4. Click on chat users in the sidebar to start conversations
5. Access your profile settings through the profile icon

### **Main Features Navigation**
- **💬 Chat**: Click on any user in the Direct sidebar or use floating chat buttons
- **⚙️ Settings**: Access through the gear icon in the floating menu
- **📊 Analytics**: View your activity dashboard
- **🔗 Connections**: Manage your network connections
- **📝 Profile**: Customize your profile information

### **Chat System**
1. **Direct Messages**: Click on any user to start a private conversation
2. **AI Assistant**: Chat with Sophia (the built-in AI bot) for assistance
3. **Group Chats**: Join study groups and participate in group discussions
4. **File Sharing**: Send images and documents through the chat interface

---

## Project Structure
```
unicrossed/
├── 📁 admin/              # Administrative dashboard
├── 📁 analytics/          # User analytics and metrics
├── 📁 bruto/              # Raw/development files
├── 📁 cadastro/           # User registration system
├── 📁 confi/              # User configuration and profiles
├── 📁 Direct/             # Real-time chat application
│   ├── 📁 public/         # Chat frontend files
│   ├── 📁 src/            # Chat source code
│   ├── server.js          # Chat server
│   └── package.json       # Chat dependencies
├── 📁 img/                # Static images and assets
├── 📁 infos/              # Information pages (about, terms, etc.)
├── 📁 landingpage/        # Landing page components
├── 📁 linkeds/            # Social connections interface
├── 📁 mainsite/           # Main application interface
├── 📁 node_modules/       # Dependencies
├── 📁 rejis-food/         # Food-related features
├── server.js              # Main application server
├── package.json           # Main dependencies
├── global-vars.css        # Global CSS variables
└── README.md              # Project documentation
```

---

## API Endpoints

### **Main Server (Port 3000)**
```
GET  /                    # Redirects to main site
GET  /mainsite/*          # Main social interface
GET  /confi/*             # User configuration pages
GET  /linkeds/*           # Social connections
GET  /img/*               # Static image assets
GET  /cadastro/*          # Registration pages
GET  /chat/*              # Direct chat interface
GET  /status              # Server status and metrics
```

### **Socket.IO Events**
```javascript
// Authentication
socket.emit('login', userId)

// Private messaging
socket.emit('sendPrivateMessage', { sender, receiver, content })
socket.on('newPrivateMessage', messageData)

// Group messaging
socket.emit('novaMensagem', { sala, msg, tipo, sender })
socket.on('mensagemRecebida', messageData)

// User status
socket.on('userStatusChanged', { userId, online })

// Conversation history
socket.emit('getConversationHistory', { userId, contactId })
```

---

## Contributing  
We welcome contributions from the community! Here's how you can help:

### **Getting Started**
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

### **Development Guidelines**
- Follow existing code style and conventions
- Add comments for complex functionality
- Test your changes thoroughly
- Update documentation if needed
- Ensure responsive design compatibility

---

## Development Team

### **Meet Our Team**
- **🎨 Kauã Filipe** - Frontend Developer  
  *Passionate about technology, design, and creating beautiful interfaces*

- **📋 Yan Maul** - Product Manager  
  *Organized, communicative, and detail-oriented team coordinator*

- **🎨 Matheus Rudiger** - UX Designer  
  *Creative problem-solver focused on user experience optimization*

- **⚙️ Leonardo Ferreira** - Backend Developer  
  *Focused on clean code, security, and performance optimization*

- **🔍 Erik Santana** - QA Tester  
  *Detail-oriented quality assurance and testing specialist*

---

## Testing

### **Manual Testing**
Follow the instructions in `TESTING_INSTRUCTIONS.md` for comprehensive testing procedures.

### **Quick Test Steps**
1. Start the server: `npm start`
2. Navigate to http://localhost:3000
3. Test profile swiping functionality
4. Test chat redirection from main page
5. Verify real-time messaging works
6. Check AI bot responses
7. Test responsive design on different screen sizes

### **Automated Testing**
```bash
# Run tests (when available)
npm test

# Run specific test suites
npm run test:chat
npm run test:frontend
```

---

## License  
This project is currently **private** and not released under an open-source license. All rights are reserved to the development team.

For licensing inquiries or permission requests, please contact the development team.

---

## Contact  

### **Project Information**
- **Project Name**: UniCrossed
- **Version**: 1.0.0
- **Description**: Complete social networking app for students

### **Development Team**
For questions, suggestions, or collaboration opportunities:
- **Email**: [team@unicrossed.com](mailto:team@unicrossed.com)
- **GitHub**: [UniCrossed Organization](https://github.com/unicrossed)
- **Website**: [www.unicrossed.com](https://www.unicrossed.com)

### **Support**
- **Technical Issues**: Open a GitHub issue
- **Feature Requests**: Contact the development team
- **General Questions**: Check our FAQ or reach out directly

---

<div align="center">

**Made with ❤️ by the UniCrossed Team**

*Connecting knowledge through networking*

</div>
