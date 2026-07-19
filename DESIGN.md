---
# AI

## Mission
Create implementation-ready, token-driven UI guidance for AI that is optimized for consistency, accessibility, and fast delivery across marketing site.

## Brand
- Product/brand: AI
- URL: https://rootly.com/
- Audience: buyers, teams, and decision-makers
- Product surface: marketing site

## Style Foundations
- Visual style: clean, functional, implementation-oriented
- Main font style: `font.family.primary=Ppmori`, `font.family.stack=Ppmori, Arial, sans-serif`, `font.size.base=14px`, `font.weight.base=200`, `font.lineHeight.base=20px`
- Typography scale: `font.size.xs=10.4px`, `font.size.sm=12px`, `font.size.md=14px`, `font.size.lg=16px`, `font.size.xl=18px`, `font.size.2xl=20px`, `font.size.3xl=32px`, `font.size.4xl=36px`
- Color palette: `color.text.primary=#100f12`, `color.border.muted=#ffffff`, `color.text.tertiary=#787685`, `color.text.inverse=#8d6fde`, `color.surface.base=#000000`, `color.surface.strong=#fbfaff`
- Spacing scale: `space.1=8.4px`, `space.2=10px`, `space.3=12px`, `space.4=12.8px`, `space.5=14px`, `space.6=16px`, `space.7=18px`, `space.8=20px`
- Radius/shadow/motion tokens: `radius.xs=5.6px`, `radius.sm=16px`, `radius.md=20px`, `radius.lg=24px`, `radius.xl=2560px` | `motion.duration.instant=200ms`, `motion.duration.fast=300ms`, `motion.duration.normal=400ms`

## Accessibility
- Target: WCAG 2.2 AA
- Keyboard-first interactions required.
- Focus-visible rules required.
- Contrast constraints required.

## Writing Tone
Concise, confident, implementation-focused.

## Rules: Do
- Use semantic tokens, not raw hex values, in component guidance.
- Every component must define states for default, hover, focus-visible, active, disabled, loading, and error.
- Component behavior should specify responsive and edge-case handling.
- Interactive components must document keyboard, pointer, and touch behavior.
- Accessibility acceptance criteria must be testable in implementation.

## Rules: Don't
- Do not allow low-contrast text or hidden focus indicators.
- Do not introduce one-off spacing or typography exceptions.
- Do not use ambiguous labels or non-descriptive actions.
- Do not ship component guidance without explicit state rules.

## Guideline Authoring Workflow
1. Restate design intent in one sentence.
2. Define foundations and semantic tokens.
3. Define component anatomy, variants, interactions, and state behavior.
4. Add accessibility acceptance criteria with pass/fail checks.
5. Add anti-patterns, migration notes, and edge-case handling.
6. End with a QA checklist.

## Required Output Structure
- Context and goals.
- Design tokens and foundations.
- Component-level rules (anatomy, variants, states, responsive behavior).
- Accessibility requirements and testable acceptance criteria.
- Content and tone standards with examples.
- Anti-patterns and prohibited implementations.
- QA checklist.

## Component Rule Expectations
- Include keyboard, pointer, and touch behavior.
- Include spacing and typography token requirements.
- Include long-content, overflow, and empty-state handling.
- Include known page component density: links (114), cards (98), buttons (20), inputs (7).


## Quality Gates
- Every non-negotiable rule must use "must".
- Every recommendation should use "should".
- Every accessibility rule must be testable in implementation.
- Teams should prefer system consistency over local visual exceptions.
