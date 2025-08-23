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

### 📥 Installation


## 📂 Project Setup  



1. **Clone the repository**

   ```bash
   git clone https://github.com/Ritika1588/-GrooveCode.AI-.git

2. **Go to the project directory**
   ```bash
   cd GrooveCodeAI

3. **Backend Setup**
   ```bash
   cd backend
   npm install
   

4. **Environment Configuration**
   ```bash
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   AI_API_KEY=your_google_generative_ai_api_key
   JWT_SECRET=your_jwt_secret_key
   NODE_ENV=development

5. **Start the backend server**
    ```bash
    npm start
    npm run dev

6. **Preview production build**
    ```bash
    npm run preview

7. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   

8. **Environment Configuration**
    Create a .env file in the /frontend directory:
   ```bash
   VITE_API_URL=http://localhost:5000
   VITE_APP_NAME=GrooveCodeAI

5. **Start the development server**
    ```bash
    npm start
    npm run dev

6. **Preview production build**
    ```bash
    npm run preview

Open your browser and navigate to http://localhost:5000

## 📸 Demo 

<img width="1587" height="673" alt="image" src="https://github.com/user-attachments/assets/822731cc-7b62-4336-9e2d-cd0765fac9ef" />

### Login Page

<img width="622" height="341" alt="image" src="https://github.com/user-attachments/assets/0e24a3d4-86d8-46e2-b402-89a84e396234" />


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

🔥 GrooveCode.AI – Code smarter, collaborate better, debug faster. 🚀  
