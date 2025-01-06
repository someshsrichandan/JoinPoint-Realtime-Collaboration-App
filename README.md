# JoinPoint - Real-time Collaboration App

JoinPoint is a real-time collaboration web application that allows multiple users to work together on code in the same virtual room. It is built using the MERN (MongoDB, Express.js, React, Node.js) stack and Socket.IO for seamless real-time communication.

## **Features**

- **Virtual Rooms**: Create or join a room using a unique room ID.
- **User Identification**: Set your username to identify yourself during collaboration.
- **Real-time Collaboration**: Changes made by one user are instantly reflected on all connected clients.
- **Code Editor Customization**: Code highlighting, linting, and editor customization options.
- **User Interaction**: In-app chat for discussions, color-coded user contributions, and real-time activity tracking.
- **Version Control**: View version history and rollback changes if needed.
- **Responsive Design**: Optimized for both desktop and mobile users.

---

## **Technologies Used**

- **Frontend**: React.js with CodeMirror for the code editor.
- **Backend**: Node.js with Express.js for API and Socket.IO for real-time communication.
- **Database**: MongoDB for storing room details and user preferences.
- **Utilities**: UUID for generating unique room IDs.

---

## **Installation and Usage**

To run JoinPoint locally, follow these steps:

### **1. Clone the Repository**
```bash
https://github.com/someshsrichandan/JoinPoint-Realtime-Collaboration-App
cd JoinPoint-Realtime-Collaboration-App
```

### **2. Install Dependencies**

#### Backend Setup
```bash
cd server
npm install
npm start
```
The server will run on [http://localhost:5000](http://localhost:5000).

#### Frontend Setup
```bash
cd ../frontend
npm install
npm start
```
The frontend will run on [http://localhost:3000](http://localhost:3000).npm install
npm start
```

---

## **Improvisations**

JoinPoint improves upon its predecessor (CodeCast) with several new features and enhancements:

1. **Enhanced UI/UX**:
   - Rebranded with a modern and responsive design.
   - Improved onboarding and room management interfaces.

2. **Authentication and User Management**:
   - Optional JWT-based authentication for saving user preferences.
   - Display active users in rooms with avatars or initials.

3. **Real-time Collaboration Improvements**:
   - Better synchronization to handle high-latency environments.
   - Color-coded user changes and optional read-only mode.

4. **Version Control**:
   - Track changes and rollback to previous versions.

5. **In-app Chat**:
   - Chat system with markdown support for better collaboration.

6. **Performance and Deployment**:
   - Docker support for easy deployment.
   - Optimized backend for scalability and reduced latency.

---

## **How to Use**

1. **Open JoinPoint**: Visit the live app or run locally.
2. **Create/Join a Room**: Enter a unique Room ID or generate a new one.
3. **Set Username**: Identify yourself to other collaborators.
4. **Collaborate**: Start coding with real-time updates and communication.

---

## **Contributing**

We welcome contributions to JoinPoint! If you'd like to improve the app, please:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with detailed information about your changes.

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Contact**

For questions, suggestions, or feedback, reach out at [someshsrichandan@gmail.com](mailto:someshsrichandan@gmail.com).

---

## **Demo**

- Live Demo: [JoinPoint Live](#)
- Demo Video: **JoinPoint.mp4**

