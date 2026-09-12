# HTML Content Improvement Plan

## Purpose

Improve the content of `index.html` by using the stronger, more specific evidence in `JM_Resume_[EN]_11_sep_26.md` while preserving the current site's visual identity.

The page should serve consulting clients and hiring managers equally. It should present Jorge Mayorga as both a hands-on cybersecurity engineer and a trusted technical consultant.

## Main Content Gaps

- The HTML says `10+ years`, while the resume supports `15+ years` in IT and cybersecurity.
- The `99+ projects` claim is not supported by the resume and should be removed unless independently verified.
- The HTML does not mention AWS Community Builder status or bilingual English/Spanish capability.
- AppSec and DevSecOps are described generically instead of mentioning SAST, SCA, DAST, vulnerability triage, risk prioritization, and remediation.
- Cloud security is limited to AWS and GCP without explaining the architecture and development experience behind it.
- Technical leadership, staff management, training, pre-sales support, and customer decision-making are absent.
- The page has no professional experience timeline or selected career achievements.
- Certifications are incomplete and some names need to be reconciled against the resume and official verification records.
- Education, ongoing learning, and community service are not represented.
- The writing/community section lists profiles but does not identify specific articles, labs, projects, or outcomes.
- The current contact CTA is clear and should remain Telegram-only.

## Recommended Positioning

Use a consistent title such as:

> Cybersecurity Engineer & Consultant

Recommended supporting statement:

> Helping engineering and technology teams build safer software, cloud environments, and security programs through application security, DevSecOps, cloud security, and technical delivery.

The positioning should balance technical execution with customer-facing leadership. Avoid presenting Jorge only as a general cybersecurity consultant or only as a tool specialist.

## Section-by-Section Plan

### 1. Hero

- Replace the generic role label with `Cybersecurity Engineer & Consultant`.
- Keep the existing concise headline and visual treatment.
- Add `15+ years in IT and cybersecurity` as a supporting proof point.
- Mention AppSec, DevSecOps, cloud security, and professional services.
- Keep the primary actions as `View expertise` and `Contact me`.
- Keep Telegram as the only contact destination unless a public professional email is later approved.

### 2. Proof Bar

Use only claims that can be supported:

- `15+` years in IT and cybersecurity.
- `11+` people led or managed.
- `40+` professionals trained.
- AWS Community Builder and first security-focused AWS Community Builder in Colombia, if this distinction can be verified.

Remove `99+ projects`. Do not replace it with another project count unless a source or defined counting method is available.

The existing vendor list can remain, but it should be presented as experience with technologies and vendors rather than as a certification claim.

### 3. About or Professional Profile

Add a short profile section covering:

- AppSec, cloud, and security engineering specialization.
- Consulting and technical decision-making based on customer needs.
- Experience working across engineering, product, compliance, and customer teams.
- English and Spanish communication.
- AI-assisted workflows, prompt engineering, and security productivity improvements.

Keep this section concise. The full resume should not be copied into the landing page.

### 4. Expertise

Refine the current cards with resume-backed outcomes and methods:

- **Application Security:** Mobile and web application audits, OWASP practices, pentesting, SAST, SCA, DAST, vulnerability management, and remediation.
- **DevSecOps and Secure SDLC:** Integrating security into engineering workflows and prioritizing findings across technical and business teams.
- **Cloud Security:** Secure AWS and GCP architecture, cloud-native delivery, and AWS development experience.
- **Network and Edge Security:** Firewalls, WAF, IPS, anti-DDoS, SIEM, email security, and XDR.
- **Technical Leadership:** Customer consulting, architecture decisions, pre-sales PoCs, technical reports, product testing, staff management, and training.

Each card should state what Jorge does and the type of outcome it enables, rather than only listing tools.

### 5. Selected Experience

Add a compact, chronological timeline using the employment information in the resume:

- Tech Lead & Consultant, independent contractor, October 2025-present.
- Senior AM Engineer, AppSec & DevSecOps, Endava, 2022-September 2025.
- Cybersecurity Consultant, Data Systems Innovations, 2021-2022.
- Product Manager & Professional Services, Wanau SAS / Telefónica Movistar partner, 2016-2021.
- Systems & Security Engineer, independent contractor, 2013-2016.
- Senior Security Engineer / Support II / Systems Administrator, Digiware, 2009-2014.

