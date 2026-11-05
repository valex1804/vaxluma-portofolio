# Vaxluma.ai — 2026 Portfolio

A cutting-edge, high-performance portfolio showcasing AI-assisted creative direction, character consistency systems, style exploration, and commercial video production.

---

## Architecture & Canonical Pages

| Page File | Title | Description |
|:---|:---|:---|
| [`index.html`](./index.html) | **Intro & Hero** | 4K WebM intro animation with theatrical curtain reveal to the *AI Content Specialist* hero. Smart session skip logic prevents replay on refresh or back-navigation. |
| [`character-framework.html`](./character-framework.html) | **Character Consistency** | Interactive 4-card style consistency showcase (3D Pixar, Stylized Comic, Pop Animation, Digital Vector) with Figma-specified drop shadows and smooth animations. |
| [`styles-showcase.html`](./styles-showcase.html) | **Styles Showcase** | 21-style interactive slider with dynamic dot grid, mouse spotlight dampening, and category badges. |
| [`collection-of-work.html`](./collection-of-work.html) | **Collection of Work** | Deep-dive case studies covering Branding, Commercial Video Ads, Social Media Campaigns, and Production Workflows. |
| [`selected-work.html`](./selected-work.html) | **Selected Work 2026** | 4-column infinite waterfall video stream with hover pause, fullscreen lightbox viewer, and sound toggle. |

---

## Assets Directory Breakdown

```text
assets/
├── hero/              # Hero illustration & badge icons
├── character/         # Character illustration, process doodle, 4 card styles
├── styles/            # 21 high-definition style thumbnails
├── collection/        # Campaign graphics, 3D pedestals, process steps
│   ├── assets/
│   ├── adds-assets-htmlpage/
│   └── social-assets-video/
└── videos/
    ├── intro/           # 4K Intro animation (Intro-portofolio-4k.webm)
    └── selected-work/   # 10 curated MP4 clips (all under 30 MB for GitHub)
```

---

## GitHub & Web Deployment Notes

1. **GitHub 100 MB Limit Compliant**: All media files have been optimized and compressed. The largest file (`Freedom_MotorBike-V2.mp4`) was compressed from 312 MB down to 28 MB without visual fidelity loss.
2. **Zero External Dependencies**: Built with Vanilla CSS & Vanilla JavaScript. No bundlers or Node.js runtime required.
3. **Deploy Ready**: Directly compatible with **GitHub Pages**, **Vercel**, **Netlify**, or standard Apache/Nginx web servers.