# AI Engineer Roadmap

An interactive, self-hosted progress tracker for learning AI engineering — six phases, in dependency order, from Python fundamentals to a shipped portfolio.

🔗 **Live:** [add your GitHub/Codeberg Pages link here]

## What it is

A single self-contained `index.html` file (no build step, no dependencies) that tracks progress through a structured AI engineering learning path. Tap a phase to expand it, mark it complete, and the next one unlocks automatically.

## Features

- 📋 Six-phase roadmap: Foundations → Pre-trained Models → Building with LLMs → Agents → Production & Shipping → Portfolio
- ✅ Tap-to-complete phases with automatic progression
- 📊 Visual progress bar
- 🌗 Light/dark mode toggle (saved automatically)
- 🎉 Animated congratulations screen on full completion
- 💾 Progress saved locally in your browser — no account, no backend
- 📱 Mobile-first, works fully offline once loaded

## Roadmap structure

| Phase | Focus |
|---|---|
| 0 | Foundations — Python, Git, HTTP/REST/JSON, light math |
| 1 | Working with pre-trained models — APIs, prompt engineering |
| 2 | Building with LLMs — structured outputs, embeddings, RAG |
| 3 | Agents — orchestration, tool use, frameworks |
| 4 | Production & shipping — deployment, evaluation, LLMOps |
| 5 | Portfolio — end-to-end projects, public GitHub presence |

## Usage

Just open `index.html` in any browser — locally or hosted. No installation, no npm, no build tools.

To host it yourself:
1. Fork or clone this repo
2. Enable GitHub Pages (Settings → Pages → Deploy from branch → main → root)
3. Your live URL appears at `https://yourusername.github.io/reponame/`

## Notes

- Progress is stored in `localStorage`, scoped per browser/device — it won't sync across devices unless you use the same browser everywhere.
- Built as a personal learning tracker while following a structured path into AI engineering (as an engineering discipline — building with existing models/APIs, distinct from AI research or training models from scratch).

## License

MIT — do whatever you want with it.