Feature two or three achievements beside the timeline:

- Managed or coordinated teams of 11+ people.
- Trained 40+ staff members in security solutions.
- Supported pre-sales through PoC environments and technical reports.
- Achieved a 99% case-closure rate in 2010 and 100% customer satisfaction in 2011, with the dates and original context preserved.

Avoid implying that the historical support metrics are current performance.

### 6. Anonymized Case Studies

Add three case-study cards when enough details can be confirmed. Each should include:

- Client context or industry without disclosing restricted names.
- Security or delivery problem.
- Jorge's role and contribution.
- Relevant methods or technologies.
- Measurable result, risk reduction, delivery improvement, or customer outcome.

Potential case-study themes are AppSec and DevSecOps enablement, cloud security architecture, and professional-services or pre-sales delivery. Do not invent metrics; use qualitative outcomes when quantitative results are unavailable.

### 7. Certifications

Keep the current grouped layout, but reconcile it against authoritative records before publishing. Candidate entries from the resume include:

- AWS Certified Developer - Associate.
- AWS Certified Solutions Architect - Associate.
- FortiWeb Specialist.
- Fortinet Network Security Expert.
- Palo Alto Networks PSE Cortex and PCCSA.
- Sophos Certified Engineer.
- Certified Ethical Hacker.
- CompTIA Security+.
- Imperva Database Security Specialist / IDSS.

The current HTML also references Tenable TCME, Imperva, and Radware. Confirm whether these are certifications, product experience, or both before retaining them in the credentials section. Add verification links only when they are available and public.

### 8. Education and Ongoing Learning

Add a compact education section after certifications or experience:

- B.S. in Computer Science, major in Software Engineering, Colombian School of Engineering Julio Garavito, 2009.
- LLM Performance Engineering, O'Reilly, 2025.
- AWS Skill Builder architecture and development learning, 2022-2024.
- Web Security and OWASP in Java, SecureFlag, 2022.
- AI, ML, and Python, Platzi, 2019-2021.

Use a separate label such as `Education & continuing learning` so short courses are not confused with formal degrees.

### 9. Writing and Community

Keep the existing links to GitBook, TryHackMe, Hack The Box, GitHub, LinkedIn, and Telegram. Improve the content by:

- Featuring two or three representative articles, labs, or projects when available.
- Describing what visitors will find on each platform.
- Adding AWS Community Builder, OWASP, Google Developer Groups, BSides, and Python community participation.
- Including translator and volunteer experience only if it supports the desired professional narrative.

If no current articles or projects are ready to feature, label the section `Profiles and community` rather than promising writing and projects that are not linked.

### 10. Final Contact CTA

Use a direct, specific invitation such as:

> Need help with an AppSec program, cloud security review, secure delivery workflow, or technical security decision? Start a conversation on Telegram.

Repeat the Telegram CTA in the hero, navigation, and footer. Keep the action consistent and avoid adding a second contact channel without a deliberate decision.

## Content Rules

- Prefer specific responsibilities and outcomes over broad claims such as “secure everything.”
- Do not publish unsupported project counts, satisfaction percentages, or vendor claims.
- Distinguish current capabilities from historical achievements.
- Use exact certification names and preserve official capitalization.
- Treat the Markdown resume as the source for career facts, then adapt it into concise web copy.
- Use anonymization whenever client confidentiality is uncertain.
- Keep technical terms understandable to both security practitioners and non-specialist decision-makers.

## Implementation Order

1. Update the title, hero positioning, proof bar, and contact copy.
2. Rewrite the expertise cards using the resume-backed service areas.
3. Add the professional profile and selected experience timeline.
4. Add verified certifications, education, and community credentials.
5. Add anonymized case studies after confirming facts and publication permissions.
6. Replace generic writing/community copy with specific featured links or rename the section.
7. Review every metric, certification, employer name, date, and external link before publishing.

## Validation Checklist

- Confirm the `15+ years` calculation and wording.
- Confirm the AWS Community Builder distinction.
- Confirm whether `11+` refers to direct reports, staff managed, or a broader team.
- Confirm the `40+` training figure and subject matter.
- Verify every certification name and available verification URL.
- Confirm which vendor names represent certifications versus product experience.
- Approve anonymized case-study descriptions and results.
- Check that all public links and the Telegram CTA remain current.
