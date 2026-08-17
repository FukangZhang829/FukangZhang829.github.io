# FukangZhang829.github.io

Fukang Zhang (张福康) — personal homepage & portfolio.

Industrial LLM & Agent Engineer @ AVIC Digital · Master's student @ Beihang University
(National Superior College for Engineers). Focus: industrial LLMs & agents, production
scheduling optimization, GNN & reinforcement learning.

## Structure

- `index.html` — single-file portfolio (no build step): hero, stats, about, experience,
  projects (with APS.mp4 demo & jump link), skills, publications, awards, contact.
  Supports EN/CN toggle, dark/light theme, mobile menu, scroll-reveal animations.
- `aps/index.html` — standalone project intro page for the Interactive Production
  Scheduling Agent (HiDAPS × APS Agent), linked from the Projects section.
- `assets/` — images and demo videos (APS.mp4, dataTran.mp4, FJSP-Thesis.png, ...).

## Deploy

Push to the `main` branch — GitHub Pages serves the repo root automatically:

```bash
git add -A
git commit -m "update portfolio"
git push origin main
```
