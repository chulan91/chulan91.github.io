# Living Biography Portfolio Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Replace the maintenance placeholder with a polished, responsive living-biography portfolio for Chulan Marapana.

**Architecture:** Static GitHub Pages implementation with semantic HTML for content structure, a dedicated CSS design system for the editorial visual language, and a small vanilla JS layer for navigation/reveal interactions. Real public identity imagery is used where reliable; project and media links point to real sources.

**Tech Stack:** HTML5, CSS3, vanilla JavaScript, GitHub Pages.

**Spec:** `docs/superpowers/specs/2026-09-13-living-biography-design.md`

## Global Constraints
- Biography-first rather than services-first.
- Primary headline is “I build things.”
- Supporting line is “Software. Businesses. Communities. Ideas.”
- Keep private/sensitive information out of the public site.
- No fabricated personal photography.
- NewfieRadar receives the largest personal project treatment.
- Responsive from mobile through desktop.
- Respect `prefers-reduced-motion`.

---

### Task 1: Build the narrative document

**Files:**
- Modify: `index.html`

**Interfaces:**
- Consumes: the approved biography/design spec.
- Produces: semantic section IDs `story`, `journey`, `work`, `now`, `media`, and `contact` for navigation and JS state.

- [ ] Replace the maintenance markup with the complete page structure.
- [ ] Add the hero, origin story, proof metrics, journey timeline, featured work, NewfieRadar case study, current-build section, media section, and closing contact section.
- [ ] Use Chulan’s public GitHub avatar as the V1 portrait and real external links for LinkedIn, GitHub, Twitch, portfolio project pages, NewfieRadar and VOCM.
- [ ] Verify headings are sequential and anchor IDs are unique.
- [ ] Commit the page structure.

### Task 2: Implement the design system and responsive layout

**Files:**
- Create: `styles.css`

**Interfaces:**
- Consumes: class names and section structure from `index.html`.
- Produces: shared tokens and responsive component styles.

- [ ] Define color, typography, spacing, border, radius and motion tokens.
- [ ] Implement dark cinematic hero and warm editorial body sections.
- [ ] Implement asymmetric story grid, proof rail, timeline, project compositions, feature band and footer.
- [ ] Add tablet and mobile breakpoints with single-column narrative flow.
- [ ] Add focus-visible and reduced-motion rules.
- [ ] Commit styling.

### Task 3: Add lightweight interaction

**Files:**
- Create: `script.js`

**Interfaces:**
- Consumes: section IDs and `.reveal` elements from `index.html`.
- Produces: mobile nav toggle, intersection-based reveal state and active section navigation.

- [ ] Implement accessible mobile navigation toggle.
- [ ] Add IntersectionObserver reveal classes while respecting reduced motion.
- [ ] Update active navigation link based on the visible section.
- [ ] Close mobile navigation after anchor selection.
- [ ] Commit interaction logic.

### Task 4: Source/content QA

**Files:**
- Modify as needed: `index.html`, `styles.css`, `script.js`

**Interfaces:**
- Consumes: the completed V1 site.
- Produces: a deployable branch suitable for review/merge.

- [ ] Confirm no private phone number, home address, immigration, health, financial or employer-confidential data is present.
- [ ] Confirm factual claims are limited to user-provided history, current public site/profile statements, GitHub history and verified media references.
- [ ] Confirm all external links use safe `rel` attributes when opened in new tabs.
- [ ] Confirm responsive HTML contains no horizontal-overflow-prone fixed widths.
- [ ] Open a pull request for review.
