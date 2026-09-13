# Living Biography Portfolio Design

## Purpose
Transform Chulan Marapana's personal site from a services-first developer portfolio into a living biography where projects, media, technical work, business history, creator work, and current experiments support a larger personal story.

## Positioning
Primary identity: **Chulan Marapana — Builder · Solutions Architect · Founder · Creator**.

Primary headline: **I build things.**

Supporting line: **Software. Businesses. Communities. Ideas.**

The site should communicate progression rather than a static résumé: Sri Lanka → Dubai/UAE → Newfoundland → creator/community builder → developer → founder → solutions architect → current experiments.

## Visual Direction
Editorial, cinematic, high-contrast, image-led and restrained. Dark first viewport, warm/light reading sections, strong typography, generous whitespace, asymmetric grids, timeline rails, occasional oversized statistics, real photography, real project artifacts, and no generic SaaS dashboard styling.

Use real public imagery where reliable and appropriate. For V1, use Chulan's public GitHub avatar as the primary portrait source and link to real project/media sources. Do not fabricate personal photographs.

## Homepage Information Architecture
1. Hero: portrait, "I build things.", identity line, compact navigation, CTAs to story and current work.
2. Story introduction: concise biography and origin path Sri Lanka → UAE → Newfoundland.
3. Proof strip: 100+ projects, 100% Job Success, 100K+ creator/community audience, Memorial University 2023.
4. Journey: chronological timeline covering business/operations, creator era, freelance growth, university, larger platforms, NewfieRadar, Jackedin, architecture/AI systems, and an unfinished "Next" milestone.
5. Featured work: NewfieRadar as the anchor project, then GameOnLoop, SenQuest, UnrealCarries, PlayerZone and selected business/client systems.
6. Evolution: business → community → software → architecture → AI/automation, showing the technical progression without a logo wall.
7. NewfieRadar case-study band: origin from speed-camera tools to fire information to community maps and broader local platform, with media proof.
8. Building now: NewfieRadar, Jackedin, Trading Hub, property intelligence and AI infrastructure.
9. Media and recognition: VOCM and CBC/Radio-Canada references, plus a compact credibility section.
10. Closing statement: "The story is still being written." with contact/social links.

## Navigation
Story · Journey · Work · Building Now · Media · Contact

For V1 these are in-page anchors so the site is complete and deployable immediately. Dedicated routes can follow without changing the core design.

## Content Rules
- Keep private/sensitive information out of the public site.
- Do not publish unverified historical claims.
- Use concise, first-person copy.
- Client/project work should support the biography instead of overwhelming it.
- NewfieRadar is the largest personal project story.
- Present current work as evolving, not finished.

## Responsive Behaviour
Desktop uses broad editorial grids and a fixed-width reading measure. Tablet collapses 3-column grids to 2 columns. Mobile becomes a single-column narrative with compact sticky navigation, horizontally scrollable stats where useful, and timeline dates stacked above entries.

## Interaction
Subtle entrance motion, active navigation states, smooth anchor scrolling, lightweight parallax/portrait drift only where motion preferences allow, hover emphasis on projects, and no dependency-heavy animation framework.

## Accessibility
Semantic landmarks, keyboard-visible focus states, sufficient contrast, alt text for portrait/artifacts, reduced-motion support, responsive type scaling, and no interaction that relies only on hover.

## V1 Technical Architecture
Static GitHub Pages site using semantic HTML, CSS custom properties, and minimal vanilla JavaScript. No build step or runtime dependency. Files: `index.html`, `styles.css`, `script.js`.
