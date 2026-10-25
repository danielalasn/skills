---
name: brand-design-systems
description: >-
  Apply authentic design systems and UI guidelines from 84 industry-leading brands (Stripe, Linear, Vercel, Apple, Claude, Cursor, Raycast, Supabase, Figma, Superhuman, PostHog, Airbnb, etc.). Use whenever asked to design, style, or recreate an interface, dashboard, or component following the visual identity, tokens, and aesthetic of a specific brand or company.
---

# Brand Design Systems (Awesome DESIGN.md)

This skill provides access to 84 curated, production-level `DESIGN.md` specifications extracted from industry-leading tech platforms, consumer products, and developer tools.

Each specification defines precise visual tokens: color palettes, typography scales, line-heights, letter-spacing, component states, card styles, and layout principles.

## Available Brands & Systems

The catalog is stored locally inside this skill in `design-md/<brand>/DESIGN.md`:

| Category | Brands |
| :--- | :--- |
| **Developer Tools & Cloud** | `vercel`, `linear.app`, `supabase`, `cursor`, `warp`, `raycast`, `expo`, `posthog`, `sentry`, `resend`, `mintlify`, `hashicorp`, `mongodb`, `clickhouse` |
| **AI & LLM Platforms** | `claude`, `cohere`, `elevenlabs`, `mistral.ai`, `ollama`, `opencode.ai`, `replicate`, `runwayml`, `together.ai`, `voltagent`, `x.ai`, `minimax` |
| **Fintech & Enterprise** | `stripe`, `mercury`, `revolut`, `wise`, `coinbase`, `binance`, `kraken`, `mastercard`, `nerdwallet` |
| **Productivity & Design** | `notion`, `figma`, `framer`, `webflow`, `miro`, `airtable`, `cal`, `superhuman`, `slack`, `clay`, `intercom` |
| **Consumer & Tech Giants** | `apple`, `airbnb`, `spotify`, `meta`, `uber`, `pinterest`, `playstation`, `nike`, `starbucks`, `tesla`, `spacex`, `dji`, `oura` |
| **Automotive & Luxury** | `bmw`, `bmw-m`, `ferrari`, `lamborghini`, `bugatti`, `renault` |

## How to Apply a Brand's Design System

1. **Locate the Brand's Specification:**
   Check the folder within this skill: `design-md/<brand-name>/DESIGN.md`.
   *(Example: `design-md/stripe/DESIGN.md` or `design-md/linear.app/DESIGN.md`)*

2. **Read the Design Tokens:**
   Read the `DESIGN.md` file using `view_file` to extract:
   - Primary, background, canvas, and accent color hex codes.
   - Exact typography tokens (`fontFamily`, `fontSize`, `fontWeight`, `letterSpacing`, `lineHeight`).
   - Border radius, shadows, and elevation hierarchies.
   - Component behaviors (buttons, inputs, cards, navigation).

3. **Incorporate into Target Projects:**
   - **For web projects (CSS/Tailwind/Next.js):** Map the tokens from `DESIGN.md` into CSS custom properties (`:root { ... }`) or `tailwind.config.ts`.
   - **Persistent Agent Alignment:** When starting a new app or project with a designated brand style, copy the chosen `DESIGN.md` directly into the root of that project so any agent reading `DESIGN.md` maintains strict visual cohesion.
