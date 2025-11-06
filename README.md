<div align="center">

# 🧰 PyKit

**Modern Python project initializer - inspired by `npm init`.**

[![PyPI](https://img.shields.io/pypi/v/pykitx?color=6ea8fe&label=PyPI)](https://pypi.org/project/pykitx)
[![Python](https://img.shields.io/badge/python-%3E%3D3.8-blue.svg)](https://www.python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Docs](https://img.shields.io/badge/docs-online-brightgreen.svg)](https://pykit.vercel.app)

</div>

---

## 🚀 What is PyKit?

PyKit is a **modern Python project initializer** -  
think of it as `npm init` for Python 🐍.

With **one command**, you can scaffold a complete Python project  
ready with proper structure, CI, license, and optional templates (CLI, web, TUI).

---

## ⚙️ Installation

```bash
pip install pykitx
```

> ⚠️ *Temporary package name is `pykitx` while waiting for the `pykit` name approval on PyPI.*

---

## 🧱 Usage

Create a new Python project instantly:

```bash
pykit new myproject
```

Choose a template for your project:

```bash
pykit new myproject -T <template>
```

Available templates:

| Template | Description |
|-----------|-------------|
| `cli-stdlib` | Simple CLI using `argparse` |
| `cli-typer` | Modern CLI with [Typer](https://typer.tiangolo.com) |
| `cli-click` | Command-line app using [Click](https://click.palletsprojects.com) |
| `tui-rich` | Terminal UI with [Rich](https://github.com/Textualize/rich) |
| `web-fastapi` | Minimal [FastAPI](https://fastapi.tiangolo.com) web app (dark mode, DitDev footer) |
| `web-flask` | Minimal [Flask](https://flask.palletsprojects.com) web app (DitDev footer) |

---

## 🧩 Example

```bash
pykit new astro -T web-fastapi --init-git

cd astro
pip install -e .
astro
# → runs at http://127.0.0.1:8000
```

Resulting structure:
```
astro/
├─ pyproject.toml
├─ README.md
├─ requirements.txt
├─ LICENSE
├─ .gitignore
├─ .github/workflows/ci.yml
├─ src/astro/
│  ├─ __init__.py
│  ├─ main.py
│  ├─ templates/
│  │  ├─ base.html
│  │  └─ 404.html
│  └─ static/
│     ├─ css/styles.css
│     ├─ js/app.js
│     └─ img/{logo.svg,favicon.svg}
└─ tests/
```

---

## ✨ Features

- ⚡ **One-shot scaffold:** instantly create a full Python package/app.
- 📦 **Smart structure:** follows modern `src/` layout and PEP 621 (`pyproject.toml`).
- 🎨 **Web templates:** FastAPI & Flask dark-mode sites with DitDev footer and tooltips.
- 💻 **CLI templates:** Typer, Click, Rich TUI, or plain `argparse`.
- 🧾 **Auto metadata:** README, License, CI, and `.gitignore` generated.
- 🪄 **Requirements & .env:** automatic `requirements.txt` and `.env.example`.
- 💬 **Friendly UX:** "Next steps" message after scaffold.
- 🧰 **Template-safe:** templates packaged inside the wheel; works anywhere.
- 🧱 **Extensible:** future support for custom `--org`, `--github`, and auto updates.

---

## 💡 Background & Philosophy

> “Why not make starting a Python project as easy as `npm init`?”

PyKit was born from the idea that **Python deserves a modern, developer-friendly initializer**.  
Instead of typing boilerplate by hand or copying folders, one command sets up everything:
- structure (`src/`, `tests/`)
- metadata (`pyproject.toml`)
- web/CLI templates
- license & CI

PyKit helps **developers save time** and **stay consistent** across all projects -  
just type it and start coding.

---

## 📘 Documentation

For detailed usage, template previews, and customization guide:  
👉 **[https://pykit.vercel.app](https://pykit.vercel.app)**

---

## 🧑‍💻 Author

**Adit** - *DitDev / AetherStudio*  
- GitHub: [https://github.com/rillToMe](https://github.com/rillToMe)  
- Email: [rahmataditya2817@gmail.com](mailto:rahmataditya2817@gmail.com)

---

## 🪪 License

**MIT License**  
© Adit (DitDev)

---

<div align="center">

Built with ❤️ by **AetherStudio × DitDev**

</div>
