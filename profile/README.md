# 🚀 Get Started with Notify Learn

Welcome to **Notify Learn** - your intelligent learning companion, available everywhere you work and learn. Pick the platform that suits you best and dive in!

---

## 🌐 Web App

The fastest way to get started, no installation needed.

👉 **[Open Notify Learn](https://notifylearn.akshilmy.com)**

Save links and images (paste, drag & drop, or upload) and organize them with tags. Set a reminder at a time you choose (also as browser notifications) and share any item with a public link.

---

## 📱 Mobile App (Android)

Take your learning on the go with the Notify Learn Android app. Save links and images from any app's share sheet, get reminders at the time you pick, and share items with a link.

**Steps to get early access:**

1. 🔗 Join the early access group → [Notify Learn Early Access](https://groups.google.com/g/notify-learn-early-access)
2. 🏪 Open the **Google Play Store** and sign in with the same email you used to join the group
3. 📲 Install the app → Click [here](https://play.google.com/store/apps/details?id=com.notifylearn.app) to open app page
4. ✅ Install and enjoy!

---

## 🧩 Chrome Extension

Supercharge your browser and save while you browse.

👉 **[Install from Chrome Web Store](https://chromewebstore.google.com/detail/jndhelenakecabkbigajbbncoihdadco?utm_source=item-share-cb)**

---

## 🤖 MCP Server

Integrate Notify Learn directly into your AI-powered workflow. Your assistant can save and read your links and images, manage tags and reminders, share items, and check notifications:

- **Saving:** `add_links`, `add_images` (local files by path), `preview_link`
- **Reading:** `get_history`, `get_images`, `get_item`, `get_stats`, `get_image_stats`
- **Editing:** `update_item` (tags, reminders, read state, image captions), `delete_item`
- **Sharing:** `share_item`, `get_share`, `unshare_item`, `claim_share`, `get_share_stats`
- **Reminders and notifications:** `list_reminders`, `get_notifications`, `mark_notifications_opened`, `get_notification_preferences`, `set_notification_preferences`
- **Tags:** `list_tags`, `list_image_tags`, `create_tag`, `rename_tag`, `delete_tag`
- **Login:** `login_to_notifylearn` (the token stays on your machine and is never shown to the AI)

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
