---
marp: true
lang: en-US
title: GitHub Copilot for VS Code
author: Samin Yaser
description: A brief introduction to GitHub Copilot for VS Code
theme: gaia
transition: fade
paginate: true
_paginate: false
footer: "2025 © Samin Yaser"
---

<!-- @format -->

<!--
TODO:
- Parallel programming
- Set budget to prevent overbilling
 -->

<!--
    _backgroundImage: linear-gradient(120deg, #89f7fe 0%, #66a6ff 100%);
-->

# <!--fit--> 🤖 GitHub Copilot in VS Code

**Dev Workshop, WPXPO**

Samin Yaser, SWE
Abdullah Al Asif, SWE

---

## 🛠️ Setup

-   VS Code Insiders
-   GitHub Copilot Extension

<style>
/* Global (deduped) styles formerly repeated across multiple slides */
strong { color: royalblue; }
h2 { 
  color: #ff6b6b;
  text-shadow: 2px 2px 8px rgba(255,107,107,0.3);
  font-size: 1.5em;
}
h3 { 
  color: #4ecdc4; 
  margin-bottom: 0px;
  font-size: 0.8em;
}
code {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 3px 6px;
  border-radius: 4px;
  font-size: 0.9em;
}
ul { font-size: 0.9em; }
li { margin: 6px 0; }
</style>

---

## ✨ Features: Code Completions

-   inline "ghost text" as you type
-   Tab to next edit

<!-- Removed duplicate scoped style block (h2/strong) now covered by global styles -->

---

## 💬 Features: Chat Modes

-   **Ask mode**: Regular chatting.
-   **Inline chat**: Quick chat in the editor/terminal for in-flow edits
-   **Edit mode**: Almost never used.
-   **Agent mode**: Most powerful; can create files, run tasks, and iterate with you

<!-- Removed duplicate scoped style block (h2/strong) now covered by global styles -->

---

## ⌨️ Essential Shortcuts

![bg right:40% opacity:0.8](https://images.unsplash.com/photo-1461749280684-dccba630e2f6?w=400)

### 💬 Chat & Modes

-   **Inline Chat:** `Ctrl+I` / `⌘I`
-   **Chat View:** `Ctrl+Alt+I` / `⌃⌘I`
-   **Agent Mode:** `Ctrl+Shift+I` / `⌘⇧I`

💡 **Pro Tip:** Bind "Toggle Copilot" to your favorite key!

<style scoped>
h2 { color: #ff6b6b; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); }
h3 { color: #4ecdc4; margin-top: 20px; }
ul { font-size: 0.9em; }
li { margin: 8px 0; }
code { 
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 4px 8px;
  border-radius: 6px;
  font-weight: bold;
}
</style>

---

## 🎭 Context is King

### 📂 File Management

-   **Drag** files/folders/problems into Chat
-   **Type** `#fileName`, `#folder`, `#symbol`

### 🛠️ Power Tools

-   `#codebase` — semantic search
-   `@terminal`, `@workspace`

<style scoped>
h2 { 
  color: #ff6b6b;
  text-shadow: 2px 2px 8px rgba(255,107,107,0.3);
  font-size: 1.5em;
}
h3 { 
  color: #4ecdc4; 
  margin-bottom: 0px;
  font-size: 0.8em;
}
code {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 3px 6px;
  border-radius: 4px;
  font-size: 0.9em;
}
ul { font-size: 0.9em; }
li { margin: 6px 0; }
</style>

---

## ⚙️ Settings to Tweak
- `"chat.agent.maxRequests": 100` - Increase agent iterations
- `"github.copilot.chat.codesearch.enabled": true` - Enables codebase search
- `"github.copilot.chat.agent.thinkingTool": true` - Enables agent reasoning
- `"editor.aiStats.enabled": true` - View usage stats in status bar

---

## 🚀 Prompt Boosting

Use the [Prompt Boost](https://marketplace.visualstudio.com/items?itemName=chrisdias.promptboost) to easily improve your prompts.

-   Invoke the `#promptBoost` tool in your prompt

![width:500px](assets/pompt-boost.png)

---

## 🌟 Awesome Copilot Repo

- Curated list of high‑quality prompts, agents, extensions, SDKs & learning resources
- Bookmark it: [github.com/github/awesome-copilot](https://github.com/github/awesome-copilot)

---


## 📝 Prompt Examples (1/2)

**React hook:**

> "Create useDebouncedValue<T>(value, delay) with cleanup and type-safe API. Add example."

**A11y:**

> "Refactor Modal for WCAG 2.2: focus trap, ARIA roles, ESC to close, Tab cycle. Add tests."

<style scoped>
blockquote { 
  background: #f6f8fa; 
  border-left: 4px solid #28a745; 
  padding: 10px 15px; 
  font-style: italic;
  font-size: 0.9em;
  margin: 10px 0;
}
</style>

---

## 🧪 Prompt Examples (2/2)

**Inline Chat refactor (paste & run):**

> "Refactor selected code to be side-effect-free, improve naming, keep public API stable, and add JSDoc with examples. Don't change behavior."

<style scoped>
blockquote { 
  background: #f6f8fa; 
  border-left: 4px solid #28a745; 
  padding: 10px 15px; 
  font-style: italic;
  font-size: 0.9em;
  margin: 10px 0;
}
</style>

---

### 🙏 Thanks!

Get the slides from [GitHub](https://github.com/SaminYaser-work/copilot-presentation)
