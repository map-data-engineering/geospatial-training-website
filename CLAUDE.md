# MAP September to Remember 2026 — Training Hub Site

## Purpose
Showcase the MAP geospatial modelling training programme: past cohorts,
facilitators, and the current Call for Applications. Built standalone but
structured so it can later be merged into the main MAP website without
a rebuild.

## Design constraint
Standalone-but-integrable: keep navigation, folder structure, and styling
modular (no hardcoded assumptions this is the top-level site) so it can
be folded into the main MAP site later with minimal rework.

## Tech stack
- Quarto, hosted on GitHub Pages
- Brand colors: [ #383838 , #ecbc40, #383838, #9d9c97 ]
- Logo/assets: assets/map-logo.svg (or .png)

## Sections — v1 (build now)
- Programme overview & objectives
- Previous workshop editions (2024, 2025, 2026 onwards)
- Facilitators (profiles, institutions, research interests, GitHub/LinkedIn)
- Current Call for Applications (link to existing application portal) + FAQs

## Sections — deferred (blocked on participant consent)
- Alumni directory (participants, institutions, photos, LinkedIn, GitHub, publications)
- Publications & projects arising from training
- Gallery & testimonials

Do NOT build placeholder content for these — reserve nav slots only,
mark as "coming soon."

## Content rules
- Generic/structural copy (mission statements, section intros): draft is
  OK, I will edit.
- Anything naming real people, institutions, dates, or figures: use
  bracketed placeholders only — never invent specifics.
  e.g. [Facilitator Name — Institution], [Cohort 2024 — X participants]
- No participant name, photo, or personal link goes live without
  recorded consent.

## Workflow
- Use Plan Mode for structural changes (new sections, nav, layout).
- Small content edits (text tweaks, single-page fixes) can go straight
  to implementation.
- Commit to git after each approved step.

## Git
- Local commits after each approved step are fine.
- Never create or push to a remote — I manage GitHub repo creation 
  and the first push myself.
