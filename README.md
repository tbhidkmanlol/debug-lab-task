# Debug Lab — Front-End Build Challenge

Two responsive program pages for [Debug Lab](https://www.thedebuglab.com/debug/), built as part of the technical interview task.

## Implemented Pages

| Page Target | File Pathway | Description |
| :--- | :--- | :--- |
| **Landing Page** | `index.html` | The landing page from the [original site](https://www.thedebuglab.com/debug/). |
| **Software Development** | `software-development.html` | Showcase Debug Lab's coding & software tracks for kids and teens. |
| **STEM Workshop** | `stem-workshop.html` | Showcase Debug Lab's hands-on STEM workshops and maker activities. |

## Live preview
The integrated layout can be viewed here: https://tbhidkmanlol.github.io/debug-lab-task/index.html

## Tech stack

- **HTML5** — semantic structure
- **Tailwind CSS (CDN)** — utility styling, matching the provided template
- **Google Fonts (Outfit)** — brand typography
- **Material Symbols** — icons

**Why plain HTML?** 
- It's simply the fastest and most practical approach for a static two-page expansion task. Keeping it to vanilla HTML avoids over-engineering the codebase and keeps the repository lightweight for evaluation.

## Key decisions

- Reused navbar and footer from `index.html` for visual consistency.
- Active page state highlighted in the Programs dropdown.
- Program copy and age ranges aligned with the live Debug Lab landing page where available.
- CTAs use the same external links as the live site (Google Form + WhatsApp) so they work on static hosting.
