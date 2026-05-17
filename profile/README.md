# 🚀 Get Started with Notify Learn

Welcome to **Notify Learn** — your intelligent learning companion, available everywhere you work and learn. Pick the platform that suits you best and dive in!

---

## 🌐 Web App

The fastest way to get started, no installation needed.

👉 **[Open Notify Learn](https://notify-learn.vercel.app/)**

---

## 📱 Mobile App (Android)

Take your learning on the go with the Notify Learn Android app.

**Steps to get early access:**

1. 🔗 Join the early access group → [Notify Learn Early Access](https://groups.google.com/g/notify-learn-early-access)
2. 🏪 Open the **Google Play Store** and sign in with the same email you used to join the group
3. 📲 Install the app → Click [here](https://play.google.com/store/apps/details?id=com.notifylearn.app) to open app page
4. ✅ Install and enjoy!
5. 👀 Watch demo video: Click [here](https://youtube.com/shorts/HDAUZVP3mWI?si=RTU0h7bOzW8C-Gk9)

---

## 🧩 Chrome Extension

Supercharge your browser and save while you browse.

👉 **[Install from Chrome Web Store](https://chromewebstore.google.com/detail/jndhelenakecabkbigajbbncoihdadco?utm_source=item-share-cb)**

---

## 💻 CLI — macOS & Linux

For those who live in the terminal.

```bash
brew tap AKSHILMY/notify-learn-cli https://github.com/AKSHILMY/notify-learn-cli
brew install notify-learn-cli
```

> ⚠️ **macOS security prompt?** If macOS blocks the app because the developer can't be verified, run:
> ```bash
> xattr -d com.apple.quarantine $(which notify-learn-cli)
> ```

---

## 🤖 MCP Server

Integrate Notify Learn directly into your AI-powered workflow.

### 1️⃣ Install Globally via NPM
[![npm version](https://img.shields.io/npm/v/notify-learn-mcp.svg)](https://www.npmjs.com/package/notify-learn-mcp)
```bash
npm i -g notify-learn-mcp
```

### 2️⃣ Connect to any Agentic Coding Tool (Claude Code, Antigravity or any other)

Hook it into Claude Code (the fast command-line assistant) with a single command:

```bash
claude mcp add notifylearn -- npx -y notify-learn-mcp
```

### 3️⃣ Connect to Claude Desktop

Edit your `claude_desktop_config.json` file and add the following block:

```json
"mcpServers": {
  "notifylearn": {
    "command": "npx",
    "args": ["-y", "notify-learn-mcp"]
  }
}
```

---

## 🙌 Need Help?

Have questions or feedback? We'd love to hear from you. Reach out through the [Early Access Group](https://groups.google.com/g/notify-learn-early-access) and join the conversation!
