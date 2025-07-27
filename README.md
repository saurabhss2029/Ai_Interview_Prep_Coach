# 🤖 AI Interview Coach

**AI Interview Coach** is a smart, web-based application designed to help you ace job interviews. It leverages the power of **Google's Gemini API** to provide:

- Real-time feedback  
- Practice sessions  
- Resume analysis  
- A sleek and responsive UI  

---

## 🚀 Features

- 🧠 **Real-time AI Coaching**: Chat with an AI coach that asks interview questions and gives smart feedback.
- 📄 **Resume (PDF) Analysis**: Upload your resume and receive improvement tips, keyword suggestions, and formatting advice.
- 🌗 **Dual Theme UI**: Toggle between light and dark mode based on preference.
- 📊 **Progress Dashboard**: View dummy analytics like questions answered and topics covered.
- 🧾 **Chat History Summary**: Review summarized past conversations in the "History" tab.
- 🔠 **Accessibility Settings**: Increase/decrease font size for better readability.
- ⛔ **Stop Generation**: Instantly stop AI responses mid-generation.
- ✨ **Modern UI**: Clean, fast, and responsive interface using React + Tailwind CSS.

---

## 🛠️ Tech Stack

- **React.js** – Component-based UI  
- **Tailwind CSS** – Utility-first styling  
- **Google Gemini API** – AI chat and analysis  
- **Parcel** – Bundler for fast dev setup  
- **Mozilla pdf.js** – Extracts text from PDFs on the client side  

---

## ⚙️ Setup and Installation

### 🔧 Prerequisites

- Node.js and npm installed  
- A valid **Google Gemini API Key**

### 📁 Project Files

Ensure your project has these files:
index.html
App.js
Dashboard.js
History.js
Settings.js
About.js

### ✅ Installation Steps

1. **Initialize the Project**
   ```bash
npm init
Install Dependencies

bash
Copy
Edit
npm install react react-dom parcel

Configure package.json

json
Copy
Edit
"scripts": {
  "start": "parcel src/index.html",
  "build": "parcel src/build index.html",
  "test": "echo \"Error: no test specified\" && exit 1"
}
Set Up Environment Variable

Create a .env file in the root directory:

ini
Copy
Edit
PARCEL_GEMINI_API_KEY=YOUR_API_KEY_HERE
Add .gitignore

bash
Copy
Edit
.env
node_modules/
dist/
.parcel-cache/
Run the App

bash
Copy
Edit
npm start
Open http://localhost:1234 in your browser.

Built with ❤️ by Saurabh Kumar Kashinwar
