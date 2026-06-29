# Yash Joshi — Personal Portfolio

> **Live site →** [yashjoshi.github.io](https://yashjoshi.github.io)

Personal portfolio website for **Yash Joshi**, Biotechnology Specialist (HBSc, University of Toronto) and Digital Strategy professional. Built as a single-page, fully responsive HTML/CSS/JS site — no frameworks, no dependencies, deployable anywhere.

---

## About

This portfolio showcases work at the intersection of **life sciences, data analytics, and digital strategy** — targeting roles in pharmaceutical digital strategy, bioanalytical research, and healthcare innovation.

**Sections covered:**
- Hero — headline, tagline, and call-to-action
- About — background, education, core interests, and target role profile
- Experience — Cliantha Research · Astreca · Digital Advertising
- Case Studies — 4 project cards with filterable categories and metric visualisations
- Skills Grid — Laboratory & Biotech · Data & Analytics · Digital Strategy · Compliance & AI
- Contact — email form, LinkedIn, and resume download

---

## Tech Stack

| Layer | Choice | Why |
|---|---|---|
| Markup | HTML5 | Single file, zero build step |
| Styling | CSS custom properties | Theming without a preprocessor |
| Interactivity | Vanilla JS | No dependencies, fast load |
| Charts | Canvas API | Radar chart drawn natively |
| Fonts | Google Fonts (Inter + JetBrains Mono) | Corporate-technical feel |
| Hosting | GitHub Pages | Free, fast, version-controlled |

---

## Colour Palette

| Name | Hex | Used for |
|---|---|---|
| Deep Navy | `#0F1E36` | Backgrounds, hero, nav |
| Tech Teal | `#00A3A6` | Accents, links, highlights |
| Light Slate | `#F5F7FA` | Section backgrounds |
| Warm Amber | `#E07A5F` | Primary CTA buttons only |

---

## Folder Structure

```
yashjoshi.github.io/
├── index.html       ← entire site (single file)
├── photo.jpg        ← profile photo (add your own)
├── resume.pdf       ← downloadable resume (add your own)
└── README.md        ← this file
```

---

## Getting Started Locally

No build tools required. Just open the file in a browser:

```bash
# Clone the repo
git clone https://github.com/yashjoshi/yashjoshi.github.io.git

# Open directly in browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or use VS Code's Live Server extension for hot-reload while editing.

---

## Personalisation Checklist

Before going live, make these edits inside `index.html`:

- [ ] **Profile photo** — replace the `avatar-placeholder` div with `<img src="photo.jpg" class="hero-avatar" alt="Yash Joshi" />`
- [ ] **LinkedIn URL** — update both instances of `linkedin.com/in/yash-joshi` (contact section + footer)
- [ ] **Email address** — update the `mailto:` link and display text in the contact section
- [ ] **Resume PDF** — replace `onclick="alert..."` with `href="resume.pdf" download` and upload `resume.pdf` to this repo
- [ ] **Project links** — add your GitHub repo URLs and live demo links inside each `.project-card`
- [ ] **Contact form** — wire up to [Formspree](https://formspree.io) or [EmailJS](https://emailjs.com) for real email delivery

---

## Deploying to GitHub Pages

1. Push all files to the `main` branch of a repo named `yourusername.github.io`
2. Go to **Settings → Pages → Branch → main → Save**
3. Wait 1–3 minutes — your site goes live at `https://yourusername.github.io`

Updates go live within ~60 seconds of any commit to `main`.

---

## Featured Projects

| # | Project | Domain | Tools |
|---|---|---|---|
| 1 | HealthFlux Biological Data Integration | Digital Health · Systems Biology | Python, REST APIs, D3.js |
| 2 | Bioanalytical Method Validation Pipeline | GxP · HPLC · IVRT/IVPT | ICH Q2(R1), CAPA, SOP |
| 3 | Multi-Channel Campaign Attribution Model | Digital Analytics | GA4, Looker Studio, GTM |
| 4 | Biotech Drug-Development Dashboard | Python · Data Viz | Pandas, Plotly Dash, NumPy |

---

## Contact

| Channel | Link |
|---|---|
| LinkedIn | [linkedin.com/in/yash-joshi](https://linkedin.com/in/yash-joshi) |
| Email | yash@youremail.com |
| Portfolio | [yashjoshi.github.io](https://yashjoshi.github.io) |

---

## License

This repository is open for reference and inspiration. If you use this as a base for your own portfolio, please replace all personal content (text, images, project descriptions) with your own before publishing.

---

*Built and maintained by Yash Joshi · University of Toronto HBSc Biotechnology*
