# 🩺 JSON Doctor

### A Fast, Privacy-First JSON Validator & Formatter

Validate, format, and minify JSON effortlessly with a clean, responsive, and animated interface. Built with vanilla HTML, CSS, and JavaScript, JSON Doctor works entirely in your browser — no backend, account, dependencies, or API key required.

<p align="center">
  <a href="https://json-doctor-cyan.vercel.app/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Try_JSON_Doctor-7C3AED?style=for-the-badge" alt="Live Demo" />
  </a>
  <a href="https://github.com/Muhtasim-Masum-Hasnayen/json-doctor">
    <img src="https://img.shields.io/badge/GitHub-Source_Code-181717?style=for-the-badge&logo=github" alt="GitHub Repository" />
  </a>
</p>

---

## 🎬 Project Preview

<p align="center">
  <img src="./portfolio_.gif" alt="JSON Doctor animated project preview" width="100%" />
</p>

<p align="center">
  <i>Clean interface. Instant feedback. Effortless JSON handling.</i>
</p>

---

## ✨ Key Features

- **JSON Validation** — Detect invalid JSON using the browser's native parser.
- **Smart Formatting** — Prettify JSON with consistent two-space indentation.
- **JSON Minification** — Remove unnecessary whitespace for compact output.
- **Syntax Highlighting** — Visually distinguish keys, strings, numbers, booleans, and `null`.
- **Helpful Error Feedback** — Display parser errors and approximate error positions when available.
- **One-Click Copy** — Copy formatted or minified JSON to the clipboard.
- **JSON Download** — Export the output as a `.json` file.
- **Live Statistics** — Track lines, characters, and input size.
- **Quick Sample** — Explore the tool with sample JSON instantly.
- **Responsive UI** — Use the application across desktop, tablet, and mobile devices.
- **Keyboard Shortcuts** — Validate with `Ctrl + Enter` or `Cmd + Enter`; use `Tab` to insert spaces in the editor.
- **Privacy by Design** — Process JSON locally in your browser without uploading it to a server.

## 🔒 Privacy First

Your JSON data stays in your browser.

JSON Doctor does not require an account, API key, or backend to validate and format JSON. Its core processing uses the browser's native JavaScript capabilities, helping keep your data under your control.

> Avoid pasting sensitive production credentials or confidential data into any tool unless you have verified its implementation and environment.

---

## 🛠️ Built With

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Deployment-Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
</p>

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Responsive layouts, gradients, animations, and styling |
| Vanilla JavaScript | JSON parsing, validation, formatting, and interactions |
| Browser APIs | Clipboard, Blob, and file downloads |
| Vercel | Live deployment |

---

## 🚀 Getting Started

Run JSON Doctor locally in just a few steps.

### Prerequisites

- A modern web browser
- Git (optional)

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/Muhtasim-Masum-Hasnayen/json-doctor.git
```

**2. Open the project directory**

```bash
cd json-doctor
```

**3. Launch the application**

Open `index.html` directly in your browser.

Alternatively, start a local development server:

```bash
python -m http.server 8000
```

Visit [http://localhost:8000](http://localhost:8000).

No package installation or build process is required.

---

## 📁 Project Structure

```text
json-doctor/
├── index.html       # Application structure, styles, and logic
├── README.md        # Project documentation
└── portfolio_.gif   # Animated project preview (optional)
```

*The structure above assumes the application is contained in `index.html` and the GIF is stored in the repository root.*

---

## 🧪 How to Use

1. Open [JSON Doctor](https://json-doctor-cyan.vercel.app/).
2. Paste your JSON or click **Sample** to load an example.
3. Click **Validate JSON** to check syntax.
4. Select **Format** to prettify valid JSON or **Minify** to compact it.
5. Copy the result or download it as a `.json` file.

**Keyboard shortcut:** Press `Ctrl + Enter` on Windows/Linux or `Cmd + Enter` on macOS to validate.

---

## ⚠️ Limitations

- JSON must follow standard syntax, including double-quoted property names and strings.
- Trailing commas and other non-standard JSON syntax are rejected.
- Parser error messages may vary between browsers.
- Error positions are approximate when inferred from browser error messages.
- JSON Doctor checks JSON syntax; it does not perform custom JSON Schema validation.
- Clipboard functionality may require HTTPS or `localhost`, depending on the browser.

---

## 🔮 Future Enhancements

Potential improvements for future releases:

- [ ] JSON Schema validation
- [ ] Interactive tree-view explorer
- [ ] Compare and diff two JSON documents
- [ ] Drag-and-drop JSON file support
- [ ] Optional light theme
- [ ] Improved error-location reporting

---

## 👨‍💻 About the Developer

**Muhtasim Masum Hasnayen**

Computer Science & Engineering student passionate about web development, software quality assurance, and AI/ML.

I enjoy building practical, user-friendly tools that solve real problems while exploring modern development practices and continuously improving my engineering skills.

<p>
  <a href="https://github.com/Muhtasim-Masum-Hasnayen">
    <img src="https://img.shields.io/badge/GitHub-Follow_My_Journey-181717?style=for-the-badge&logo=github" alt="Follow on GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/muhtasim-masum-hasnayen-048517273/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect_with_Me-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" />
  </a>
</p>

🌐 **Live Project:** [json-doctor-cyan.vercel.app](https://json-doctor-cyan.vercel.app/)

💻 **GitHub:** [Muhtasim-Masum-Hasnayen](https://github.com/Muhtasim-Masum-Hasnayen)

🔗 **LinkedIn:** [Connect with me](https://www.linkedin.com/in/muhtasim-masum-hasnayen-048517273/)

---

## 📄 License

This project is licensed under the **MIT License**. You are welcome to use, modify, and learn from it in accordance with the license terms.

---

<p align="center">
  <b>Built with 💜 and a passion for clean, useful software.</b>
  <br />
  <sub>JSON Doctor — making JSON handling simpler, faster, and more accessible.</sub>
</p>
