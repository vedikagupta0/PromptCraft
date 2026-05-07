# PromptCraft ✦ AI Prompt Builder

> Build powerful, structured prompts for AI image & text generation — visually, interactively, instantly.

## What Is It?

PromptCraft is a single-file, zero-dependency HTML app that helps you compose high-quality prompts for AI image generators (Midjourney, DALL·E, Stable Diffusion, Flux, etc.) and text models (Claude, GPT, Gemini, etc.).

Instead of staring at a blank text box, you click your way through curated option cards — art styles, lighting, mood, composition, tone, audience, constraints — and the builder assembles a coherent, professional prompt in real time.

---

## Features

- **Dual Mode** — Switch between Image Prompt mode and Text Prompt mode, each with their own tailored category sets
- **Visual Option Cards** — Browse 100+ options across multiple categories with descriptions explaining *why* each modifier matters
- **Live Prompt Builder** — Selected options assemble into a formatted prompt instantly as you click
- **Chip Management** — Selected options appear as removable chips above the builder for easy review
- **Custom Subject Field** — Add your own subject or core idea that anchors the generated prompt
- **One-Click Copy** — Copy the finished prompt to clipboard instantly
- **Search / Filter** — Search across all options by label or description keyword
- **Category Sidebar** — Jump to any category instantly; badges show how many options are selected per category
- **Sample Prompts Library** — Collapsible examples panel with real prompts and expert breakdowns explaining *why* each prompt works
- **Zero Dependencies** — Pure HTML, CSS, and JavaScript. One file. No build step, no npm, no framework
- **Fully Offline** — Works without an internet connection (after the Google Fonts load)

---

## Quick Start

```bash
# Clone the repo
git clone https://github.com/vedikagupta0/PromptCraft.git

# Open in your browser — that's it
open promptcraft.html
```

No server required. No install. Just open the HTML file.

---

## Image Prompt Categories

| Category | Options | What It Controls |
|---|---|---|
| 🎨 Art Style | 46 | Visual language, artistic movement, rendering aesthetic |
| 💡 Lighting | 28 | Mood, atmosphere, directionality of light |
| 🌫 Mood & Atmosphere | 24 | Emotional register and feeling of the scene |
| 🖼 Composition | 23 | Framing, perspective, visual hierarchy |
| 🎭 Color Palette | 28 | Color relationships, saturation, tonal character |
| ⚙️ Quality & Render | 28 | Technical quality signals and rendering directives |
| 📐 Format & Dimensions | 16 | Aspect ratios and output format |
| 🌟 Subject Matter | 20 | Primary genre and focal subject |
| 🌍 Environment & Setting | 20 | World-building and scene location |
| 📷 Camera & Lens | 16 | Focal length, optical character, photographic feel |
| 🕰 Time Period / Era | 18 | Historical, contemporary, or futuristic context |

## Text Prompt Categories

| Category | Options | What It Controls |
|---|---|---|
| 📄 Output Format | 38 | Structural shape of the content |
| 🎙 Tone & Voice | 22 | Personality and emotional register |
| 👥 Target Audience | 20 | Vocabulary level, assumptions, depth |
| 📏 Length & Depth | 13 | Verbosity and comprehensiveness |
| 🏗 Structure & Style | 20 | How ideas flow and connect |
| 🎭 Persona / Role | 20 | Identity and professional perspective |
| 🔒 Constraints & Rules | 28 | Explicit rules that shape output |
| 🎓 Subject Domain | 24 | Field or industry grounding |

---

## How to Use

**1. Choose a mode** — Image Prompts or Text Prompts using the tabs at the top.

**2. Browse categories** — Scroll through the option cards or use the sidebar to jump to a specific category.

**3. Click options** — Each click toggles the option. Selected options appear as chips in the builder above.

**4. Add your subject** — Type your main subject or idea into the "Your Subject / Core Idea" textarea.

**5. Copy and use** — Hit "Copy Prompt" and paste into your AI tool of choice.

**Pro tip:** Open the examples panel at the bottom to see professional prompts with expert commentary on *why* each element was included.

---

## Project Structure

```
promptcraft.html   ← The entire application (single file)
README.md          ← This file
```

Everything — HTML, CSS, JavaScript, and all data — lives in one self-contained HTML file. No external dependencies beyond Google Fonts.
---

## Contributing

Pull requests welcome. Useful contributions include:

- New option cards with accurate, useful descriptions
- New categories that cover gaps (e.g. negative prompts, model-specific modifiers)
- Additional example prompts in the examples panel
- Accessibility improvements
- Dark/light theme toggle
- Export to JSON feature

Please keep option descriptions in the same format: one sentence on *what* it does, one on *when* to use it or what it evokes.

---

## License

MIT — use it, fork it, embed it, modify it. Attribution appreciated but not required.

---

<p align="center">
  Made with obsessive attention to prompt craft.<br>
  <em>Good prompts are the difference between mediocre and extraordinary AI output.</em>
</p>
