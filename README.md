# Eduvators-AI-Tools
A curated, accessible AI discovery directory for educators and students, featuring pedagogical guides, classroom prompts, and FERPA privacy audits.
# Eduvators AI Tool Guide

> Curated Artificial Intelligence Resources for Educators and Students

[![Eduvators Standard](https://img.shields.io/badge/Eduvators-Official%20Standard-A02383?style=flat-square)](https://www.eduvators.net)
[![Accessibility](https://img.shields.io/badge/Accessibility-WCAG%202.1%20AA-045577?style=flat-square)](#accessibility-standards)
[![Privacy](https://img.shields.io/badge/Privacy-FERPA%20%26%20COPPA%20Audited-3D0A30?style=flat-square)](#institutional-privacy-audit)
[![License](https://img.shields.io/badge/License-MIT-2D2D2D?style=flat-square)](LICENSE)

An accessible, Futurepedia-style discovery catalog and pedagogical scaffolding engine designed specifically for educational institutions, faculty, instructional designers, and students.

---

## Table of Contents

* [Overview](#overview)
* [Key Features](#key-features)
* [Curated Tools Index](#curated-tools-index)
* [Pedagogical Model & Framework](#pedagogical-model--framework)
* [Institutional Privacy Audit](#institutional-privacy-audit)
* [Brand Identity & Design System](#brand-identity--design-system)
* [Getting Started](#getting-started)
* [Tech Stack](#tech-stack)
* [Contact & Community](#contact--community)

---

## Overview

The **Eduvators AI Tool Guide** addresses a critical need in educational technology: bridging the gap between cutting-edge generative artificial intelligence platforms and the stringent privacy, accessibility, and pedagogical standards demanded by modern academic environments.

Every tool listed within the catalog is reviewed against:
1. **FERPA and COPPA Alignment:** Data isolation policies, training data usage, and student data protection agreements.
2. **Pedagogical Integration:** Universal Design for Learning (UDL) scaffolds, Bloom's Taxonomy alignment, and practical classroom activities.
3. **Responsible AI Practice:** Human-in-the-loop verification, attribution requirements, and academic integrity guidance.
4. **Digital Equity & Accessibility:** Screen reader compatibility, WCAG 2.1 AA color contrast compliance, and assistive workflow accommodations.

---

## Key Features

* **Futurepedia-Style Discovery Grid:** Multi-filter catalog sorting by category, pricing model (Free for EDU, Freemium, Institutional License), and student privacy ratings.
* **Prioritized Educational Stacks:** Core foundation models and high-utility creative suites surfaced sequentially at the top of the directory.
* **Interactive Classroom Guide Modal:**
  * Curricular learning objectives and assignment integration strategies.
  * Classroom-ready copyable prompts with single-click clipboard integration.
  * Responsible AI directives highlighting potential biases and hallucination risks.
  * Complete FERPA/COPPA audit status and account architecture notes.
* **Zero Dependency Single-File Architecture:** Pure HTML5, Tailwind CSS, and vanilla JavaScript for frictionless deployment to GitHub Pages, AWS S3, Cloudflare Pages, or LMS iframes (Canvas, Blackboard, Moodle).
* **Local Persistence:** Bookmarking system stored directly within browser `localStorage` without tracking cookies or remote user database requirements.

---

## Curated Tools Index

The directory prioritizes foundational systems and creative suites before moving into specialized niche pedagogies:

### Top Foundation Models & Multimodal Suites
1. **Gemini for Education (Gemini Edu)** : Enterprise Google Workspace integration with zero model training on student submissions.
2. **Gemini Advanced / Pro** : Long-context document reasoning and multimodal data analysis.
3. **Gemini Notebook (NotebookLM)** : Source-grounded synthesis, study guides, and citation generation.
4. **Microsoft Copilot** : Commercial data protection, syllabus authoring, and presentation scaffolding.
5. **ChatGPT Plus** : Custom GPTs, advanced reasoning, data analysis, and iterative writing canvas.
6. **Claude** : Anthropic Claude 3.5 Sonnet for scholarly prose composition, code analysis, and interactive visual artifacts.
7. **Midjourney** : Visual aesthetics, prompt engineering, digital media concepting, and speculative architecture.
8. **Suno** : Poetic meter, lyrical cadence, and musical composition across cross-disciplinary humanities.
9. **Runway** : Gen 3 Alpha video synthesis, cinematic storytelling, and multimedia journalism.
10. **Perplexity** : Live academic source citation, literature searching, and factual corroboration.
11. **ElevenLabs** : Speech synthesis, language pronunciation, and auditory reading accommodations.

### Specialized Pedagogical & Creative Applications
12. **Adobe Firefly** : Commercially safe visual design trained exclusively on licensed stock media.
13. **Canva Magic Studio** : Classroom infographic posters, student presentations, and collaborative sandboxes.
14. **Udio** : Vocal arrangement and music theory structural exploration.
15. **MagicSchool AI** : 60+ educator-focused tools for rubric generation, IEP adaptations, and lesson planning.
16. **Khanmigo** : Khan Academy Socratic tutor designed never to provide direct answers.
17. **Goblin.tools** : Neurodivergent assistive tools breaking complex assignments into low-stress steps.
18. **Diffit** : Instant Lexile reading passage leveling and vocabulary adaptation.
19. **Recraft** : Scalable vector graphic synthesis and user experience icon design.
20. **Scite** : Smart citation engine verifying whether research papers have been corroborated or contested.

---

## Institutional Privacy Audit

Tools are categorized under one of three primary privacy badges:

| Privacy Badge | Institutional Meaning |
| :--- | :--- |
| **FERPA Verified** | Platform offers signed Student Privacy Pledge / DPA terms; user input is isolated and never used to train public foundation weights. |
| **Campus Safe** | Enterprise SSO supported with commercial data protection; safe when configured via school tenant credentials. |
| **Student Direct** | Open consumer platform requiring direct login; intended for age 18+ or teacher-guided demonstration workflows. |

---

## Brand Identity & Design System

The project adheres to the official **Eduvators** visual identity system:

### Color Palette

| Name | Hex Code | Usage |
| :--- | :--- | :--- |
| **Eduvators Purple** | `#A02383` | Primary action buttons, active tags, key focus states, top highlights |
| **Deep Purple** | `#3D0A30` | Main headers, hero banners, modal titles, toast containers |
| **Eduvators Teal** | `#045577` | Structural borders, subheadings, badges, link hover states |
| **Light Teal** | `#E8F4F8` | Callout panels, search input containers, secondary pill buttons |
| **Light Purple** | `#F5E6F0` | Subtle backdrops, prompt code blocks, hover highlights |
| **Charcoal Body** | `#2D2D2D` | High-contrast WCAG 2.1 AA body text |
| **White** | `#FFFFFF` | Card surfaces and high-contrast UI elements |

### Typography & Writing Guidelines
* **Typeface:** Strict `Verdana` typography applied across all elements, inputs, and headings.
* **Punctuation Standard:** Strict avoidance of dash (`-`) symbols in descriptive body text, titles, prompts, and interface strings; replaced by colons (`:`), bullet points (`•`), parenthetical notation, or forward slashes (`/`).

---

## Getting Started

### Local Setup
Since the application uses a single self-contained structure, no build tools or package managers (`npm`, `yarn`, `pnpm`) are required.

1. Clone this repository:
   ```bash
   git clone https://github.com/your-org/eduvators-ai-tool-guide.git
   cd eduvators-ai-tool-guide
   ```

2. Open `index.html` in any modern web browser:
   ```bash
   # On macOS
   open index.html

   # On Linux
   xdg-open index.html

   # On Windows
   start index.html
   ```

### Deploying to GitHub Pages
1. Go to repository **Settings** > **Pages**.
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
3. Set the branch to `main` (or `master`) and folder to `/ (root)`.
4. Click **Save**. The guide will be live on your GitHub Pages URL within minutes.

---

## Tech Stack

* **Markup:** Semantic HTML5 with complete ARIA role labeling.
* **Styling:** Tailwind CSS via CDN with customized brand themes.
* **Iconography:** Phosphor Icons Web Library.
* **Scripting:** Pure Vanilla ES6+ JavaScript (zero external framework runtime).
* **Storage:** Native browser `window.localStorage`.

---

## Contact & Community

* **Official Website:** [www.eduvators.net](https://www.eduvators.net)
* **General Inquiries & Tool Submissions:** [contact@eduvators.net](mailto:contact@eduvators.net)
* **License:** Released under the [MIT License](LICENSE).

<div align="center">
  <sub>Built with care for educators and students worldwide • Strict WCAG 2.1 AA Accessible</sub>
</div>
