# Bilal Irfan

**Applied AI engineer.** I build LLM applications and measure whether they're right.

[bilalirfanportfolio.online](https://www.bilalirfanportfolio.online)

I build LLM systems you can check: answers that show their working, trace back to a source, and admit when there isn't one. I score them against a benchmark instead of trusting a demo. Python and TypeScript day to day, Rust when something has to be fast and local, Linux throughout.

## Selected work

### [AskMyDoc](https://github.com/BilalIrfanContact/AskMyDoc)

Ask a company's 10-K a question and get an answer you can check. Calculations go through a calculator instead of the model, every number in the answer is checked against the filing, and anything it can't back up becomes "not in the document".

On a held-out set of 34 questions, run once, it answered **21 of 26** answerable questions correctly and refused **8 of 8** that the filing doesn't answer.

<img src="https://raw.githubusercontent.com/BilalIrfanContact/AskMyDoc/main/.github/readme/score-progress.svg" alt="Bar chart of working-set score as each change landed, rising from 5 of 41 correct to 29 of 41." width="720">

[Website](https://askmydoc-drab.vercel.app) · [Repo](https://github.com/BilalIrfanContact/AskMyDoc)

### [Sketchnote](https://github.com/BilalIrfanContact/sketchnote)

Show your coding agent the problem instead of typing it out. Hit a hotkey, talk, and draw on your screen. One Ctrl+V pastes timestamped notes and an annotated contact sheet into Claude Code, Codex, or any chat box. It's a GNOME Shell extension with a Rust service behind it, and transcription runs locally with whisper.cpp. It installs with one command and ships as versioned releases.

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/BilalIrfanContact/sketchnote/main/docs/images/anatomy-light.png">
  <img src="https://raw.githubusercontent.com/BilalIrfanContact/sketchnote/main/docs/images/anatomy-light.gif" alt="Sketchnote drawn as a film crew, with labels following a capture from the GNOME extension through recording and transcription to Ctrl+V." width="720">
</picture>

[Website](https://get.sketchnote.workers.dev) · [Repo](https://github.com/BilalIrfanContact/sketchnote)

## Open source

Merged a fix to [bulwark-mcp](https://github.com/churik5/bulwark-mcp/pull/7), a proxy that catches prompt injection before it reaches your AI agent: it now explains what's wrong when Ollama isn't running instead of failing opaquely.

## Stack

<p align="center">
  <img src="./Icons/stack/python.svg" alt="Python" title="Python" height="36">&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./Icons/stack/typescript.svg" alt="TypeScript" title="TypeScript" height="36">&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./Icons/stack/rust.svg" alt="Rust" title="Rust" height="36">&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./Icons/stack/fastapi.svg" alt="FastAPI" title="FastAPI" height="36">&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./Icons/stack/nextdotjs.svg" alt="Next.js" title="Next.js" height="36">&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./Icons/stack/postgresql.svg" alt="PostgreSQL" title="PostgreSQL" height="36">&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./Icons/stack/linux.svg" alt="Linux" title="Linux" height="36">&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./Icons/stack/claude.svg" alt="Claude Code" title="Claude Code" height="36">
</p>

<p align="center">Retrieval and evals · tool calling · Supabase · GitHub Actions · Vercel</p>

## Contact

[Email](mailto:bilalirfancontact@gmail.com) · [Portfolio](https://www.bilalirfanportfolio.online) · [LinkedIn](https://linkedin.com/in/bilalirfancontact) · [X](https://x.com/biloo0_2)
