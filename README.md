# Caleb — Portfolio

**https://portfolio-five-bice-18.vercel.app/**

Single-page portfolio built with vanilla HTML, CSS, and JavaScript. Orbital ring project display, dark theme, custom canvas background animation per project.

## Projects

| # | Project | Category |
|---|---------|----------|
| 01 | Incident Analysis | Forensics / Log Analysis |
| 02 | Agent Fleet | Autonomous Multi-Agent Orchestration |
| 03 | Choice Engine | C++ / Game Dev |
| 04 | Home Lab | Multi-OS Security Lab |
| 05 | Wall-Drawing Robot | Arduino / Robotics |
| 06 | Rubik's Cube Solver | Computer Vision / Robotics |
| 07 | Bionic Claws | Mechanical Design |
| 08 | Custom RC Car | Electronics / Assembly |
| 09 | ShortForm Engine | Local AI / Video Pipeline |
| 10 | Trading Scanner | Quant / Algo Research |
| 11 | DormNet Monitor | Networking / Sysadmin |
| 12 | School Network Ops | Network Monitoring / Dashboards |
| 13 | AI Filter Engine | AI-Driven Content Filtering |

## Tech

- HTML, CSS, vanilla JS
- Canvas 2D (per-project background animations)
- Fraunces + JetBrains Mono (Google Fonts)
- Deployed on Vercel (auto-deploy from `main`)

## Structure

```
├── index.html      # Everything — markup, styles, scripts, project data
└── reports/        # Linked PDFs (incident analysis report, etc.)
```

## Development

Edit `index.html` directly. Project data lives in the `PROJECTS` array near the top of the script block; background animations are the `drawXxx()` functions; orbital tweaks are in `TWEAK_DEFAULTS`. Push to `main` and Vercel deploys automatically.

## Contact

Caleb Howell — [LinkedIn](https://www.linkedin.com/in/caleb-howell-28979540a/) | [GitHub](https://github.com/thesquirrel437fr)
