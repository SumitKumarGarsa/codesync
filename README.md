# CodeSync — Online Playground & Multi-Language IDE

> A powerful browser-based code playground with real-time compilation, multi-language support, and a feature-rich editor experience.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?style=for-the-badge&logo=vercel)](https://code-deck.vercel.app/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Judge0](https://img.shields.io/badge/Judge0%20CE-API-blue?style=for-the-badge)](https://ce.judge0.com/)
[![Styled Components](https://img.shields.io/badge/Styled--Components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)](https://styled-components.com/)

---

## 📸 Preview

[![CodeSync Home Page]

> 🎬 Click the image above to watch the demo video on YouTube.

---

## 🚀 Live Project

🔗 [https://code-deck.vercel.app/](https://code-deck.vercel.app/)

---

## 📌 About

**CodeSync** is a fully client-side online IDE that lets developers write, run, and manage code snippets directly in the browser — no setup required. It supports multiple programming languages, themes, and file operations, with persistent storage so your playgrounds are always saved locally.

---

## ✨ Features

- 🧩 **Multi-Playground Management** — Create, save, and manage multiple code snippets, all persisted in local storage
- 🌐 **Multi-Language Support** — Write and execute code in C++, Python, Java, and JavaScript
- 🎨 **Multi-Theme Support** — Switch between editor themes for a personalized coding experience
- ⚡ **Live Compilation** — Real-time code execution powered by Judge0 CE API via Rapid API
- 📁 **File I/O** — Upload code files as input and download output results directly from the browser
- 📤 **Upload & Download Code** — Load existing code files into the editor or export your work
- 🖥️ **Fullscreen Mode** — Distraction-free coding with fullscreen editor support
- 🔲 **Flexible Layout** — Resizable split-pane layout for editor and console panels
- 📋 **Input & Output Console** — Dedicated input/output panels with support for uploading text files as stdin

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js |
| Styling | Styled Components |
| Code Editor | CodeMirror (`@uiw/react-codemirror`) |
| Compilation API | Judge0 CE API |
| API Gateway | Rapid API |
| HTTP Client | Axios |
| Routing | React Router |
| Deployment | Vercel |

---

## ⚙️ Getting Started

### Prerequisites

- Node.js >= 16.x
- npm or yarn
- A free [Rapid API](https://rapidapi.com/) account with Judge0 CE API access

### Installation

```bash
# Clone the repository
git clone https://github.com/sumitkumargarsa/codesync.git

# Navigate into the project
cd codesync

# Install dependencies
npm install
```

### Environment Setup

Create a `.env` file in the root directory:

```env
REACT_APP_RAPID_API_KEY=your_rapidapi_key_here
REACT_APP_RAPID_API_HOST=judge0-ce.p.rapidapi.com
```

### Run Locally

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
npm run build
```

---

## 📂 Project Structure

```
codesync/
├── public/
├── src/
│   ├── assets/          # Images and static assets
│   ├── components/      # Reusable UI components
│   ├── pages/           # Page-level components
│   ├── utils/           # API helpers and utilities
│   ├── App.js
│   └── index.js
├── .env
├── package.json
└── README.md
```

---

## 🔗 API & References

| Resource | Link |
|---|---|
| Judge0 CE API Docs | [https://ce.judge0.com/](https://ce.judge0.com/) |
| Judge0 on Rapid API | [https://rapidapi.com/judge0-official/api/judge0-ce](https://rapidapi.com/judge0-official/api/judge0-ce) |
| CodeMirror for React | [https://uiwjs.github.io/react-codemirror/](https://uiwjs.github.io/react-codemirror/) |
| Styled Components Docs | [https://styled-components.com/docs/basics](https://styled-components.com/docs/basics) |
| Vercel Deployment | [https://vercel.com/](https://vercel.com/) |

---

## 🙋‍♂️ Author

**Sumit Kumar Garsa**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sumitkumargarsa-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/sumitkumargarsa/)
[![GitHub](https://img.shields.io/badge/GitHub-sumitkumargarsa-181717?style=flat-square&logo=github)](https://github.com/sumitkumargarsa)

---

## 📄 License

This project is open source and available under the [MIT License](./LICENSE).
