# BRAND

## Overview
Defines the visual identity of the product across all touchpoints and governs how brand decisions are made.

---

## Colors

### Primary
- Primary 01: #000000
- Primary 02: #FFFFFF

### Secondary
- Secondary 01: #F5F5F5
- Secondary 02: #E0E0E0

### Accent
- Accent: #4F46E5

### Usage Rules
- Primary colors dominate UI  
- Accent used for CTAs and highlights only  
- Avoid overusing gradients unless specified  

---

## Typography

### Font Families
- Headings: Inter / SF Pro  
- Body: Inter / Roboto  

### Scale
- H1: 48px  
- H2: 36px  
- H3: 28px  
- Body: 16px  
- Caption: 12px  

### Rules
- Max 2 font families  
- Maintain consistent line height (1.4–1.6)  
- Avoid excessive weights  

---

## Spacing System

- Base unit: 8px  
- Scale: 4, 8, 16, 24, 32, 48, 64  

---

## Grid

- Desktop: 12 columns  
- Tablet: 8 columns  
- Mobile: 4 columns  

---

## Imagery

- Style: Clean, high contrast, minimal clutter  
- Avoid stock-heavy visuals  
- Prefer product-focused or contextual imagery  

---

## Do / Don’t

### Do
- Keep layouts breathable  
- Use consistent spacing  

### Don’t
- Mix too many styles  
- Overuse shadows or gradients  

---

## Brand Decision Rules

When creating or modifying assets:

- If clarity conflicts with creativity → choose clarity  
- If consistency conflicts with variation → choose consistency  
- If visual style conflicts with usability → choose usability  
- If unsure → default to simplicity  

---

## Constraints

- Maximum 1 accent color per asset  
- No gradients unless explicitly defined  
- No new visual styles without system extension  
- No decorative elements without functional purpose  

---

## Layout Behavior

- Layout must prioritize readability over density  
- Spacing must follow the 8px system consistently  
- Internal spacing must always be smaller than external spacing  
- Visual hierarchy must be clear within 3 seconds  

---

## Hierarchy Rules

- Use size before color for emphasis  
- Use spacing before borders for separation  
- Use color only as a last resort for hierarchy  

---

## Consistency Rules

- Same layout logic must be reused across similar assets  
- Same spacing patterns must repeat across components  
- Same typography scale must be applied across all outputs  
- No one-off design decisions  

---

## Failure Conditions

An output is not brand-compliant if:

- Colors are used inconsistently  
- Typography scale is broken  
- Spacing is irregular  
- Layout lacks clear hierarchy  
- Visual style deviates from system  

---

## Token Reference

```yaml
colors:
  primary: ["#000000", "#FFFFFF"]
  secondary: ["#F5F5F5", "#E0E0E0"]
  accent: "#4F46E5"

spacing:
  base: 8
  scale: [4, 8, 16, 24, 32, 48, 64]

typography:
  h1: 48
  h2: 36
  h3: 28
  body: 16
  caption: 12
```