# MD → HTML Converter

**Turn LLM markdown into polished documents in seconds.**

A zero-install, privacy-first tool that converts Markdown to rich HTML you can paste directly into Word, Quip, Google Docs, and more — with one click.

🌐 **[Try it live](https://peelizulfein.github.io/mdtohtml)** — no install needed

![Screenshot](screenshot.png)

---

## Why This Exists

If you work with LLMs (ChatGPT, Claude, Gemini, etc.), you know the drill:

1. You get beautifully formatted markdown output
2. You need to share it in a "real" document for your team
3. You spend 10 minutes fighting with pandoc, fixing table borders, and deleting "Here's the information you requested!" filler

**This tool eliminates that friction.**

Paste your markdown, click copy, paste into your doc. Done. Your formatting survives, your tables have borders, and the LLM's conversational fluff is gone.

---

## What It Does

| Input | Output |
|-------|--------|
| Raw markdown from any LLM | Rich formatted HTML |
| Messy tables with no borders | Clean tables that paste perfectly into Word |
| "Sure! Here's the table you asked for:" | Just the table |
| Mermaid diagram code | Visual flowcharts you can paste into PowerPoint |

---

## Features

### 🧹 LLM Cleanup
One-click removal of conversational filler. Strips phrases like:
- "Here's the table you requested:"
- "Sure! Below is..."
- "Let me know if you need anything else!"

### 📄 Word/Excel Mode
Copies with inline styles so tables paste with proper borders and formatting in Microsoft Office.

### 📊 Smart Excel Export
Export button appears automatically when your markdown contains tables. Downloads a `.xls` file ready to open.

### 📈 Mermaid Diagrams
LLMs love generating Mermaid flowcharts. This tool renders them as images you can copy into presentations.

### ✏️ Editable Preview
Click the preview pane to make last-minute edits before copying.

### 🔒 100% Private
Single HTML file. No backend. No tracking. Your content never leaves your browser.

### 🌓 Dark/Light Mode
Easy on the eyes, day or night.

### 📁 Drag & Drop
Drop `.md` files directly onto the editor.

---

## Use Cases

### 📝 LLM → Documentation
Generate technical docs, meeting notes, or reports with an LLM, then paste them into your team's wiki or Google Docs with formatting intact.

### 📊 Data Tables for Stakeholders
Ask an LLM to format data as a markdown table, then export directly to Excel or paste into Word with clean borders.

### 🎨 Diagrams for Presentations
Generate Mermaid flowcharts with an LLM, render them visually, and paste into PowerPoint or Keynote.

### 🏢 Corporate Environments
Works on locked-down laptops where you can't install software. Just open the HTML file or use the hosted version.

### ✍️ Blog & Content Writing
Draft in markdown, preview the HTML, then paste into your CMS or email client.

---

## Quick Start

### Option 1: Use Online (Recommended)
Visit **[peelizulfein.github.io/mdtohtml](https://peelizulfein.github.io/mdtohtml)**

### Option 2: Run Locally
```bash
git clone https://github.com/peelizulfein/mdtohtml.git
open mdtohtml/index.html
```

### Option 3: Just Download
Download `index.html` and double-click it. That's it.

---

## How to Use

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   LLM       │ ──▶ │  MD→HTML    │ ──▶ │  Word/Quip  │
│  (markdown) │     │  Converter  │     │  (formatted)│
└─────────────┘     └─────────────┘     └─────────────┘
```

1. **Paste** your markdown into the left pane (or drag a `.md` file)
2. **Click 🧹 Cleanup** to strip LLM filler (optional)
3. **Edit** the preview if needed (it's editable!)
4. **Click 📋 Copy** for general use, or **📄 Word** for Microsoft Office
5. **Paste** into your document

---

## Button Reference

| Button | What It Does |
|--------|--------------|
| 📁 Open | Load a `.md` file from your computer |
| 🧹 Cleanup | Remove LLM conversational filler |
| 💾 HTML | Download as standalone HTML file |
| 📄 Word | Copy with inline styles for Microsoft Office |
| 📊 Excel | Export tables to `.xls` (only shows when tables exist) |
| 🔤 Code | Copy raw HTML for developers |
| 📋 Copy | Copy rich text for Quip, Google Docs, Notion |
| 🌓 | Toggle dark/light mode |

---

## Supported Markdown

| Element | Syntax |
|---------|--------|
| Headers | `#`, `##`, `###`, etc. |
| Bold | `**text**` |
| Italic | `*text*` |
| Lists | `-` or `1.` |
| Code | `` `inline` `` or fenced blocks |
| Tables | GFM style |
| Blockquotes | `>` |
| Links | `[text](url)` |
| Images | `![alt](url)` |
| Task lists | `- [ ]` or `- [x]` |
| Mermaid | ` ```mermaid ` |

---

## Self-Hosting

### GitHub Pages (Free)
1. Fork this repo
2. Go to **Settings** → **Pages**
3. Set source to **main branch** / **root**
4. Live at `https://yourusername.github.io/mdtohtml`

### Any Web Server
Just serve `index.html`. It's a single file with no dependencies.

### Local Use
Double-click `index.html`. Works offline after first load.

---

## Privacy & Security

- **No backend** — everything runs in your browser
- **No analytics** — zero tracking
- **No cookies** — nothing stored
- **No data transmission** — your markdown never leaves your machine
- **External requests** — only to load libraries (marked.js, DOMPurify, mermaid.js) on first load

Safe for confidential documents and enterprise use.

---

## Contributing

PRs welcome! Ideas for improvement:

- [ ] Syntax highlighting for code blocks
- [ ] Custom CSS themes for output
- [ ] Keyboard shortcuts (Cmd+Enter to copy)
- [ ] PWA support for true offline use
- [ ] Browser extension
- [ ] Direct DOCX export

---

## License

MIT — Use it however you want.
