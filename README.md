# Debug Lab — Front-End Build Challenge

Two responsive program pages for [Debug Lab](https://www.thedebuglab.com/debug/), built as part of the technical interview task.

## Live preview
The integrated layout can be viewed here: https://tbhidkmanlol.github.io/debug-lab-task/index.html

## Implemented Pages

| Page Target | File Pathway | Description |
| :--- | :--- | :--- |
| **Landing Page** | `index.html` | The landing page from the original site. |
| **Software Development** | `software-development.html` | Showcase Debug Lab's coding & software tracks for kids and teens. |
| **STEM Workshop** | `stem-workshop.html` | Showcase Debug Lab's hands-on STEM workshops and maker activities. |

## Tech stack

- **HTML5** — semantic structure
- **Tailwind CSS (CDN)** — utility styling, matching the provided template
- **JavaScript (Vanilla)** — Intersection Observer API for performance-focused scroll triggering
- **Google Fonts (Outfit)** — brand typography
- **Material Symbols** — icons

**Why plain HTML?** 
- It's simply the fastest and most practical approach for a static two-page expansion task. Keeping it to vanilla HTML avoids overengineering the codebase and keeps the repository lightweight for evaluation.

## Key decisions & Enhancements

- **Visual Consistency:** Reused navbar and footer layout structures across all child templates.
- **Curriculum Symmetry:** Restructured the progression cards on `software-development.html` to follow a consistent 3-stage modular template (**Beginner > Intermediate > Advanced** / **Format Breakdown**).
- **Fluid Micro-Animations:** Extended the Tailwind runtime engine configuration with custom translation keyframes to build elegant page-load and scroll-triggered fade entries via a native JavaScript Intersection Observer.
- **Audience-Focused Copy:** Fine-tuned the descriptive copy to be highly accessible and engaging for kids and parents, removing corporate tech jargon in favor of authentic project milestones.
- **Functional Integration:** CTAs use matching external links from the live center profiles (Google Forms and WhatsApp channels) to make the live deployment fully interactive.
