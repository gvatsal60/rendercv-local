# RenderCV Local

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

Generate professional, beautifully formatted CVs from **YAML** configuration files. Version control your resume, iterate with live preview, export to PDF and Markdown.

## ⚡ Quick Start

### 🐳 Using Dev Container (1 min setup)

```bash
git clone https://github.com/gvatsal60/rendercv-local.git
cd rendercv-local
code .
```

→ Click **"Reopen in Container"** when prompted → Done! ✅

### 📦 Local Setup

```bash
git clone https://github.com/gvatsal60/rendercv-local.git
cd rendercv-local
pip install -e .
```

## 🚀 Build Commands

```bash
just           # Clean, sync, and build
just build     # Render your CV
just watch     # Live preview (auto-reload on save)
just --list    # See all commands
```

Output: **PDF** + **Markdown** files in current directory

## 📁 File Structure

```
src/
├── resume.yaml    # Your CV content
├── design.yaml    # Colors, fonts, margins, theme
├── locale.yaml    # Language & date formatting
└── settings.yaml  # App configuration
```

## ✨ Features

- 📝 **YAML-based** - Easy to edit and version control
- 🎨 **Customizable themes** - Multiple professional designs
- 👀 **Live preview** - See changes as you type (`just watch`)
- 📄 **Multi-format export** - PDF + Markdown
- 🌍 **Localization** - Support for multiple languages
- 🐳 **Dev Container** - Pre-configured environment with all extensions

## 🔧 Dev Container Includes

Python 3.13 • RenderCV • PDF Preview • Python Extension • YAML Support • Ruff Linter • Spell Checker • Error Lens

## 📚 Configuration

**resume.yaml** - Personal info, experience, education, skills, projects
**design.yaml** - Theme, colors, typography, margins
**locale.yaml** - Language, date format, translations
**settings.yaml** - App settings

👉 [Full RenderCV docs](https://sinaatalay.github.io/rendercv/)

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)

## 📄 License

Apache 2.0 - See [LICENSE](LICENSE)
