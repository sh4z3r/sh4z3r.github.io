# index.html Improvement Plan (Bugs + Content, Minimal)

Scope: fix invalid HTML/CSS and correct existing copy using
`JM_Resume_[EN]_11_sep_26.md` as the source of truth.
No redesign, no new sections, no experience timeline.

## Phase 1 — HTML validity

- [ ] Add `<html lang="en">` and the missing opening `<body>` tag
- [ ] Fix both `<class class="sections">` → `<div class="sections">` (index.html:144, 169)
- [ ] Add `<meta charset="utf-8">`
- [ ] Use local `Avatar.png` instead of the `raw.githubusercontent.com` URL
- [ ] Replace deprecated `<center>` in the footer with CSS

## Phase 2 — CSS fixes (keep current style)

- [ ] Fix invalid `p { font-size: 17; }` → `17px`
- [ ] Replace layout hacks: `.cards { margin-top: 280px }`, `footer { margin-top: 2050px }`, `.sections { height: 50px }`
- [ ] Remove unused timeline CSS (no markup uses it)
- [ ] Add `aria-label`/`title` to icon-only links

## Phase 3 — Metadata & accessibility

- [ ] Add meta description, favicon, Open Graph and Twitter tags
- [ ] Add semantic `header`/`main` wrappers; review alt text
- [ ] Add visible keyboard focus styles

## Phase 4 — Content corrections (existing sections only)

- [ ] `10+ years` → `15+ years` in IT and cybersecurity
- [ ] Remove unsupported "99 projects" and "98% satisfaction" cards
- [ ] Hero role label → "Cybersecurity Engineer & Consultant"
- [ ] Add AWS Community Builder and bilingual (EN/ES) proof point
- [ ] Sharpen existing skill cards: SAST/SCA/DAST and triage for AppSec; AWS & GCP architecture for Cloud
- [ ] Reconcile certifications against the resume (add CEH and IDSS; confirm whether Tenable, Imperva and Radware entries are certifications or product experience)

## Validation

- [ ] HTML validates (no errors on validator.w3.org)
- [ ] Test at 425 / 768 / 1024 / 1440px widths
- [ ] Every metric, certification name, date and external link verified against the resume
