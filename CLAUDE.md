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
- Brand colors/typography: _brand.yml (must be referenced in _quarto.yml
  — e.g. "brand: _brand.yml" or "format: html: theme: brand" — or the
  colors won't actually apply)
- Logo/assets: assets/map-logo.png

## Title
Keep the site title year-agnostic (no single year baked in) — the
programme runs annually. Year-specific details belong on that year's
edition page, not the title, homepage, or Programme overview.

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
mark as "coming soon" on the page itself (not in the nav label text).

## Source material
- Content from already-published, publicly distributed promotional
  materials (adverts, official programme flyers) can be reused/reworded
  freely — e.g. facilitator bios from official adverts.
- Participant/alumni personal data remains consent-gated regardless of
  source.

## Content rules
- Generic/structural copy (mission statements, section intros): draft is
  OK, I will edit.
- Anything naming real people, institutions, dates, or figures: use
  bracketed placeholders only — never invent specifics — unless sourced
  from already-published promotional material per the rule above.
  e.g. [Facilitator Name — Institution], [Cohort 2024 — X participants]
- No participant name, photo, or personal link goes live without
  recorded consent.
- Year-specific details (exact dates, deadlines, single-cohort figures)
  belong on that edition's page, not on year-agnostic pages (Programme,
  Home, title, _brand.yml meta.name).

## Workflow
- Use Plan Mode for structural changes (new sections, nav, layout).
- Small content edits (text tweaks, single-page fixes) can go straight
  to implementation.
- Commit to git after each approved step, locally only.

## Git
- Local commits after each approved step are fine.
- Pushing to an already-connected remote (origin) is fine once I've set
  it up.
- Never create a remote repo or run the first push — I handle GitHub
  repo creation and initial connection myself.