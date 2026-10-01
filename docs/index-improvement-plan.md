# index.html Improvement Plan (Bugs + Content, Minimal)

Scope: fix invalid HTML/CSS and correct existing copy using
`JM_Resume_[EN]_11_sep_26.md` as the source of truth.
No redesign, no new sections, no experience timeline.

## Phase 1 — HTML validity

- [x] Add `<html lang="en">` and the missing opening `<body>` tag
- [x] Fix both `<class class="sections">` → `<div class="sections">` (index.html:144, 169)
- [x] Add `<meta charset="utf-8">`
- [x] Use local `Avatar.png` instead of the `raw.githubusercontent.com` URL
- [x] Replace deprecated `<center>` in the footer with CSS

## Phase 2 — CSS fixes (keep current style)

- [x] Fix invalid `p { font-size: 17; }` → `17px`
- [x] Replace layout hacks: `.cards { margin-top: 280px }`, `footer { margin-top: 2050px }`, `.sections { height: 50px }`
- [x] Remove unused timeline CSS (no markup uses it)
- [x] Add `aria-label`/`title` to icon-only links

## Phase 3 — Metadata & accessibility

- [x] Add meta description, favicon, Open Graph and Twitter tags
- [x] Add semantic `header`/`main` wrappers; review alt text
- [x] Add visible keyboard focus styles

## Phase 4 — Content corrections (existing sections only)

- [x] `10+ years` → `15+ years` in IT and cybersecurity
- [x] Reword "99 projects" / "98% satisfaction" cards without numbers (user decision)
- [x] Hero role label → "Cybersecurity Engineer & Consultant"
- [x] Add AWS Community Builder and bilingual (EN/ES) proof point
- [x] Sharpen existing skill cards: SAST/SCA/DAST and triage for AppSec; AWS & GCP architecture for Cloud
- Skipped: reconcile certifications — no changes to certifications (user decision)

## Validation

- [ ] HTML validates (no errors on validator.w3.org)
- [ ] Test at 425 / 768 / 1024 / 1440px widths
- [ ] Every metric, certification name, date and external link verified against the resume
