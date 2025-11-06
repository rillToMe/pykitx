
---

### ⚙️ Project metadata
- Auto populates `pyproject.toml` with:
  - Name, description, author, email, license, Python version.
  - Entry points (`[project.scripts]`) for CLI execution.
- Auto injects `dependencies` section per template type.
- Sets up `[tool.setuptools.package-data]` to include template/static files.

---

### 💾 Packaging
- Included templates and license files packaged inside the wheel.
- Uses `importlib.resources` and `pkgutil` fallback for compatibility.
- Added `include-package-data = true` in `pyproject.toml`.

---

### 🧠 Developer experience
- Clear CLI help via `argparse`.
- Errors and warnings use concise `[!]` prefixes.
- Success messages use `[✓]`.
- Sensible defaults and helpful “Next steps” messages.

---

### 🧾 Documentation
- Project docs hosted at [**pykit.vercel.app**](https://pykit.vercel.app).
- README with examples and template usage.
- License: MIT.

---

### Credits
Built by **Adit**  
Maintained by **DitDev**

---

> 🧾 PyKit - modern Python project initializer  
> Scaffold clean, ready-to-publish packages and apps in one command.
