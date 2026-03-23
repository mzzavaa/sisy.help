# sisy.help

The SISY Support Center. Built with Hugo - no theme, layouts only.

**Live site:** https://sisy.help

## About

sisy.help is the support and help center for the SISY platform. Users can find guides, FAQs, video walkthroughs, and contact support.

## SISY Ecosystem

| Site | Purpose |
|------|---------|
| [sisy.world](https://sisy.world) | Main platform landing page |
| [sisy.help](https://sisy.help) | Support center (this repo) |
| [sisy.info](https://sisy.info) | Press kit |
| [sisy.social](https://sisy.social) | Community hub |
| [sisy.my](https://sisy.my) | Expert profiles |
| [sisy.video](https://sisy.video) | Speaker reels |
| [sisy.courses](https://sisy.courses) | Expert learning |
| [sisy.today](https://sisy.today) | Live opportunities feed |
| [sisy.team](https://sisy.team) | Organizer tools |
| [sisy.forum](https://sisy.forum) | Community forum |

## Development

```bash
brew install hugo
hugo server -D
hugo --gc --minify
```

## Design System

- **Fonts:** Inter (body) + Playfair Display (display/headings) via Google Fonts
- **Icons:** Lucide via CDN
- **Accent:** #8b7e74 (light) / #a89b91 (dark)
- **BG:** #f8f6f4 (light) / #1a1816 (dark)
- **Dark mode:** data-theme="dark" on html, persisted in localStorage

## Deployment

GitHub Actions to GitHub Pages on push to main.
