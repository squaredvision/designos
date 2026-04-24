---
name: DesignOS
version: 1.0
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

# DesignOS Specification

A machine-readable system that defines how marketing and design outputs are created, structured, and validated.

---

## 1. SYSTEM OVERVIEW

DesignOS combines:

- Design (layout, hierarchy)
- Brand (identity, visuals)
- Voice (tone, communication)
- Vocabulary (language rules)

Into a single system for **consistent, scalable output production**.

---

## 2. SYSTEM FLOW

```text
Input (Prompt)
  ↓
DesignOS System
  ↓
Structured Output
  ↓
Validation
  ↓
Final Output
```

---

## 3. DESIGN SYSTEM

### Principles
- High information density
- Low visual noise
- Fast scanning
- Clear hierarchy

---

### Color Rules
- Primary = key actions only
- Accent = highlights and CTAs
- Max 2 accent colors per screen
- No pure white on dark UI
- Minimum contrast ratio 4.5:1

---

### Typography Rules
- Max 3 sizes per screen
- Max 2 font families
- Line height: 1.4–1.6
- Avoid excessive weights

Hierarchy:
- Display → Hero
- Heading → Structure
- Body → Content
- Caption → Metadata

---

### Layout System
Grid:
- Desktop: 12 columns
- Tablet: 8 columns
- Mobile: 4 columns

Spacing:
- 8px base system
- Internal spacing < external spacing
- Consistent padding across components

---

### Components
- Reusable
- Predictable
- Stateless by default

---

### Interaction
- Motion: 150–300ms
- Subtle transitions only
- Immediate feedback required

---

### Accessibility
- WCAG AA (4.5:1)
- Minimum click target: 44px
- Keyboard navigation required

---

## 4. BRAND SYSTEM

### Rules
- Primary colors dominate
- Accent used sparingly
- Avoid heavy gradients

---

### Imagery
- Clean
- High contrast
- Minimal clutter
- Contextual (not stock-heavy)

---

## 5. VOICE SYSTEM

### Tone
- Clear
- Confident
- Human
- Direct

---

### Writing Rules
- Short sentences
- Active voice
- No unnecessary jargon

---

### Messaging Pillars
1. Simplicity
2. Clarity
3. Value
4. Speed

---

## 6. VOCABULARY SYSTEM

### Approved Terms
- UI
- AI-powered
- Workflow
- Component
- System

---

### Banned Terms
- Cutting-edge
- Revolutionary
- Next-gen
- Seamless

---

### Microcopy Rules
- Buttons: 1–2 words
- Errors: clear + actionable

---

## 7. OUTPUT SYSTEM (CORE)

### Output Generation Rules

All outputs must:

1. Follow a defined structure (based on type)
2. Apply layout and hierarchy rules (Design System)
3. Apply tone and clarity (Voice System)
4. Use approved terminology (Vocabulary System)
5. Align with brand identity (Brand System)

---

### Document Type Mapping

Deck:
- Cover
- Problem
- Solution
- Results
- CTA

Case Study:
- Problem
- Approach
- Solution
- Results

Report:
- Summary
- Insights
- Data
- Recommendations

Landing Page:
- Hero
- Problem
- Solution
- Features
- CTA

---

## 8. VALIDATION SYSTEM

Before publishing, outputs must pass:

- Structure completeness
- Tone consistency
- Vocabulary compliance
- Visual hierarchy clarity

If any rule fails:
→ Output must be revised

---

## 9. SCALABILITY RULES

### Adding Components
- Must use system tokens
- Must include all states
- Must be reusable across ≥2 contexts

---

### Extending System
- Add tokens, not overrides
- Avoid hardcoded values

---

## 10. SYSTEM PRINCIPLES

- If everything stands out → nothing stands out
- If structure is inconsistent → output fails
- If language varies → trust is reduced

---

## FINAL PRINCIPLE

If content is not structured, it cannot scale.

DesignOS introduces constraints so AI can produce consistent, high-quality outputs across any format.