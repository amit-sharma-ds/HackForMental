# Astra 🌟  
A Chrome extension to help you use social media mindfully and build better digital habits.

![Extension]([https://github.com/amit-sharma-ds/HackForMental/blob/main/astra_Img/onextension.png](https://github.com/amit-sharma-ds/HackForMental/blob/main/astra_Img/Details_Button.png))

---

## 🚀 Features  

- ⏱ **Custom Time Limit** — Set your own time in hours, minutes, and seconds.  
- 🌫 **Blur + Overlay** — When time is up, the page blurs to reduce distraction.  
- 💬 **AI Mindful Message** — Receive a short motivational message powered by Gemini AI.  
- 🎯 **Continue or Close Tab** — Choose to continue browsing or close tab for 1 Mindful Point.  
- 🏆 **Mindful Points** — Earn points for mindful choices; stored daily.  
- 📊 **Dashboard** — Simple dashboard shows your daily Mindful Points.  
- 🔊 **Sound Option (planned)** — Gentle alert sound when time is up (can be toggled).

---

## 🌟 Real-World Benefits  

✅ Helps break mindless scrolling habits.  
✅ Encourages reflection before spending more time on social media.  
✅ Builds awareness of your digital consumption.  
✅ Rewards mindful behavior with points for motivation.  
✅ Simple, clean, no ads, no tracking — just focus on you.

---

## 📂 Project Structure  

```
Astra/
├── Astra/ # Chrome extension code
│ ├── manifest.json
│ ├── background.js
│ ├── content.js
│ ├── popup.html
│ ├── popup.js
│ ├── dashboard.html
│ ├── dashboard.js
│ └── icon.png
├── backend/ # Node.js backend
│ ├── server.js
│ ├── .env
│ └── package.json
```


---

## 🛠 Tech Stack  

### 🚀 Backend  
- **Node.js + Express** — Backend server to handle AI API requests  
- **Axios** — Make HTTP requests to Google Gemini API  
- **CORS** — Handle cross-origin requests from extension to backend  
- **dotenv** — Load and manage environment variables securely  

---

### 💻 Frontend (Extension Logic)  
- **JavaScript (ES6)** — Main programming language for logic  
- **Chrome Extension APIs** — 
  - `chrome.tabs` — Track active and updated tabs  
  - `chrome.storage` — Store user settings and points  
  - `chrome.scripting` — Inject content scripts dynamically  
  - `chrome.runtime` — Messaging between parts of the extension  

---

### 🎨 UI & Styling  
- **HTML + CSS** — Popup, dashboard, overlay and button styles  
- **Inline CSS (JS)** — Dynamic styling in content scripts  
- **DOM Manipulation** — Vanilla JS for building dynamic UI (overlay, blur, popups)  

---

### 🌐 External Services / APIs  
- **Google Gemini API** — Generate short motivational messages  

---

### ⚡ Other Tools / Concepts  
- **LocalStorage / Chrome Local Storage** — For saving user points and time limits  
- **SetTimeout / SetInterval** — For timing and checking tab usage  
- **Z-Index / Positioning Techniques** — For overlay + blur layers  


## ⚙️ Quick Setup  

1️⃣ Unzip the project folder.  

2️⃣ Open it in VS Code.  

3️⃣ In terminal:  
```bash
cd backend
npm install
node server.js
```

4️⃣ In Chrome:

Go to Extensions → Enable Developer Mode → Load Unpacked → Select the extension folder

5️⃣ Pin the extension icon if you like.

6️⃣ Use the icon to set time limits or view the dashboard.

