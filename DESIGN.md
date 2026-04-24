---
name: DevFocus Dark
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

typography:
  fontFamily: Inter
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

# DESIGN SYSTEM

## Overview
A focused, minimal dark interface built for developer productivity.

Priorities:
- High information density
- Low visual noise
- Fast scanning
- Clear hierarchy

---

## Foundations

### Color Usage
- **Primary** - reserved for key actions only (CTA, active states)
- **Secondary** - supporting UI and less critical actions
- **Surface** - main background
- **Surface Variant** - cards, containers
- **Border** - subtle separation, never dominant
- **On Surface** - main text
- **Muted Text** - secondary info, labels

### Rules
- Avoid using more than 2 accent colors per screen
- Never use pure white (#FFFFFF) on dark surfaces
- Maintain minimum contrast ratio of 4.5:1

---

## Typography

### Hierarchy
- Display - hero sections only
- Headings - structure content
- Body - primary reading text
- Caption - metadata, hints

### Rules
- Max 3 sizes per screen
- Line height: 1.4–1.6
- Avoid mixing weights excessively

---

## Layout & Spacing

### Grid
- Desktop: 12 columns
- Tablet: 8 columns
- Mobile: 4 columns

### Spacing Rules
- Use 8px base system
- Internal spacing < external spacing
- Maintain consistent padding across similar components

---

## Components

### Principles
- Reusable
- Predictable
- Stateless by default, extended with states

---

### Buttons
- Radius: 8px
- Height: 40–48px

**Variants**
- Primary (filled)
- Secondary (outline)
- Ghost (no background)

**States**
- Default
- Hover (slightly brighter)
- Active (slightly darker)
- Disabled (reduced opacity)

---

### Inputs
- Border: 1px solid border color
- Background: surface-variant
- Text: on-surface

**States**
- Default
- Focus (primary border)
- Error (error color)
- Disabled

---

### Cards
- No elevation
- Use background contrast instead
- Optional border for separation

---

### Modals
- Centered
- Dimmed background (overlay)
- Clear primary action

---

## Interaction

### Motion
- Use subtle transitions only
- Duration: 150–300ms
- Avoid decorative animations

### Feedback
- Immediate response on interaction
- Always show hover/focus states

---

## Accessibility

- Minimum contrast: WCAG AA (4.5:1)
- Click targets: minimum 44px height
- Keyboard navigation required
- Visible focus states mandatory

---

## Design Logic (Important)

### Hierarchy Order
1. Size
2. Contrast
3. Position
4. Color

### Decision Rules
- If everything is highlighted → nothing stands out
- If spacing is inconsistent → layout feels broken
- If colors compete → hierarchy is lost

---

## Do / Don’t

### Do
- Use primary color intentionally
- Keep layouts tight but readable
- Reuse components consistently

### Don’t
- Mix border styles randomly
- Overuse color for hierarchy
- Create one-off components

---

## File Structure (Figma / Code)

### Figma
- Foundations
- Tokens
- Components
- Patterns
- Screens

### Naming
- Button / Primary / Default
- Input / Error / Focus
- Card / Default / Compact

---

## System Scalability

### Adding New Components
- Must follow token system
- Must include all states
- Must be reusable across ≥2 use cases

### Extending Theme
- Add new tokens, not overrides
- Avoid hardcoded values

---

## Summary

This system prioritizes:
- Speed
- Clarity
- Consistency

Every design decision should reduce friction, not add decoration.