# Real-Time Collaboration Whiteboard

## Description
This project is an interactive web-based whiteboard that enables multiple users to draw, sketch, and brainstorm ideas together in real-time. Designed for remote teams, educators, and students, it supports mobile devices and ensures smooth synchronization.

## Tech Stack
- Frontend: HTML, CSS, JavaScript (with Canvas API)
- Backend: Node.js with Express
- Real-time Communication: Socket.IO (WebSocket)
- Storage: Optional session persistence (using server-side storage or database)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/bitasmbl-real-time-collaboration-whiteboard.git
```
2. Install backend dependencies:
```bash
cd backend
npm install
```
3. Start the backend server:
```bash
node index.js
```
4. Open the `index.html` in the `frontend` directory in your web browser, or serve it via a local server.

## Usage
- Open the web app on multiple devices or browsers.
- Use mouse or touch to draw on the canvas.
- Watch real-time updates as others draw.
- Save or rejoin sessions to continue collaboration.

## Implementation Steps (Overview)
- Create a responsive, touch-enabled drawing canvas.
- Set up WebSocket communication for live sync.
- Handle multiple users drawing simultaneously.
- Implement session persistence (optional).

## Note
This project is advanced; familiarity with WebSocket, Canvas API, and web development is recommended.

When you are done, submit the project from your profile: [https://bitasmbl.com/home/profile](https://bitasmbl.com/home/profile)