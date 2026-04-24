---
name: DesignOS
theme: dark

colors:
  primary: "#2665fd"
  secondary: "#475569"
  surface: "#0b1326"
  surface-variant: "#111a33"
  border: "#1f2a44"
  on-surface: "#dae2fd"
  on-surface-muted: "#94a3b8"
  error: "#ffb4ab"
  success: "#4ade80"
  warning: "#facc15"

brandColors:
  primary:
    - "#000000"
    - "#FFFFFF"
  secondary:
    - "#F5F5F5"
    - "#E0E0E0"
  accent: "#4F46E5"

typography:
  fontFamily: Inter
  secondaryFont: Roboto
  scale:
    display-lg: 48px
    display-md: 36px
    heading-lg: 28px
    heading-md: 22px
    body-lg: 16px
    body-md: 14px
    caption: 12px

fontWeights:
  regular: 400
  medium: 500
  semibold: 600

spacing:
  base: 8
  scale: [4, 8, 16, 24, 32, 48, 64]

radius:
  sm: 4px
  md: 8px
  lg: 12px

motion:
  fast: 150ms
  normal: 200ms
  slow: 300ms
  easing: ease-in-out
---

# DESIGN OS

## Overview
A unified system that combines design, brand, voice, and language into one scalable framework.

Built for:
- Speed
- Clarity
- Consistency
- Scalability

---

# 1. DESIGN SYSTEM

## Principles
- High information density
- Low visual noise
- Fast scanning
- Clear hierarchy

---

## Color Usage

### Rules
- Primary = key actions only
- Accent = highlights and CTAs
- Max 2 accent colors per screen
- No pure white on dark UI
- Minimum contrast ratio 4.5:1

---

## Typography

### Rules
- Max 3 sizes per screen
- Max 2 font families
- Line height: 1.4–1.6
- Avoid excessive weights

### Hierarchy
- Display → Hero
- Heading → Structure
- Body → Content
- Caption → Metadata

---

## Layout & Spacing

### Grid
- Desktop: 12 columns
- Tablet: 8 columns
- Mobile: 4 columns

### Spacing Rules
- 8px base system
- Internal spacing < external spacing
- Consistency across components

---

## Components

### Principles
- Reusable
- Predictable
- Stateless by default

---

### Buttons
- Height: 40–48px
- Radius: 8px

Variants:
- Primary
- Secondary
- Ghost

States:
- Default
- Hover
- Active
- Disabled

---

### Inputs
- Border: 1px
- Background: surface-variant

States:
- Default
- Focus
- Error
- Disabled

---

### Cards
- No elevation
- Use contrast instead
- Optional borders

---

### Modals
- Centered
- Dimmed overlay
- Clear CTA

---

## Interaction

### Motion
- 150–300ms only
- Subtle transitions
- No decorative animation

### Feedback
- Immediate response
- Always show hover/focus

---

## Accessibility
- WCAG AA (4.5:1)
- Min target: 44px
- Keyboard navigation required
- Visible focus states mandatory

---

## Design Logic

### Hierarchy Order
1. Size
2. Contrast
3. Position
4. Color

### Rules
- If everything stands out → nothing does
- Inconsistent spacing breaks layout
- Competing colors kill hierarchy

---

## Do / Don’t

### Do
- Use color intentionally
- Keep layouts tight
- Reuse components

### Don’t
- Overuse color
- Mix styles randomly
- Create one-offs

---

# 2. BRAND SYSTEM

## Visual Identity

### Rules
- Primary colors dominate UI
- Accent used sparingly
- Avoid heavy gradients

---

## Imagery
- Clean
- High contrast
- Minimal clutter
- Avoid stock-heavy visuals

---

## Brand Do / Don’t

### Do
- Keep layouts breathable
- Maintain spacing consistency

### Don’t
- Mix styles
- Overuse shadows/gradients

---

# 3. VOICE SYSTEM

## Tone
- Clear
- Confident
- Human
- Direct

---

## Writing Style
- Short sentences
- Active voice only
- No unnecessary jargon

---

## Audience Modes

### B2B
- Structured
- Data-driven
- Professional

### B2C
- Conversational
- Relatable
- Benefit-focused

---

## Messaging Pillars
1. Simplicity
2. Clarity
3. Value
4. Speed

---

## Writing Standard

Weak:
"We aim to leverage innovative solutions..."

Strong:
"We help you build faster with AI."

---

## Voice Do / Don’t

### Do
- Be specific
- Use examples

### Don’t
- Over-explain
- Use filler words

---

# 4. VOCABULARY SYSTEM

## Approved Terms
- UI
- AI-powered
- Workflow
- Component
- System

---

## Banned Terms
- Cutting-edge
- Revolutionary
- Next-gen
- Seamless

---

## Naming Conventions

### Components
- Button / Primary Button
- Card / Product Card

### Files
- kebab-case
  - design-system.md
  - button-component.md

### Variables
- camelCase
  - primaryColor
  - spacingLarge

---

## Consistency Rules
- Same term = same meaning
- No synonyms for core features

---

## Microcopy

### Buttons
- 1–2 words
  - Get Started
  - Save

### Errors
- Clear + actionable
  - Email is invalid

---

# 5. SYSTEM STRUCTURE

## Figma Structure
- Foundations
- Tokens
- Components
- Patterns
- Screens

---

## Scalability Rules

### New Components
- Must use tokens
- Must include all states
- Must be reusable (≥2 use cases)

### Extending System
- Add tokens only
- Avoid hardcoded values

---

# FINAL PRINCIPLE

Every decision must:
- Reduce friction
- Improve clarity
- Increase speed

No decoration without purpose.