# 🚀 AI Agent Skills Collection

Curated collection of high-impact skills for AI coding agents (**Antigravity**, **Claude Code**, **Cursor**, **Codex**, and other agentic environments).

Designed to enforce visual excellence, eliminate generic AI-generated interfaces ("AI slop"), adhere to authentic brand design systems, audit accessibility, and automate browser testing.

---

## 📦 Quick Installation

You can install all or individual skills from this repository using the [Skills CLI](https://skills.sh):

### Install into Current Project
```bash
# Install all skills interactively or at once
npx skills add danielalasn/skills

# Install a specific skill
npx skills add danielalasn/skills --skill design-taste-frontend
npx skills add danielalasn/skills --skill image-to-code
npx skills add danielalasn/skills --skill brand-design-systems
npx skills add danielalasn/skills --skill web-design-guidelines
npx skills add danielalasn/skills --skill playwright-cli
```

### Install Globally (Available across all your projects)
```bash
npx skills add danielalasn/skills -g -y
```

---

## 🛠 Included Skills

| Skill | Description | Original Source |
| :--- | :--- | :--- |
| **`design-taste-frontend`** | Anti-slop frontend art direction distilled from 247 curated Awwwards & One Page Love sites. Enforces strict typography, varied layouts, harmonious palettes, and browser validation. | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) |
| **`image-to-code`** | Elite image-first website workflow. Generates reference design images first, performs deep visual analysis, and then implements faithful frontend code without card clutter. | [Leonxlnx/imagegen-skills](https://github.com/Leonxlnx/imagegen-skills) |
| **`brand-design-systems`** | 84 authentic, production-grade `DESIGN.md` specifications extracted from industry leaders (Stripe, Linear, Vercel, Apple, Claude, Cursor, Raycast, Supabase, Figma, etc.). | [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) |
| **`web-design-guidelines`** | Review and audit UI code against Vercel's Web Interface Guidelines for UX, accessibility, focus states, and best practices. | [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) |
| **`playwright-cli`** | Automated browser interaction, CLI-based navigation, element clicking/typing, snapshots, screenshots, and end-to-end testing with Playwright. | [microsoft/playwright-cli](https://github.com/microsoft/playwright-cli) |

---

## 🎯 Usage Examples

### 1. Anti-Slop Frontend Design
Ask your AI agent:
> *"Design a landing page for a developer analytics platform using design-taste-frontend. Avoid generic card grids and centered dark-hero defaults."*

### 2. Image-First Workflow
Ask your AI agent:
> *"Generate visual design mockups for our SaaS pricing and feature sections first, analyze the composition, and then build the React components to match."*

### 3. Brand Design System Alignment
Ask your AI agent:
> *"Build our dashboard UI following the Stripe (or Linear / Vercel / Raycast) design system tokens and typography."*

### 4. Accessibility & UX Audit
Ask your AI agent:
> *"Audit this component against web-design-guidelines and check contrast, aria attributes, and keyboard navigation."*

### 5. Automated Browser Testing
Ask your AI agent:
> *"Use playwright-cli to open the local dev server, navigate to the signup page, fill the form, and verify that the success toast appears."*

---

## 📁 Repository Structure

```text
skills/
├── skills/
│   ├── brand-design-systems/     # 84 brand DESIGN.md files + SKILL.md
│   ├── design-taste-frontend/    # Anti-slop frontend art direction
│   ├── image-to-code/            # Image-first design-to-code pipeline
│   ├── playwright-cli/           # Microsoft Playwright browser automation
│   └── web-design-guidelines/    # Vercel UX & accessibility guidelines
├── .agents/                      # Workspace customizations for Antigravity
│   └── skills/                   # Local agent skill links
├── skills-lock.json              # Skills CLI lockfile
└── README.md                     # Documentation
```

---

## 📄 License
Individual skills are distributed under their respective open-source licenses (MIT / Apache-2.0).
