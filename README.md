<!-- Banner Image -->
<p align="center">
  <img src="Picture1.png" alt="TeXpedition" width="800"/>
</p>

# GanMA-Ai: AI Sidebar Taskbar Extension

**Epsilon Campus Hackathon '25 Submission**

---

## 📹 [Watch the Full Demo & Setup Video 
## 📹 Watch the Full Demo & Setup Video (https://drive.google.com/file/d/1f7QCfv78kirarrqcdw6QlEjBUvu3Lt_O/view?usp=drive_link)
- [Alternate  for (6 min) Link (Google Drive)](https://drive.google.com/file/d/1Gpd4uobP885iZolYPyujoKr7lo2Hk7-Y/view?usp=drive_link)

---  


---

## 🚀 Overview

GanMA-Ai is a Chrome extension that injects a powerful AI-driven sidebar into every webpage, enabling features like Market Analysis, Feedback Analysis, Text-to-Image generation, and Ethical AI insights—all accessible with a single click.
Please Note: The Enter key has been disabled to prevent accidental submissions. After typing your prompt in the chat input, use your mouse to click the “Send” button to submit and process your request
---

## 🛠️ Features
- **Market Analysis**: Get real-time market insights powered by AI.
- **Feedback Analysis**: Instantly analyze user feedback and sentiment.
- **Text-to-Image**: Generate images from text prompts using AI.
- **Ethical AI**: Access ethical guidelines and AI best practices.
- **User Authentication**: Secure login/signup modal for personalized experience.

---

## 📂 Project Structure
```
GanMA-Ai-main/
│
├── assets/
│   └── ganma-ai-extension/
│       └── aiagent forntend/
│           ├── auth.js
│           ├── content.js
│           ├── icon.png
│           ├── manifest.json
│           ├── package-lock.json
│           ├── sidebar.css
│           ├── sidebar.html
│           └── sidebar.js
└── index.html
```

---

## 🧑‍💻 Step-by-Step Setup & Execution

### 1. **Clone or Download the Repository**
```bash
git clone <repo-url>
cd GanMA-Ai-main/assets/ganma-ai-extension/aiagent forntend
```

### 2. **Install Dependencies**
> No external dependencies required. All scripts and styles are included locally.

### 3. **Load the Extension in Chrome**
1. Open Chrome and go to `chrome://extensions/`.
2. Enable **Developer mode** (top right).
3. Click **Load unpacked**.
4. Select the folder: `GanMA-Ai-main/assets/ganma-ai-extension/aiagent forntend`
5. The "AI Sidebar Taskbar" extension should now appear in your extensions list.

### 4. **Using the Extension**
- Navigate to any webpage.
- The AI Sidebar will automatically appear.
- Use the sidebar icons to access Market Analysis, Feedback Analysis, Text-to-Image, and Ethical AI features.
- Click the user icon to login or sign up.

### 5. **Backend/API**
- The extension communicates with the backend at `https://ganma-backend.onrender.com/` for AI features.
- No local backend setup is required for basic usage.

---

## 📸 Screenshots
<p align="center">
  <img src="extension logo.png" alt="Extension Icon" width="120"/>
</p>

---

## 📄 License
This project is for educational and hackathon purposes.

---

## 🙏 Acknowledgements
- Epsilon Campus Hackathon '25
- All contributors and mentors

---

<p align="center">
  <img src="GanMa-logo.png" alt="TeXpedition" width="800"/>
</p>
