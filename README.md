# Demo
----

##  Table of Contents

- [ Features](#features)  
- [ Prerequisites](#prerequisites)  
- [ Getting Started](#getting-started)  
- [ Usage](#usage)  
- [ Deployment](#deployment)  
- [ Troubleshooting](#troubleshooting)  
- [ Contributing](#contributing)  

---

##  About This Demo part

This folder contains a minimal, working demonstration of the ChatGPT-powered app—designed to let you experience AI interaction firsthand. Ideal for prototyping and sharing!

---

##  Features

- 💬 Real-time chat powered by ChatGPT  
-  Supports multi-step conversations   
- 🖥️ Fully customizable UI (styling, messages, layout)  

---

##  Prerequisites

Make sure you have:

-  Node.js v18 or higher (recommended)  
-  A valid `OPENAI_API_KEY` (set in `.env`)  

---

##  Getting Started

1. Clone the repo and navigate to the project root:
    ```bash
    git clone <your-repo-url>
    cd <repo-root>/demo
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Copy the environment template and add your API key:
    ```bash
    cp .env.example .env
    # then edit:
    # OPENAI_API_KEY=sk-...
    ```

4. Launch the demo:
    ```bash
    npm run dev
    ```
   Then visit `http://localhost:3000` to chat away!

---

##  Usage

- Start chatting immediately in the browser.
- Customize prompts, settings, or UI in `src/` to suit your needs—ideal for experimentation!
- Use browser dev tools for debugging and tweaking interactions.

---

## Deployment

Want to share the demo?

- **Vercel**:  
  1. Fork the repo.  
  2. Set up project with your GitHub account.  
  3. Add `OPENAI_API_KEY` as an environment variable.  
  4. Deploy with a click—automatic rebuilds on updates.

- **Netlify**:  
  1. Fork and connect to Netlify.  
  2. Set to environment variables.  
  3. Configure build & publish settings.  
  4. Hit **Deploy**!

---

##  Troubleshooting

| Problem | Solution |
|--------|----------|
| API errors or rate limits | Check your OpenAI account and key validity |
| CORS or network issues | Ensure Node.js version is v18+ and use proper proxy . |
| UI glitches | Inspect console logs and adjust CSS or JS files in `src/` |

---

##  Contributing

Your insights rock! Feel free to:

- 🐛 Report bugs  
-  Improve prompt flows  
-  Enhance UI/UX  
-  Add new features  

---

##  License

Licensed under the **MIT License**, same as the main repository base.

---

