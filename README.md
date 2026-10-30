# Present Continuous & Prepositions Adventure — A1 ESL Quiz

A gamified, single-file webpage quiz for young learners (A1 level) covering **present continuous (-ing forms)** and **prepositions of place**, with grammar, reading comprehension (with visuals), and speaking sections.

## Contents

| File | Purpose |
|------|---------|
| `index.html` | Page structure (start, section intros, quiz, results) |
| `style.css` | Kid-friendly card UI |
| `script.js` | Quiz engine: scoring, streaks, levels, progress, confetti |
| `questions.json` | 100 questions (30 grammar, 30 prepositions, 20 reading, 20 speaking) |

## Features

- **Grammar (30):** choose the correct `-ing` form, fix auxiliary errors (`am/is/are + -ing`), and build sentences by dragging word tiles.
- **Prepositions (30):** SVG visuals — choose `in`, `on`, `under`, `behind`, `in front of`, `next to`, `between`.
- **Reading (20):** illustrated 4-part park story with comprehension questions per part.
- **Speaking (20):** open-ended prompts with star self-rating and sentence starters.
- **Gamification:** score, streak, level, progress bar, per-section intros, confetti on streaks, best-score persistence.
- **No build step:** open `index.html` directly in a browser (loads `questions.json` if served, otherwise falls back to embedded data).

## Sections

1. Grammar - The -ing Machine (🔤)
2. Prepositions - Where is the Cat? (📍)
3. Reading - A Fun Day in the Park (📖)
4. Speaking - Let's Talk! (🎤)

## Usage

Open `index.html` in any modern browser. No installation or server required.

## License

MIT
