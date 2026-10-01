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
- [x] Hero role label: reverted to `Cybersecurity Consultant | Web Security | Engineering & Management` (user decision)
- [x] Add AWS Community Builder proof point (bilingual line removed per user decision)
- [x] Sharpen existing skill cards: SAST/SCA/DAST and triage for AppSec; AWS & GCP architecture for Cloud
- Skipped: reconcile certifications — no changes to certifications (user decision)

## Phase 5 — Communities (open)

- [ ] Add the resume's communities to the page: `OWASP, AWS Community Builder, Google Dev Groups, BSides, Python` (resume `Community Service` → `Communities`, Present)
  - Hero already shows `AWS Community Builder` only; the other four communities are missing from `index.html`
  - Place them in the existing profiles/community area (or add a compact `Communities` line under the hero) — no new section redesign
  - Optional: add the rest of the resume's `Community Service` table (US Embassy "Continuing Promise" translator 2010-2011; Osorno, Chile volunteer 2004-2006) only if it fits the professional narrative

## Phase 6 — Consistency with GitHub profile README (open)

- [ ] Check `index.html` (and `resume.md`) against the profile README at https://github.com/sh4z3r (source: `sh4z3r/sh4z3r/README.md`)
  - Years of experience: README says `17+ years`, page says `+ 15 years` — pick one source of truth
  - Tagline: README uses `Cybersecurity · Cloud · DevSecOps & AppSec · Practical AI`; hero uses `Cybersecurity Consultant | Web Security | Engineering & Management`
  - Spelling of the handle: README `Sh4z3r` vs page `* Shazer *` / `sh4z3r`
  - Links: README exposes gitbook, X, LinkedIn only; page also has Telegram, TryHackMe, Hack The Box — confirm none are missing or conflicting
  - README mentions a second account (`jorgeiteng`) — decide whether the page should reference it
  - Focus areas: README stresses practical AI / automation; confirm the page matches

## Validation

- [x] HTML validates (no errors on validator.w3.org) — 0 messages; CSS passes csstree-validator (W3C CSS service was down)
- [x] Test at 425 / 768 / 1024 / 1440px widths (headless Chromium screenshots, all clean)
- [x] Every metric, certification name, date and external link verified against the resume
  - Metrics/claims: all match resume (15+ years, AWS Community Builder, AppSec/cloud wording)
  - Links: 10/11 return 200; tryhackme.com returns 429 (bot rate-limit from this network, not a dead link)
  - Cert discrepancies vs resume (not changed per user decision): HTML has CSFPC, NSE4, Tenable TCME/PSI-IO/SC, Radware which resume doesn't list; resume has CEH and IDSS which HTML doesn't
