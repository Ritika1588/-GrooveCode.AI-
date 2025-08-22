# 👨‍💻 **GrooveCode.AI 🤖**

GrooveCode.AI is a next-gen real-time collaborative code editor built on the MERN stack.
It empowers 3–5 developers to write, edit, and debug code together live in the browser with:

💡 AI-powered code reviews & bug fixes (via Google Generative AI API)

📝 Monaco Editor (VS Code experience in browser)

⚡ Instant collaboration with Socket.io

Whether you’re working on projects, hackathons, or learning to code with friends — GrooveCode.AI makes coding smarter, faster, and more collaborative. 🚀

## 🌟 **Features**

🖊️ Real-Time Editing – Multiple users coding together seamlessly.

📝 Monaco Editor – Full VS Code–like coding experience in the browser.

🤖 AI Suggestions – Automatic bug detection, improvements & explanations.

👥 Multi-User Collaboration – Designed for 3–5 users per session.

🎨 Modern UI/UX – Clean, responsive design powered by Tailwind CSS.

📦 MERN Stack – Scalable & production-ready.

## 🛠️ **Tech Stack**

### **Frontend**

React.js ⚛️

Tailwind CSS 🎨

Monaco Editor ✨

### **Backend**

Node.js 🌐

Express.js ⚡

MongoDB Atlas 🍃

Socket.io 🔗

### **AI Integration**

Google Generative AI API 🤖

## 🚀 **Getting Started**
### ✅ **Prerequisites**

Node.js (v16+)

MongoDB Atlas or local MongoDB instance

Google Generative AI API Key

## 📥 **Installation**
# Clone repo
git clone https://github.com/your-username/GrooveCodeAI.git
cd GrooveCodeAI

## **Backend Setup**
cd backend
npm install
npm start


Create a .env file in /backend

PORT=5000
MONGO_URI=your_mongo_uri
AI_API_KEY=your_google_ai_key

## **Frontend Setup**
cd frontend
npm install
npm run dev


Create a .env file in /frontend

VITE_API_URL=http://localhost:5000

## 📡 **API Example**



POST /api/review


**Request:**

{
  "code": "function add(a, b) { return a + b }"
}


**Response:**

{
  "review": "Consider adding input validation to avoid unexpected errors."
}

## 📈 **Use Cases**

👩‍💻 Pair Programming – Code together remotely.

🏫 Learning Platform – Teachers & students collaborating live.

🏆 Hackathons – Teams coding in sync with AI bug detection.

💼 Enterprise Teams – AI-assisted code reviews for productivity.

## 🌱 **Roadmap**

📊 Session analytics & reports

🌍 Multi-language AI support

🔐 Role-based access control

☁️ Cloud deployment (Vercel + Render/Heroku)

🧑‍🏫 AI mentor mode (explain code line-by-line)

## 👥 **Contributions**

We welcome contributions! 🚀

Fork the repo

Create a branch: git checkout -b feature/AmazingFeature

Commit changes: git commit -m 'Add some AmazingFeature'

Push to branch: git push origin feature/AmazingFeature

Open a pull request 🎉

## 🙌 **Acknowledgements**

📝 Monaco Editor – For VS Code–like experience in browser.

🔗 Socket.io – For enabling real-time collaboration.

🍃 MongoDB Atlas – Reliable cloud database.

🤖 Google Generative AI – Powering AI code reviews.

🔥 GrooveCode.AI – Code smarter, collaborate better, debug faster. 🚀   MAKE THE HAEADING BOLD HERE
