# 🧠 LIVE-EPISODES — AI Handoff Document

> Purpose: Provide a comprehensive guide for any AI system (Claude, GPT, Gemini, Copilot, etc.) to handle context and continue building the LIVE-EPISODES project without breaking existing functionality.

---

## 1. Project Identity

- **Project Name:** LIVE-EPISODES
- **Owner / Builder:** AIVaneer (GitHub: https://github.com/AIVaneer)
- **Repository:** https://github.com/AIVaneer/LIVE-EPISODES
- **Live Deployment:** https://aivaneer.github.io/LIVE-EPISODES/
- **Mission Motto:** *"Collaborative learning through live integration and innovation."*
- **Tone:** Professional, minimalistic, neon/cyberpunk aesthetic, user-centric.

---

## 2. What LIVE-EPISODES Is

LIVE-EPISODES is an **interactive real-time education and music hub** for the PCVR EdTech ecosystem. It serves as the GitHub Pages portal for AIVaneer's music catalog and live coding episodes.

The project includes:
- **Music Cards:** Prominent, featured cards linking to AIVaneer's Audius music profile and PCVR catalog.
- **Project Cards:** Cards linking to related PCVR EdTech projects and live portals.
- **Card System:** Expandable grid with dedicated sections for future links, resources, or episodes.

---

## 3. Repository Structure

```
LIVE-EPISODES/
├── index.html                # Main GitHub Pages entry point (card system hub)
├── assets/
│   └── css/
│       └── cards.css         # Card system stylesheet (sections, grid, hover effects)
├── README.md
├── LICENSE
└── AI_HANDOFF.md             # This file
```

**Do not** modify or delete any file unless explicitly instructed.

---

## 4. Card System Design Pattern (IMPORTANT — follow exactly)

Cards are organized into **sections** inside `index.html`:

```html
<section class="section">
    <h2 class="section-title neon">🎵 SECTION TITLE</h2>
    <div class="cards">

        <!-- Featured card (full-width, use only once per section) -->
        <div class="card card-featured">
            <div class="card-header">
                <span class="card-icon">🎵</span>
                <h3 class="card-title">Card Title</h3>
            </div>
            <div class="card-body">
                <p class="card-description">Short description of the card content.</p>
            </div>
            <div class="card-footer">
                <a href="URL" target="_blank" class="card-link link-music">CTA Text</a>
            </div>
        </div>

        <!-- Standard card -->
        <div class="card">
            <div class="card-header">
                <span class="card-icon">🔊</span>
                <h3 class="card-title">Card Title</h3>
            </div>
            <div class="card-body">
                <p class="card-description">Short description.</p>
            </div>
            <div class="card-footer">
                <a href="URL" target="_blank" class="card-link">CTA Text</a>
            </div>
        </div>

        <!-- PLACEHOLDER: Add more cards here -->

    </div>
</section>
```

### Card Link Classes
| Class | Color | Use For |
|---|---|---|
| `card-link` | `#00ff9d` (green) | General / project links |
| `card-link link-music` | `#ff00ff` (magenta) | Music links |

---

## 5. CSS Architecture

All card-specific styles live in `assets/css/cards.css`. The base page styles (body, container, scanline animation, headings) stay inline in `index.html`.

**To add new card variants:** add a modifier class in `cards.css` (e.g., `.card-episode`, `.link-episode`) and apply it in `index.html`.

---

## 6. Build Guidelines for AIs

1. **Confirm before committing changes.**
2. **Explicit Approval Only**: Modify only files explicitly named.
3. Maintain the current section/card structure pattern.
4. New external links go inside the appropriate `<!-- PLACEHOLDER -->` comment.
5. Only introduce external dependencies with prior approval.

---

## 7. Roadmap

Planned features:
- Episode-wise progression system with dedicated episode cards.
- Live collaboration tools for educators and learners.
- Additional music sections (SoundCloud, Spotify, YouTube).
- Enhanced AI integration with context-aware assistance.

---

## 8. Hand-Off Summary

This document maintains the integrity of the LIVE-EPISODES project while enabling further expansion by any AI system. Follow the card pattern and section structure to ensure visual and functional consistency.

---
