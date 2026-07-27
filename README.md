<div align="center">

![Maher Magic Puzzle animated header](https://capsule-render.vercel.app/api?type=waving&height=280&color=gradient&customColorList=2,3,25,26&text=Magic%20Puzzle&fontColor=ffffff&fontSize=76&fontAlignY=38&desc=Any%20image%20%E2%86%92%20a%20sliding%20puzzle&descAlignY=60&animation=fadeIn)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Montserrat&weight=800&size=24&duration=3000&pause=800&color=F59E0B&center=true&vCenter=true&width=760&lines=Any+Image+%E2%86%92+Sliding+Puzzle;Slide.+Solve.+Smile.;3%C3%973+%C2%B7+4%C3%974+%C2%B7+5%C3%975)](https://maherkhan-builds.github.io/maher-magic-puzzle/)

<p><strong>Upload any photo and it instantly becomes a playable sliding puzzle — right in your browser, no app or account required.</strong></p>

![JavaScript](https://img.shields.io/badge/JavaScript-09090D?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![HTML5 Canvas](https://img.shields.io/badge/HTML5_Canvas-111827?style=for-the-badge&logo=html5&logoColor=E34F26)
![Web Audio API](https://img.shields.io/badge/Web_Audio_API-19151F?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-19151F?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Live-F59E0B?style=for-the-badge)

[Live Demo](https://maherkhan-builds.github.io/maher-magic-puzzle/) · [Features](#-what-it-can-do) · [Quick Start](#-run-it-locally) · [How It Works](#-how-it-works)

</div>

---

## ✨ Meet Maher Magic Puzzle

One upload, one instant game: drop in a family photo, a product shot, or a Pinterest find, and it becomes a fully playable, solvable sliding puzzle in your browser — sound effects, confetti, and all.

## 🌱 The problem

Sliding puzzles are a timeless format, but every existing app locks you into stock artwork, ads, or an app-store download. Parents want a safe game built from *their own kids' photos*; brands want a fun, interactive product experience they can drop into a campaign page — without commissioning a custom game build for it.

## 🍓 The solution / What it can do

Maher Magic Puzzle turns any image into a sliding puzzle instantly, entirely client-side — no upload to a server, no sign-up, no install.

| Feature | What it feels like |
|---|---|
| 🖼️ Your image, your puzzle | Drag & drop or pick a photo from your phone gallery — it's saved privately in your browser for next time |
| 🎚️ Three difficulty levels | Beginner 3×3, Advanced 4×4, Expert 5×5 — each with its own best-score tracker |
| 🧩 Always solvable | Shuffled using real, valid moves, so there's never an unsolvable board |
| 🔊 Satisfying slide "snap" | A tile-slide sound synthesized live with the Web Audio API — no sound files |
| 🎉 Win celebration | Confetti burst, victory fanfare, and applause the moment you solve it |
| 👀 Hold to peek | Press and hold to preview the full picture when you're stuck |
| 🔢 Numbered tiles | Optional tile numbers make it toddler-friendly |

**Who it's for:** families turning vacation photos into a game for kids · brands wanting an instant interactive product experience for a campaign microsite · teachers building a quick focus-and-reward activity around a lesson image.

## 🫶 How to use it

1. Open the [live game](https://maherkhan-builds.github.io/maher-magic-puzzle/).
2. Tap **Change image** and pick any photo from your device (or play with the built-in default artwork).
3. Choose Beginner, Advanced, or Expert and start sliding tiles into place.
4. Stuck? Hold to peek at the full picture. Solve it to trigger the confetti celebration.

**Embed it on any website** — the whole game is a single `index.html`:

```html
<iframe src="https://maherkhan-builds.github.io/maher-magic-puzzle/"
        width="420" height="900" style="border:0;border-radius:20px"></iframe>
```

## 🧠 How it works

```
 Image input                 Client-side engine                Feedback
┌────────────────┐        ┌───────────────────────┐        ┌──────────────────┐
│ File picker /    │       │ Canvas-based tile grid │        │ Web Audio API      │
│ drag & drop       │─────▶│ + solvable-shuffle      │───────▶│ synthesized slide  │
│ (or default art)  │       │ algorithm (3×3/4×4/5×5) │        │ "snap" per move     │
└────────────────┘        └───────────┬────────────┘        └──────────────────┘
                                       │ solved?
                                       ▼
                            ┌───────────────────────┐
                            │ <canvas> confetti burst│
                            │ + fanfare + best-score  │
                            │ saved to localStorage   │
                            └───────────────────────┘
```

Everything — the tile grid, the shuffle algorithm, the audio, and the confetti — runs entirely client-side in one HTML file. Images and best scores are kept in the browser's `localStorage`, so nothing you upload ever leaves your device.

## 🛠️ Built with

Plain HTML + CSS + JavaScript in a **single file** — no frameworks, no build step, no external assets. The default artwork is generated in code, the slide "snap" and win fanfare are synthesized live with the **Web Audio API**, and the win celebration is a hand-rolled `<canvas>` confetti animation.

## 🚀 Run it locally

Single static file, zero dependencies.

```bash
git clone https://github.com/maherkhan-builds/maher-magic-puzzle.git
cd maher-magic-puzzle
```

Then just open `index.html` in a browser — or serve it locally:

```bash
npx serve .
```

## 🔎 Keywords

`sliding-puzzle` · `html5-game` · `puzzle-game` · `kids-games` · `web-audio-api` · `brand-engagement` · `interactive-marketing` · `javascript` · `claude-code` · `single-file-app` · `canvas-game` · `no-dependencies`

---

## 👤 Builder

Built by **[Maher Khan](https://digimarketingstudio.com)** — AI educator, no-code builder & digital marketing strategist.

- 🎓 UCLA Extension Guest Lecturer — ChatGPT, LLMs & Agentic AI
- 🏆 LinkedIn Top Voice, North America — 3 consecutive years
- 🛠️ 28+ AI-powered tools built · 20,000+ professionals trained
- 💼 [LinkedIn](https://www.linkedin.com/in/mahersocialmediastrategistus) · [GitHub](https://github.com/maherkhan-builds) · [Instagram](https://www.instagram.com/social.icm) · [Book a call](https://calendly.com/digitalpoles/let-s-meet-up)

Part of the **Maher Magic** series of AI & web apps. ✨ Built with **[Claude Code](https://claude.com/claude-code)** (Anthropic, model Fable) — game logic, solvability-guaranteed shuffling, synthesized audio, and responsive UI in a single session.

## 📄 License

[MIT](LICENSE) — free to use, learn from, and build on.

<div align="center">
  <h3>Slide. Solve. Smile.</h3>
  <p>If Magic Puzzle sparks an idea, drop the repo a ⭐</p>
</div>

![Maher Magic Puzzle footer](https://capsule-render.vercel.app/api?type=waving&height=150&section=footer&color=gradient&customColorList=2,3,25,26&animation=twinkling)
