# Computer Vision Roadmap 
A structured, resource-rich learning path from pixels to production. Covers Classical CV, Deep Learning, Vision Transformers, and Edge AI deployment — with interactive tools built in.

<p align="center">
  <a href="https://sadhanasharma26.github.io/computer-vision-roadmap/roadmap.html" target="_blank">
    <img src="https://img.shields.io/badge/Launch%20Interactive%20Roadmap-Click%20Here-blueviolet?style=for-the-badge" alt="interactive roadmap">
  </a>
</p>

---

## Navigation Sitemap

```
computer-vision-roadmap/
├── docs/
│   ├── index.html          Landing page → roadmap.html
│   └── roadmap.html        Interactive roadmap (main experience)
│       ├── Phase 1: The Foundations (Math & Pixels)
│       ├── Phase 2: Feature Engineering & Classical CV
│       ├── Phase 3: The Deep Learning Era
│       ├── Phase 4: Modern Frontiers
│       ├── 💼 Interview Prep Bank
│       └── ⚡ Edge AI Deployment Track
├── roadmap.md              Text outline of all 4 phases
├── resources.md            Curated resource cards with metadata
├── projects.md             Milestone project specs
├── CONTRIBUTING.md         Contribution guidelines
└── README.md               This file
```

---

## The 4 Phases

| Phase | Title | Duration | Milestone Project |
|-------|-------|----------|-------------------|
| 01 | The Foundations — Math & Pixels | 4–6 weeks | NumPy Image Filter Library |
| 02 | Feature Engineering & Classical CV | 4–5 weeks | Panorama Stitcher (SIFT + RANSAC) |
| 03 | The Deep Learning Era | 6–8 weeks | Custom Object Detector + Segmentation |
| 04 | Modern Frontiers | 5–7 weeks | Real-Time Edge AI Detector |

---

## Progress Tracking

All progress saved to `localStorage` — no account needed. Check topics as you complete them; your progress persists across sessions. Hit **Reset** in the header to start over.

---

## Resource Card Format

Every resource in this roadmap includes:

| Field | Values |
|-------|--------|
| **Difficulty** | Easy / Intermediate / Hard |
| **Time** | Estimated hours |
| **Type** | Video / Paper / Book / Tutorial / Course / Repo |
| **Why this?** | One sentence on specific value |

---

## Suggested Tech Stack (for contributors)

The current site is plain HTML/CSS/JS deployed via GitHub Pages — zero build step, works everywhere.

To scale toward a full content platform:

- **Next.js + MDX** — write phase content in Markdown, embed React components (resource cards, visualizers) inline
- **Tailwind CSS** — utility-first, matches the card-heavy layout
- **Framer Motion** — phase transitions and checklist animations
- **Vercel** — free tier covers this traffic volume

Until content volume justifies the migration, the current stack is the right call.

---

## Quick Start

```bash
# Clone
git clone https://github.com/sadhanasharma26/computer-vision-roadmap.git

# Python environment
conda create -n cv_env python=3.9
conda activate cv_env

# Core libraries
pip install opencv-python numpy matplotlib
pip install scikit-learn scikit-image
pip install torch torchvision          # or tensorflow
pip install ultralytics                # YOLOv8
pip install jupyter notebook
```

Open `docs/roadmap.html` in a browser, or visit the [live site](https://sadhanasharma26.github.io/computer-vision-roadmap/roadmap.html).

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). To add a resource, follow the card format above — include difficulty, time estimate, type, and a one-sentence "why this?" rationale.

---

## License

MIT — see [LICENSE](LICENSE).

---

## Contact

- Open an [issue](https://github.com/sadhanasharma26/computer-vision-roadmap/issues) for bugs or suggestions
- [LinkedIn](https://www.linkedin.com/in/sadhana-sharma-/)
- [Discussions](https://github.com/sadhanasharma26/computer-vision-roadmap/discussions)
