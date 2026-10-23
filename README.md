# JSON Doctor 🩺
**🔗 Try the Live Demo:
https://lnkd.in/dwyE7f32**  
A polished, responsive JSON validation and formatting tool built with **vanilla HTML, CSS, and JavaScript**. It runs entirely in your browser — no backend, dependencies, account, or API key required.
# GitHub Profile
**💻 Explore My GitHub & Follow My Journey:
https://lnkd.in/d5WFGYJ4**
## ✨ Features

- **Validate JSON** using the browser's native `JSON.parse()` parser.
- **Format / prettify** valid JSON with two-space indentation.
- **Minify** valid JSON into a compact single-line representation.
- **Syntax-highlighted preview** for keys, strings, numbers, booleans, and `null`.
- **Error feedback** with the browser's parser message and an approximate position when the browser provides one.
- **Quick sample** to try the tool instantly.
- **Copy output** to clipboard and **download as `.json`**.
- **Live stats** for lines, characters, and input size.
- Responsive animated UI, keyboard support (`Ctrl/Cmd + Enter` to validate; `Tab` inserts spaces in the editor).
- Privacy-friendly: the JSON is processed locally in the browser and is not uploaded.

## 🚀 Run locally

No installation is needed.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

Optional: serve it locally from the project directory:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## 📁 Project structure

```text
json-doctor/
├── index.html
└── README.md
```

## 🧪 Try it

Click **Sample** to load an example, then use **Validate JSON**, **Format**, or **Minify**. You can also paste your own JSON into the editor.

## 🛠 Built with

- HTML5
- CSS3 (responsive layout, gradients, animations, reduced-motion support)
- Vanilla JavaScript
- Browser APIs: `JSON.parse`, `Blob`, Clipboard API, and object URLs

## ⚠️ Notes and limitations

- JSON must follow the standard syntax: property names and strings use double quotes, and trailing commas are not allowed.
- Exact parser error wording differs by browser. Error positions are shown as approximate only when the browser includes a character position in its message.
- This is a client-side utility, not a JSON schema validator. It checks syntax and provides basic root-level information; it does not validate data against a custom schema.
- Clipboard access may require HTTPS or `localhost` in some browsers.

## 🌱 Possible next improvements

- JSON Schema validation
- Tree-view explorer and collapsible nodes
- Diff two JSON payloads
- Drag-and-drop `.json` file input
- Optional light theme

## 📄 License

MIT — feel free to use, modify, and learn from this project.
