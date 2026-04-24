---
name: DevFocus Dark
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
Defines how layout, hierarchy, and components are structured and applied across all outputs.

---

## 1. DESIGN PRINCIPLES

- High information density  
- Low visual noise  
- Fast scanning  
- Clear hierarchy  

---

## 2. FOUNDATIONS

### Color Usage

- Primary → key actions only  
- Secondary → supporting UI  
- Surface → base layout  
- Surface Variant → containers  
- Border → subtle separation  
- On Surface → primary text  
- Muted → secondary text  

### Rules
- Max 2 accent colors per screen  
- No pure white (#FFFFFF) on dark surfaces  
- Minimum contrast ratio: 4.5:1  

---

## 3. TYPOGRAPHY

### Hierarchy
- Display → hero sections  
- Headings → structure  
- Body → reading content  
- Caption → metadata  

### Rules
- Max 3 sizes per screen  
- Line height: 1.4–1.6  
- Avoid excessive weights  

---

## 4. LAYOUT & SPACING

### Grid
- Desktop: 12 columns  
- Tablet: 8 columns  
- Mobile: 4 columns  

### Spacing Rules
- Use 8px base system  
- Internal spacing < external spacing  
- Consistent padding across components  

---

## 5. COMPONENT SYSTEM

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
- Clear primary action  

---

## 6. INTERACTION

### Motion
- 150–300ms  
- Subtle transitions only  
- No decorative animation  

### Feedback
- Immediate response  
- Always show hover/focus states  

---

## 7. ACCESSIBILITY

- WCAG AA (4.5:1)  
- Min target: 44px  
- Keyboard navigation required  
- Visible focus states mandatory  

---

## 8. DESIGN LOGIC

### Hierarchy Order
1. Size  
2. Contrast  
3. Position  
4. Color  

### Rules
- If everything stands out → nothing stands out  
- Inconsistent spacing breaks layout  
- Competing colors kill hierarchy  

---

## 9. OUTPUT APPLICATION (NEW)

Design rules must be applied differently based on output type:

### Deck
- High contrast  
- Minimal text  
- Strong hierarchy  

### Case Study
- Structured sections  
- Balanced spacing  
- Clear reading flow  

### Report
- Dense information  
- Consistent typography  
- Reduced visual noise  

### Landing Page
- Strong visual hierarchy  
- Clear CTA placement  
- Scannable sections  

---

## 10. VALIDATION RULES (CRITICAL)

Before publishing, design must pass:

- Layout hierarchy is clear  
- Spacing follows system scale  
- Typography is consistent  
- Color usage follows rules  
- Components follow defined states  

If any rule fails:
→ design must be revised  

---

## 11. SYSTEM SCALABILITY

### Adding Components
- Must use token system  
- Must include all states  
- Must be reusable across ≥2 use cases  

### Extending Theme
- Add tokens, not overrides  
- Avoid hardcoded values  

---

## 12. FAILURE CONDITIONS

A design fails if:

- Layout lacks hierarchy  
- Spacing is inconsistent  
- Typography scale is broken  
- Colors are misused  
- Components behave inconsistently  

---

## FINAL PRINCIPLE

Design is not decoration.

Design is structure.

If structure is inconsistent, the output fails.