# Usecase — AI in Sports & Carbon Science

A multi-page technical publication exploring how modern AI architectures — including Large Language Models (LLMs), agentic systems, Reinforcement Learning (RL), and Explainable AI (XAI) — are applied to **elite sports performance** and **carbon science** (radiocarbon dating and emissions forecasting).

**Author:** [Prateek Dutta](https://prateekdutta2001.github.io/PrateekDutta.in/)  
**License:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)  
**Version:** June 2026

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Pages & Content Map](#pages--content-map)
5. [Technical Concepts Covered](#technical-concepts-covered)
6. [System Architecture (Feedback-Based Design)](#system-architecture-feedback-based-design)
7. [Getting Started](#getting-started)
8. [Navigation & User Flow](#navigation--user-flow)
9. [Frontend Functionality](#frontend-functionality)
10. [Design System & Styling](#design-system--styling)
11. [Browser & Device Compatibility](#browser--device-compatibility)
12. [Deployment Options](#deployment-options)
13. [Customization Guide](#customization-guide)
14. [References & Data Sources](#references--data-sources)
15. [License & Attribution](#license--attribution)

---

## Overview

**Usecase** is a static, client-side web publication — no backend server, database, or build step required. It presents two deep-dive use cases behind a shared home page that explains cross-cutting AI trends (LLMs, agentic AI, RL, and XAI).

The site is designed for:

- **Practitioners** evaluating which AI architecture fits their data maturity
- **Researchers** reviewing model benchmarks, hyperparameters, and pipeline diagrams
- **Policymakers** understanding explainable, feedback-driven climate and sports systems
- **General technical audiences** learning how India 2036 Olympic AI infrastructure and carbon intelligence converge on the same architectural substrate

---

## Features

| Feature | Description |
|---------|-------------|
| **Multi-page layout** | Home + two dedicated use-case pages (Sports AI, Carbon Science) |
| **Separated concerns** | HTML structure, CSS styling, and JS behaviour in distinct files |
| **Use-case portal cards** | Clickable cards on the home page routing to detailed analyses |
| **Architecture diagrams** | Visual pipeline blocks for HTL-APF, EPRN, Enoch, DGL-GNN, RL+XAI loops |
| **Model comparison tables** | Sortable-style tables with badges, metrics, and architecture columns |
| **LLM & agentic AI sections** | Layered stack diagrams, ReAct loops, multi-agent orchestration |
| **RL + XAI feedback systems** | Closed-loop Predict → Act → Observe → Explain → Update design |
| **Algorithm reference tables** | PPO, SAC, DQN, A3C, MCTS, SHAP, LIME, Grad-CAM, and more |
| **India 2036 special focus** | Olympic AI roadmap timeline and national platform architecture |
| **Responsive design** | Mobile, tablet, laptop, and desktop breakpoints |
| **Cross-browser support** | Chrome, Brave, Edge, Safari, Firefox, and others |
| **Accessibility touches** | ARIA labels, focus states, reduced-motion support |
| **Scroll animations** | Fade-in sections via Intersection Observer |
| **Mobile navigation** | Hamburger menu with toggle on small screens |
| **CC BY 4.0 footer** | Copyright and license attribution on every page |

---

## Project Structure

```
AI_article/
├── index.html          # Home page — overview, LLM, agentic AI, RL+XAI, shared substrate
├── sports.html         # Use Case I — Elite sports AI deep-dive
├── carbon.html         # Use Case II — Carbon dating & emissions AI deep-dive
├── css/
│   └── styles.css      # Global styles, layout, components, responsive rules
├── js/
│   └── main.js         # Navigation, scroll effects, fade-in animations
└── README.md           # This file
```

### File Responsibilities

| File | Role |
|------|------|
| `index.html` | Landing page, use-case portal, cross-domain architecture synthesis |
| `sports.html` | Sports-specific models, India 2036 roadmap, coaching RL agents |
| `carbon.html` | Radiocarbon dating, emissions GNN, satellite methane, climate RL |
| `css/styles.css` | Design tokens, typography, cards, tables, hero, nav, footer, media queries |
| `js/main.js` | Shared client-side interactions loaded on all pages |

---

## Pages & Content Map

### Home — `index.html`

| Section | ID / Anchor | Content |
|---------|-------------|---------|
| Hero | — | Site introduction, key statistics, CTA buttons to use cases |
| Use Cases | `#use-cases` | Two portal cards linking to `sports.html` and `carbon.html` |
| LLM Architecture | `#llm-architecture` | Foundation → Orchestration → Specialist Models → Output stack |
| Agentic AI | `#agentic-ai` | Perceive-Plan-Act-Reflect loop, agent examples, ReAct architecture |
| RL + XAI Feedback | `#rl-xai-feedback` | Closed-loop system, RL algorithm table, XAI method table |
| Shared Substrate | — | Cross-domain architecture comparison table |
| Footer | — | Navigation links, hashtags, CC BY 4.0 copyright |

### Sports AI — `sports.html`

| Section | Content |
|---------|---------|
| Core Technical Stack | 7-layer stack: data → features → inference → decision → RL+XAI → agents → broadcast |
| HTL-APF | Hybrid Transformer-LSTM performance forecasting pipeline and metrics |
| EPRN | Wavelet + parallel RNN injury prevention architecture |
| RL + XAI in Sports | Sports MDP, PPO/SAC/DQN/MCTS/A3C applications, coach dashboards |
| SportsGPT & Agentic Coaching | ViT + LLM coaching, multi-tool agent architecture |
| Model comparison table | HTL-APF, EPRN, SportsGPT, GNN, PPO Training Agent, etc. |
| India 2036 Olympics | Timeline (2026–2036), domain deployment, national AI platform |
| Implementation roadmap | 4-stage maturity model for sports practitioners |

### Carbon Science — `carbon.html`

| Section | Content |
|---------|---------|
| Radiocarbon Physics | Beta counting vs AMS comparison |
| Enoch Model | Multimodal AMS + handwriting style Bayesian fusion |
| DGL Framework | GNN + Temporal Transformer for industrial emissions |
| RL + XAI in Carbon | Emission control MDP, industrial RL, policy XAI |
| Agentic Climate Monitoring | Multi-agent satellite → detection → forecast → policy pipeline |
| Satellite & Computer Vision | U-Net methane plumes, Pangu-Weather, industrial RL |
| Model comparison table | Enoch, DGL, PPO Industrial RL, Climate Agent, etc. |
| Convergence | Green Olympics, carbon credits, athlete thermal adaptation |
| Implementation roadmap | 4-stage maturity model for climate practitioners |

---

## Technical Concepts Covered

### Deep Learning Architectures

- **Transformers** — Multi-head attention, positional encoding, temporal forecasting
- **LSTM / Hybrid models** — HTL-APF (Transformer + LSTM)
- **Graph Neural Networks (GNN)** — GraphSAGE, GAT, DGL framework
- **CNN / ViT** — Pose estimation, manuscript style analysis, methane segmentation
- **U-Net** — Encoder-decoder satellite plume detection
- **Wavelet + RNN** — EPRN multi-resolution motion analysis

### Large Language Models & Agentic AI

- **Foundation models** — GPT-4o, Claude, Gemini, Llama class decoders
- **RAG** — Retrieval-Augmented Generation for domain knowledge injection
- **Function calling** — Tool registry for specialist model invocation
- **ReAct pattern** — Reason + Act agent loops
- **Multi-agent orchestration** — LangGraph / AutoGen-style pipelines
- **Alignment** — RLHF, DPO, constitutional AI

### Reinforcement Learning

| Algorithm | Sports Use | Carbon Use |
|-----------|------------|------------|
| **PPO** | Training load prescription | Data centre / industrial control |
| **SAC** | In-game tactical adjustments | Process emission minimisation |
| **DQN / Double DQN** | Discrete drill selection | Policy lever selection |
| **A3C / A2C** | Multi-athlete load balancing | Multi-facility coordination |
| **MCTS + Policy Net** | Real-time match strategy | Net-zero pathway planning |
| **Contextual Bandits** | — | AMS lab scheduling |

### Explainable AI (XAI)

| Method | Purpose |
|--------|---------|
| **SHAP** | Global/local feature attribution |
| **LIME** | Instance-level interpretable proxies |
| **Integrated Gradients** | Input sensitivity maps |
| **Grad-CAM** | Spatial heatmaps on vision models |
| **Attention Maps** | Transformer/GNN weight visualisation |
| **Counterfactual XAI** | What-if intervention scenarios |
| **Causal DAGs** | Structural causal policy analysis |
| **GNNExplainer / GraphSHAP** | Edge attribution on emission graphs |

### Other Methods

- **Bayesian fusion** — Enoch AMS + palaeographic dating
- **Federated learning** — Privacy-preserving athlete / national data training
- **OxCal calibration** — IntCal20 radiocarbon probability distributions
- **SHAP on anti-doping** — Random Forest + LSTM-VAE anomaly explanations

---

## System Architecture (Feedback-Based Design)

Both use cases follow a **closed-loop feedback architecture**:

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌──────────────────┐
│   PREDICT   │ ──► │     ACT     │ ──► │   OBSERVE   │ ──► │ EXPLAIN & UPDATE │
│ HTL-APF     │     │ RL Policy   │     │ Sensor /    │     │ SHAP / LIME /    │
│ DGL-GNN     │     │ (PPO/SAC)   │     │ satellite   │     │ human feedback   │
│ EPRN        │     │             │     │ feedback    │     │ → policy update  │
└─────────────┘     └─────────────┘     └─────────────┘     └──────────────────┘
```

**Key principle:** Human-in-the-loop overrides (coach corrections, ministerial policy reviews) are incorporated via **reward shaping**:

```
R' = R + λ · human_preference_score
```

This mirrors RLHF alignment used in LLM systems and ensures the platform learns organisational constraints over time.

---

## Getting Started

### Prerequisites

- Any modern web browser (see [Browser & Device Compatibility](#browser--device-compatibility))
- No Node.js, npm, Python, or server installation required

### Local Usage

1. Clone or download the project folder.
2. Open `index.html` in your browser:

   **Option A — Direct open**
   ```
   Double-click index.html in File Explorer
   ```

   **Option B — Local HTTP server (recommended for best link behaviour)**
   ```powershell
   # Python 3
   cd AI_article
   python -m http.server 8080
   ```
   Then visit: `http://localhost:8080`

   ```powershell
   # Node.js (if installed)
   npx serve .
   ```

3. Navigate using the top nav bar or home page use-case cards.

### Recommended Reading Order

1. **Home** (`index.html`) — Understand shared architecture and feedback design
2. **Sports AI** (`sports.html`) — Performance intelligence and India 2036
3. **Carbon Science** (`carbon.html`) — Dating, emissions, and climate agents

---

## Navigation & User Flow

```
                    ┌─────────────────┐
                    │   index.html    │
                    │   (Home)        │
                    └────────┬────────┘
              ┌──────────────┼──────────────┐
              ▼                             ▼
     ┌─────────────────┐           ┌─────────────────┐
     │   sports.html   │◄─────────►│   carbon.html   │
     │   Sports AI     │  cross-   │  Carbon Science │
     └─────────────────┘   links   └─────────────────┘
```

- **Fixed top navigation** appears on all pages: Home | Sports AI | Carbon Science
- **Active page** is highlighted in the nav bar automatically via `main.js`
- **Breadcrumbs** on use-case pages: `Home / Sports AI` or `Home / Carbon Science`
- **Cross-links** at the bottom of each use-case page link to the other use case
- **Mobile:** Hamburger icon (☰) toggles the nav menu

---

## Frontend Functionality

All behaviour is handled by `js/main.js` (vanilla JavaScript, no frameworks).

| Function | Description |
|----------|-------------|
| **Nav scroll shadow** | Adds `.scrolled` class to navbar after 10px scroll |
| **Mobile menu toggle** | Opens/closes `.nav-links` on hamburger click; sets `aria-expanded` |
| **Auto-close menu** | Closes mobile menu when a nav link is clicked |
| **Fade-in on scroll** | `.fade-in` elements animate in via `IntersectionObserver` |
| **Active nav link** | Highlights link matching current page filename |
| **Smooth anchor scroll** | In-page `#anchor` links scroll with nav offset |
| **Reduced motion fallback** | If observer unavailable, all fade elements show immediately |

### CSS Animation Dependency

Fade-in sections require JavaScript. If JS is disabled, content remains visible (graceful degradation via observer fallback in script).

---

## Design System & Styling

`css/styles.css` uses CSS custom properties for theming:

| Token | Usage |
|-------|-------|
| `--blue-*` | Sports, primary links, badges |
| `--teal-*` | Carbon, success, quotes |
| `--amber-*` | Warnings, carbon hero gradient |
| `--purple-*` | LLM, agentic, GNN accents |
| `--coral-*` | Injury prevention, alerts |
| `--green-*` | RL feedback, convergence |
| `--surface`, `--border` | Backgrounds and dividers |

### Typography

- **Headings:** Playfair Display (Google Fonts)
- **Body:** Inter with system font fallbacks
- **Code / parameters:** JetBrains Mono

### Responsive Breakpoints

| Breakpoint | Target |
|------------|--------|
| `≤ 1024px` | Tablet landscape, small laptops |
| `≤ 768px` | Tablet portrait |
| `≤ 640px` | Mobile — hamburger nav, stacked layouts |
| `≤ 480px` | Small mobile — single-column metrics |

### Component Library (CSS Classes)

- `.hero`, `.hero--home`, `.hero--sports`, `.hero--carbon` — Page heroes
- `.card`, `.card-grid` — Content cards
- `.usecase-card` — Home page portal cards
- `.arch-block`, `.arch-node` — Architecture pipeline diagrams
- `.model-table` — Comparison tables
- `.param-list` — Hyperparameter key-value lists
- `.callout-*` — Highlighted info boxes (blue, teal, amber, purple, green)
- `.agentic-loop`, `.agentic-step` — 4-step process diagrams
- `.llm-stack`, `.llm-layer` — LLM stack visualisation
- `.metric-row`, `.metric-card` — Statistics display
- `.timeline`, `.tl-item` — India 2036 roadmap
- `.quote` — Block quotations
- `.code-block` — Pseudocode snippets
- `.footer-copyright` — License footer

---

## Browser & Device Compatibility

### Supported Browsers

| Browser | Support |
|---------|---------|
| Google Chrome | ✅ Full |
| Microsoft Edge | ✅ Full |
| Brave | ✅ Full |
| Mozilla Firefox | ✅ Full |
| Apple Safari | ✅ Full (with `-webkit-` prefixes) |
| Opera | ✅ Full |

### Device Support

| Device | Support |
|--------|---------|
| Desktop / PC | ✅ |
| Laptop | ✅ |
| Tablet (portrait & landscape) | ✅ |
| Mobile (iOS & Android) | ✅ |
| Notched devices (safe-area insets) | ✅ |

### Compatibility Features

- `viewport-fit=cover` for notched screens
- `-webkit-backdrop-filter` + `backdrop-filter` for frosted nav
- `-webkit-text-size-adjust` for mobile text scaling
- `prefers-reduced-motion` disables animations
- `overflow-x: hidden` prevents horizontal scroll
- Touch targets ≥ 44px on coarse pointer devices
- Print stylesheet hides nav for clean printing

---

## Deployment Options

This is a **static site** — deploy the entire `AI_article/` folder to any static host:

| Platform | Method |
|----------|--------|
| **GitHub Pages** | Push to repo → Settings → Pages → deploy from branch |
| **Netlify** | Drag-and-drop folder or connect Git repo |
| **Vercel** | Import project, set root to `AI_article` |
| **Cloudflare Pages** | Connect repo, no build command needed |

Ensure relative paths (`css/styles.css`, `js/main.js`) are preserved. No build step or environment variables required.

---

## Customization Guide

### Change site branding

Edit the nav brand in all three HTML files:

```html
<a href="index.html" class="nav-brand">
  <span class="nav-brand-icon">AI</span>
  Usecase By Prateek Dutta
</a>
```

### Add a new page

1. Copy `sports.html` as a template.
2. Update `<title>`, hero, and main content.
3. Add a nav link in all HTML files:
   ```html
   <li><a href="newpage.html">New Page</a></li>
   ```
4. `main.js` will auto-highlight the active link by filename.

### Modify colours

Edit CSS variables at the top of `css/styles.css`:

```css
:root {
  --blue-600: #185FA5;
  --teal-600: #0F6E56;
  /* ... */
}
```

### Disable scroll animations

Remove `fade-in` class from HTML sections, or delete the Intersection Observer block in `js/main.js`.

---

## References & Data Sources

Key publications and datasets cited across the site:

| Source | Topic |
|--------|-------|
| Informatica (2025) | HTL-APF athlete performance forecasting |
| Scientific Reports (2025) | EPRN motion recognition |
| arXiv:2508.02725 (2025) | NCAA Basketball Transformers |
| arXiv (2025) | SportsGPT |
| arXiv:2407.12013 (2024) | Enoch manuscript dating |
| arXiv:2507.02912 (2025) | DGL carbon emissions framework |
| Indian Olympic Association (Oct 2024) | India 2036 Letter of Intent |
| EDGAR v8.0 | Global emissions database |
| IntCal20 | Radiocarbon calibration curve |
| Google DeepMind (2023) | Data centre RL cooling |
| Microsoft Pangu-Weather (2023) | Atmospheric modelling |
| Sentinel-5P TROPOMI | Satellite methane data |

---

## License & Attribution

© 2026 [Prateek Dutta](https://prateekdutta2001.github.io/PrateekDutta.in/)

This work is licensed under a **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You are free to:

- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:

- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.

See [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/) for full license text.

---

## Quick Reference — Key Metrics

| Domain | Metric | Value |
|--------|--------|-------|
| Sports | HTL-APF F1-Score | 92.1% |
| Sports | HTL-APF AUC-ROC | 96.3% |
| Sports | Analytics market (2030) | $22.1B+ |
| Carbon | GNN error reduction (DGL) | 15%+ |
| Carbon | Global CO₂ emissions (2023) | 37.4 Gt |
| Carbon | Pangu-Weather speedup vs NWP | 1000× |
| Carbon | DeepMind cooling savings (RL) | 40% |
| Both | India Olympics bid year | 2036 |

---

*Built with HTML5, CSS3, and vanilla JavaScript. No frameworks. No build tools. Open anywhere.*
