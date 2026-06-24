# Skills & libraries used to build this site

This site is hand-coded HTML/CSS/JS, deployed via GitHub → Vercel. It is built on the
highest-starred open-source libraries and design skills that genuinely apply to a
marketing site like this. Redundant or framework-specific ones were deliberately left
out so nothing conflicts.

## Animation & interaction libraries (loaded via official CDN)

| Library | GitHub stars | Role on this site |
|---|---|---|
| [GSAP](https://github.com/greensock/GSAP) + ScrollTrigger | ~23k | Hero image zoom, parallax, scroll-driven motion |
| [Lenis](https://github.com/darkroomengineering/lenis) | ~8k | Smooth scrolling, synced with ScrollTrigger |
| [Swiper](https://github.com/nolimits4web/swiper) | ~40k | The journey gallery carousel |

**Deliberately not added:** Three.js (3D, not needed), Anime.js (overlaps GSAP — stacking
both is an anti-pattern), Motion/Framer Motion (React-only; this site is vanilla HTML).

## Design skills applied (guidance, not code)

| Skill | Stars / installs | What it contributed |
|---|---|---|
| [Impeccable](https://github.com/pbakaus/impeccable) | ~10k stars | Ran its detector CLI; fixed contrast, AI-tell glows, em-dashes, numbered markers, eyebrow chip. 46 → 9 findings (remaining 9 are intentional). |
| Vercel Web Interface Guidelines | ~176k installs | Accessibility (decorative SVGs aria-hidden, skip link, focus rings), performance (lazy images, hero priority, CDN preconnects), CLS (image dimensions), mobile (touch-action, theme-color). |
| [Anthropic frontend-design](https://github.com/anthropics/skills) | ~124k installs | Base design principles (Impeccable extends this). |

Note: design skills are guidance files for AI coding agents — they shape *how* the site is
built, they are not part of the deployed site. Their value is in the applied result above.
