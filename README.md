# 🌐 Website Design Analysis AI Package

> A comprehensive, production-grade AI prompt engineering framework and output scaffolding designed to reverse-engineer, analyze, and document any website's design system, UI/UX architecture, component library, and technical rebuild specifications.

---

## 📌 Overview

This package equips autonomous AI agents, design engineers, and developers with a structured methodology to analyze any live website URL. The AI performs an exhaustive multi-dimensional breakdown across visual design, typography, spacing, component hierarchies, user flows, animations, technical stack, accessibility, and SEO—delivering a modular recreation blueprint without infringing on proprietary code or copyrighted assets.

---

## 📁 Repository Structure

```bash
├── README.md                  # Package documentation & usage instructions
├── SYSTEM_PROMPT.md           # The core AI analysis instructions and strict rules
├── quick-start-prompt.md      # Ready-to-copy prompt for quick AI execution
├── output-structure.md        # File & folder hierarchy specification for the output
└── output-template/           # Scaffolding templates for the generated analysis
    ├── 00-executive-summary/  # High-level summary & roadmap
    ├── 01-research/           # Sitemap & research notes
    ├── 02-screenshots/        # Screen captures across viewports
    ├── 03-design-language/    # Brand moodboard & layout principles
    ├── 04-design-system/      # Typography, colors, spacing, tokens
    ├── 05-components/         # Buttons, cards, modals, form controls
    ├── 06-pages/              # Page-by-page architectural breakdown
    ├── 07-ux-interactions-motion/ # Motion system & user flows
    ├── 08-technical-architecture/ # Frontend stack & network audit
    ├── 09-accessibility-performance-seo/ # WCAG, CWV & SEO audits
    └── 10-rebuild-specification/ # Component props, tokens, & QA criteria
```

---

## 🚀 How to Use

### 1. Quick Start with an AI Agent (Claude, ChatGPT, Gemini, etc.)
1. Provide the AI with the contents of this repository (or attach [`SYSTEM_PROMPT.md`](./SYSTEM_PROMPT.md)).
2. Supply the target website URL.
3. Paste the following execution command:

```text
Read SYSTEM_PROMPT.md completely. Use it as your strict instruction file. 
Analyze this website URL: [INSERT TARGET URL HERE]
Produce the complete structured markdown output following the output-structure.md specifications.
```

### 2. Optional Context Notes
You can append optional parameters to tailor the analysis:
- **Priority Pages:** e.g., `/pricing`, `/dashboard`, `/checkout`
- **Preferred Tech Stack:** e.g., Next.js 15, Tailwind CSS, shadcn/ui, Framer Motion
- **Target Platform:** Mobile-first web app, responsive marketing site, B2B SaaS portal
- **Competitor References:** Benchmark against specific industry standards

---

## 📊 Generated Analysis Deliverables

When executed, the AI produces a complete audit suite containing:

| Section | Description |
|---|---|
| **00 - Executive Summary** | Core findings, design rating, and staged rebuild roadmap |
| **01 - Research** | Crawled sitemap, responsive breakpoints, edge cases, and scope |
| **02 - Visual Assets** | Desktop, tablet, mobile viewports & interaction states |
| **03 - Design Language** | Visual aesthetic, grid alignment, layout rhythm, and tone |
| **04 - Design System** | Color palettes (hex/hsl/css variables), typography scales, spacing units, and `design-tokens.json` |
| **05 - Component Inventory** | Atomic design elements (Buttons, Inputs, Modals, Cards, Navbars) with interactive states |
| **06 - Page Breakdowns** | Deep dives into structure, content blocks, and visual hierarchy per route |
| **07 - UX & Motion** | Easing curves, spring physics, hover effects, page transitions, and gestures |
| **08 - Technical Stack** | DOM tree patterns, CSS architecture, third-party libraries, and API endpoints |
| **09 - Audits** | WCAG 2.1 AA compliance, Core Web Vitals (LCP, CLS, INP), and SEO metadata |
| **10 - Rebuild Spec** | TypeScript component interfaces, token mappings, acceptance criteria, and QA checklists |

---

## ⚖️ Ethical & Legal Guidelines

- **Clean-Room Analysis:** This framework is intended to document design systems, architectural patterns, and UX best practices.
- **Respect Intellectual Property:** Do not extract or replicate proprietary source code, private APIs, registered trademarks, or copyrighted text/imagery.
- **Original Creation:** Use the generated specifications to build clean, original products engineered with equivalent design polish and structural fidelity.

---

## 📄 License

MIT License. Free to use for personal, educational, and commercial AI workflows.
