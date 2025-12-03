# Collaborative Project Builder

A full-stack real-time collaborative project management and coding platform with authentication, messaging, AI assistance, file tree management, and live code execution using WebContainers.

---

## Features

### **User Authentication**

- Secure user registration & login
- Authentication middleware
- Logout functionality
- Protected routes on frontend & backend
- Redis-based session/token handling

### **User & Project Management**

- Create new projects
- Add collaborators to a project
- Display all users & collaborators
- Fetch projects by ID
- Real-time updates when collaborators join

### **Real-Time Messaging**

- Socket.io integration (frontend & backend)
- Project-based socket rooms
- Authenticated socket connection
- Improved message broadcasting
- Clean UI with proper message alignment
- State-based message management

### **AI Assistant Integration**

- Gemini API integration
- Prompt engineering improvements
- Example prompts for intelligent content generation
- AI-powered suggestions for tasks and code

### **File System & Code Editor**

- Full file-tree structure
- Create, update, and manage project files
- Syntax highlighting
- Clean and organized editor layout

### **WebContainer Integration**

- Run project code directly inside the browser
- Support for iframe preview
- Process management for execution flow
- Real-time output display
- Updated file-tree handling

### **Frontend UI**

- React + React Router setup
- Complete login/register UI
- Project pages (file tree, editor, messages, AI assistant)
- Responsive layout
- Clean design for messaging, user panel, and editor

---

## Tech Stack

### **Backend**

- Node.js
- Express.js
- MongoDB
- Redis
- Socket.io
- JWT Authentication

### **Frontend**

- React.js
- React Router
- Context API for state management
- WebContainers API
- CodeMirror / Monaco Editor (depending on your project)

### **AI**

- Google Gemini API integration

---

## Project Structure (Simplified)

```
root/
 ├── server/
 │    ├── config/
 │    ├── controllers/
 │    ├── routes/
 │    ├── middleware/
 │    ├── models/
 │    └── index.js
 ├── client/
 │    ├── src/
 │    │    ├── components/
 │    │    ├── context/
 │    │    ├── pages/
 │    │    ├── utils/
 │    │    └── App.jsx
 └── README.md

```