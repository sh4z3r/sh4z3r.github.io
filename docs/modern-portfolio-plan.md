# Modern IT Portfolio Plan

## Current Site Review

The site has strong raw material: clear cybersecurity positioning, real experience, certifications, and a recognizable ShazerTech identity. The current presentation feels dated because:

- The layout is based on old inline-block CSS and fixed spacing.
- The page has invalid HTML, including `<class>` instead of a semantic element and no opening `<body>`.
- There is no clear primary action such as "Work with me," "View experience," or "Contact."
- The hero content is confusing: the Telegram handle, alias, title, and role compete for attention.
- Social links are mostly unlabeled and rely on outdated Font Awesome 4.
- Large empty gaps and fixed footer margins create poor mobile layouts.
- Skills and certifications are dense lists rather than proof of capability.
- "99 projects" and "98% satisfaction" need context or supporting evidence.
- The external GitHub-hosted avatar should use the local `Avatar.png`.
- The copy needs sharper positioning and more outcome-focused language.

## Recommended Direction

Create a dark, technical but professional portfolio with a restrained cybersecurity aesthetic:

- Use a deep charcoal background with electric amber and red accents derived from the existing logo.
- Use a monospace font only for labels, metadata, and technical details.
- Use a modern sans-serif font for readable headings and body text.
- Add a subtle grid or terminal-inspired texture without excessive hacker effects.
- Build the layout with responsive CSS Grid and Flexbox instead of fixed-height hacks.
- Include strong contrast, keyboard-visible focus states, and accessible link labels.

## Proposed Structure

### Navigation

- ShazerTech/Jorge Mayorga branding
- About, Expertise, Certifications, and Writing links
- Prominent `Let's talk` button

### Hero

- Positioning statement: "Cybersecurity consultant helping teams ship safer software and infrastructure."
- Supporting statement covering AppSec, DevSecOps, cloud security, and professional services
- `View expertise` and `Contact me` buttons
- Logo/avatar and a small availability or status indicator

### Proof Bar

- 10+ years in cybersecurity services
- 99+ projects
- AWS, Fortinet, Palo Alto, and Tenable experience
- Replace the unsupported satisfaction percentage or explain its source

### Expertise

- Application Security
- DevSecOps and secure SDLC
- Cloud security
- Network, WAF, XDR, and DDoS protection
- Engineering leadership and customer delivery

### Selected Work

Add three to four case-study cards. Each card should explain the problem, contribution, technologies, and result. Use anonymized client descriptions where necessary.

### Certifications

Group certifications by Cloud, Security Foundations, Network Security, and Application/Infrastructure Security. Link each certification to a verification page when available.

### Writing and Community

Highlight GitBook articles, TryHackMe and Hack The Box profiles, GitHub projects, LinkedIn, and Telegram.

### Contact CTA

Add a clear invitation for consulting, architecture reviews, AppSec programs, or speaking. Include a direct email or contact link instead of making visitors search through social icons.

## Content Improvements

Replace:

> Cybersecurity Consultant | Web Security | Engineering & Management

With:

> Cybersecurity consultant focused on AppSec, DevSecOps, cloud security, and secure delivery.

Replace:

> Hundreds of successful projects and happy customers

With:

> Led technical delivery across enterprise, telecom, finance, government, and SME environments.

## Implementation Plan

1. Rebuild `index.html` with semantic sections, accessible navigation, descriptive links, and improved metadata.
2. Replace the existing stylesheet with a compact responsive design system using CSS variables, Grid, Flexbox, and `clamp()`.
3. Remove the old Font Awesome dependency and use text labels or lightweight inline SVG icons.
4. Use the local avatar asset and add Open Graph and Twitter metadata.
5. Add a favicon, descriptive page title, and basic SEO metadata.
6. Validate the HTML and test at mobile, tablet, and desktop widths.
7. Add reduced-motion support and visible focus styles.

## Design Principle

The strongest version should be a dark editorial cybersecurity portfolio: technical enough to feel authentic to an IT audience, but polished enough for consulting clients and hiring managers.
