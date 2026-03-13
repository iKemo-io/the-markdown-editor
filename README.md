# The Markdown Editor

<div align="center">

### A Modern, Real-Time Markdown Editor for the Web

**Fast · Intuitive · Powerful**

[Live Demo](https://markdownlive.dev) • [Features](#-features) • [Usage Guide](#-usage-guide)

</div>

---

## 📝 About

**The Markdown Editor** is a feature-rich, browser-based Markdown editor designed for developers, writers, and content creators. Built with modern web technologies, it offers a seamless writing experience with real-time rendering, bidirectional editing capabilities, and a clean, distraction-free interface.

What sets this editor apart is its **bidirectional data binding** — you can edit content in the Markdown source or directly in the rendered preview, and both views stay perfectly synchronized. Whether you're writing documentation, blog posts, README files, or technical notes, this editor provides everything you need without the complexity.

### Why This Editor?

- **Truly Bidirectional:** Unlike traditional one-way editors, edit the preview directly and watch changes sync back to Markdown
- **Professional Grade:** Powered by Monaco Editor (the same engine as VS Code) with full syntax highlighting and IntelliSense
- **Privacy First:** Everything runs locally in your browser — your content never leaves your device
- **Zero Setup:** No installation, no sign-up, no configuration — just open and start writing
- **Lightning Fast:** Optimized rendering with Marked.js and secure HTML sanitization with DOMPurify

## 🚀 Live Demo

Experience it yourself: **[https://markdownlive.dev](https://markdownlive.dev)**

## ✨ Features

### Core Functionality

**⚡ Real-Time Preview**
Watch your Markdown render instantly as you type with zero lag. The preview pane updates automatically with every keystroke, giving you immediate visual feedback.

**🔄 Bidirectional Editing**
Industry-leading feature that lets you edit directly in the preview pane. Make quick corrections or visual edits, and watch the Markdown source update automatically — perfect for rapid iterations.

**📜 Synchronized Scrolling**
Keep your editor and preview perfectly aligned while scrolling through long documents. The sync scroll feature maintains context and can be toggled on/off as needed.

**🎯 Smart Selection Sync**
Select or highlight text in the preview, and the editor automatically finds and highlights the corresponding Markdown source. Makes navigating large documents effortless.

**🌙 Adaptive Themes**
Beautiful light and dark modes with smooth transitions. Your preference is saved across sessions, and the entire UI adapts seamlessly.

**⌨️ Keyboard Shortcuts**
Built-in productivity shortcuts including `Cmd/Ctrl + K` for links, `Cmd/Ctrl + F` for search, plus all standard Monaco Editor commands for efficient editing.

**📋 One-Click Copy**
Copy your Markdown content to clipboard instantly — perfect for backing up or sharing your work.

**💾 Auto-Save**
Your work is automatically saved to browser local storage. Close the tab, restart your browser, or experience a crash — your content is always preserved.

**📱 Mobile Responsive**
Fully optimized for mobile devices with an intuitive tab-based interface for switching between editor and preview on smaller screens.

**🎨 GitHub-Flavored Markdown**
Complete support for GitHub-Flavored Markdown (GFM) including tables, task lists, strikethrough, fenced code blocks with syntax highlighting, and more.

### Advanced Features

- **Monaco Editor Integration:** Professional code editing with multi-cursor support, find/replace, and IntelliSense
- **Secure by Default:** All HTML output is sanitized with DOMPurify to prevent XSS attacks
- **Resizable Panes:** Drag the center divider to customize your workspace layout
- **State Persistence:** Content, scroll positions, theme preferences, and settings preserved across sessions
- **Zero Server Dependencies:** Fully client-side — works offline and requires no backend infrastructure

## 📖 Usage Guide

### Getting Started

1. **Write Your Content:** Type Markdown in the left editor pane using standard syntax
2. **See It Live:** Watch your formatted content appear instantly in the right preview pane
3. **Edit Anywhere:** Click the preview to edit directly — changes sync back to Markdown automatically
4. **Customize:** Adjust theme, sync settings, and pane sizes to match your workflow

### Interface Overview

| Element | Function |
|---------|----------|
| **Sync Scroll Toggle** | Keep editor and preview scrolling together (toggle in top bar) |
| **Help Button (?)** | View keyboard shortcuts and feature guide |
| **Theme Toggle** | Switch between light and dark modes |
| **Copy Markdown** | Copy your Markdown content to clipboard |
| **Reset** | Clear content and start fresh |
| **Divider** | Drag to resize editor and preview panes |

### Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Cmd/Ctrl + K` | Insert or remove link |
| `Cmd/Ctrl + F` | Find in editor |
| `Cmd/Ctrl + H` | Find and replace |
| `Cmd/Ctrl + /` | Toggle line comment |
| `Alt + ↑/↓` | Move line up/down |
| `Cmd/Ctrl + D` | Select next occurrence |

### Pro Tips

- **Sync Scroll:** Enable when reading long docs to maintain context. Disable to reference different sections simultaneously.
- **Preview Editing:** Perfect for quick typo fixes without hunting through Markdown source
- **Selection Sync:** Select text in preview to instantly locate it in source — great for large documents
- **Mobile Mode:** On mobile, use tab buttons to switch between editor and preview
- **Auto-Save:** Content saves automatically — close anytime and resume where you left off

## 🎯 Use Cases

- **📚 Documentation:** Write README files, API docs, and technical guides with instant preview
- **✍️ Blogging:** Draft and preview blog posts before publishing to your platform
- **📝 Note-Taking:** Maintain formatted notes with code snippets, tables, and links
- **🎓 Learning:** Perfect for learning Markdown syntax with immediate visual feedback
- **💻 Code Snippets:** Store and format code examples with syntax highlighting
- **📄 Content Creation:** Write articles, tutorials, and long-form content efficiently

## 🛠️ Technologies

Built with carefully selected modern web technologies:

- **[Monaco Editor](https://microsoft.github.io/monaco-editor/)** - Microsoft's VS Code editor engine
- **[Marked.js](https://marked.js.org/)** - Fast, extensible Markdown parser
- **[DOMPurify](https://github.com/cure53/DOMPurify)** - Industry-standard HTML sanitizer
- **[Turndown](https://github.com/mixmark-io/turndown)** - HTML to Markdown converter
- **[Vite](https://vitejs.dev/)** - Next-generation frontend build tool
- **[Storehouse.js](https://github.com/javascriptutilities/storehouse-js)** - Local storage wrapper

## 🌐 Browser Support

Works seamlessly on all modern browsers:

- ✅ Chrome/Edge (Chromium) 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+
- 📱 iOS Safari & Chrome Mobile

## 🔧 How It Works

The editor leverages a sophisticated synchronization system:

1. **Monaco Editor** provides the code editing interface with IntelliSense and syntax highlighting
2. **Marked.js** parses Markdown and converts it to HTML in real-time
3. **DOMPurify** sanitizes HTML output to prevent security vulnerabilities
4. **Turndown** converts HTML back to Markdown for bidirectional editing
5. **Storehouse.js** persists content and preferences to local storage

The bidirectional editing feature maintains synchronized state between editor and preview. When you edit the preview, Turndown converts HTML changes back to Markdown, updates the editor, and re-renders — all within milliseconds.

## 💬 Support & Feedback

- **Live Demo:** [markdownlive.dev](https://markdownlive.dev)
- **Email:** [support@ikemo.io](mailto:support@ikemo.io)
- **Developer:** [iKemo.io](https://ikemo.io/?utm_source=markdownrepo&utm_medium=referral&utm_campaign=site_link)

Have a feature request or found a bug? We'd love to hear from you!

## 🙏 Acknowledgments

Special thanks to the open-source community and these incredible projects:

- Monaco Editor by Microsoft
- Marked by Christopher Jeffrey
- DOMPurify by Cure53
- Turndown by Dom Christie
- Vite by Evan You

---

<div align="center">

**Built with ❤️ by [iKemo](https://ikemo.io/?utm_source=markdownrepo&utm_medium=referral&utm_campaign=site_link)**

Copyright © 2026 **iKemo**. All Rights Reserved.

*Making Markdown editing effortless*

</div>
