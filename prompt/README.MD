# Prompt Framework

**An open‑source, MIT‑licensed library of meta‑prompts for building and customizing advanced AI prompts powered by the meta-prompting technique.**

---

## 🚀 Overview

**Prompt Framework** is a collection of **meta‑prompts**—parameterized templates that guide AI models to generate new, domain‑specific prompts. Instead of crafting prompts from scratch, you instantiate and customize these meta‑prompts to accelerate prompt engineering for diverse tasks.

This repository provides:

1. **Four core use‑case modules**, each containing **20 curated meta‑prompts**:

   - Programming & Software Development
   - Market Research
   - Sentiment Analysis
   - Social Media Post Creation

2. comming soon: **A CLI tool and Python module** to programmatically import and use prompts from external sources (.json or .md) .
3. **Guidelines** for adaptation, ethical usage, and best practices.
4. **Examples** and practical **Use cases** of the prompts.

---

## Project Structure

```text
README.md                  ← Project documentation
prompts/                    ← Root folder for prompt modules
├── programming/            ← 20 meta‑prompts for code tasks
├── market_research/        ← 20 meta‑prompts for competitive insights
├── sentiment/              ← 20 meta‑prompts for sentiment classification
└── social_media/           ← 20 meta‑prompts for content generation

cli/                        ← CLI and module source code
├── prompt_framework/       ← Python package
│   ├── __init__.py
│   ├── loader.py           ← External prompt loader logic
│   └── cli.py              ← Entry point for CLI
LICENSE                     ← MIT License
```

---

## 🔍 Prompt Use Cases

Each module contains **20 meta‑prompts** in `.json` or `.md` format. You can:

- **Instantiate** a meta‑prompt by replacing placeholder tokens (`<Task>`, `<Dataset>`, `<Persona>`, etc.).
- **Chain** meta‑prompts to build multi‑step workflows.
- **Extend** with domain‑specific variables: industry, language, style, tone.

(See individual folders for full lists of prompts.)

---

## Getting Started

### clone the repository

```bash
git clone https://github.com/your‑org/prompt‑framework.git
cd prompt‑framework

- gain access to the framework and start experimenting and tweaking
```

## CLI tool will be available soon and can e used to generate random meta prompts

## Customization & Best Practices

- **Tweak placeholders** to fit your domain (e.g., replace `<Industry>` with `fintech`).
- **Chain meta‑prompts** for pipelines: research → analysis → creation.
- **Avoid malicious use**: licensed under MIT for **ethical purposes only** (no phishing, spam, disallowed content).
- **Optimize** by adjusting AI parameters: temperature, max tokens, and system instructions.

---

## License

This project is released under the **MIT License**. See [LICENSE](LICENSE) for details.

> "Use and modify freely. Attribution appreciated, but not required."

---

## 🤝 Contributing

Contributions welcome:

- Add new meta‑prompts or modules.
- Improve with CLI features or add new commands.
- Enhance documentation and examples.

---

**Created by prompt engineers for prompt engineers**
