# Sarowar Hossain Rony — Portfolio

This repository contains my personal portfolio website, built as a lightweight static site for presenting software, cybersecurity, CTF, education, and project work in one accessible place.

The site is intentionally dependency-light: the primary pages are static HTML documents, with CSS and JavaScript used for layout, interaction, theme preferences, navigation, and project presentation. It is designed to load quickly, remain easy to maintain, and work well as a public professional profile.

## What the site presents

| Section | Purpose |
| --- | --- |
| Profile and introduction | Provides a concise overview of my software-engineering and cybersecurity direction. |
| Selected projects | Highlights practical work such as defensive-security tooling, software projects, and document intelligence. |
| Achievements | Presents CTF results, team activities, and security accomplishments. |
| Education and certifications | Summarizes academic background and professional security credentials. |
| Contact and links | Connects visitors to GitHub, LinkedIn, email, and other professional resources. |
| CV and supporting assets | Includes the portfolio CV and selected visual assets used by the site. |

## Design and accessibility

The portfolio uses a responsive layout that adapts to desktop and mobile viewports. It includes a day/night preference, clear content grouping, readable contrast, keyboard-friendly controls, and project links that make it easy for a reviewer to move from the portfolio to the underlying source repository.

The site’s content is organized around the way an internship or early-career reviewer typically evaluates a candidate: first understanding the technical focus, then reviewing selected work, then checking evidence such as achievements, education, certifications, and contact information.

## Repository structure

```text
.
├── index.html                 # Main portfolio landing page
├── portfolio.html             # Extended portfolio/project presentation
├── assets/                    # Profile and presentation assets
├── 23524202051.pdf            # Supporting CV/document asset
├── rony_cv_project_order_fixed.tex
├── .github/workflows/pages.yml # GitHub Pages deployment workflow
└── todo.md                    # Ongoing content and maintenance notes
```

## Technology

| Layer | Technologies |
| --- | --- |
| Markup | HTML5 |
| Styling | CSS3, responsive layout, theme variables |
| Interaction | Vanilla JavaScript |
| Hosting | GitHub Pages |
| Automation | GitHub Actions |
| Documents | PDF and LaTeX source for the CV |

## Local preview

Because the site is static, it can be previewed with any local HTTP server. For example:

```bash
git clone https://github.com/AYANOKOJI-71/AYANOKOJI-71.github.io.git
cd AYANOKOJI-71.github.io
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser. Opening the HTML file directly may work for basic content, but an HTTP server is recommended for consistent asset loading and browser behavior.

## Deployment

The repository is configured for GitHub Pages. Changes pushed to the configured branch are handled by the workflow in `.github/workflows/pages.yml`. Before publishing a change, check the site at desktop and mobile widths, verify navigation and theme controls, and confirm that project links and downloadable documents still work.

## Maintenance checklist

When adding a project, include a short explanation of what it demonstrates, the technologies used, a link to the repository, and—when available—a live demonstration. Keep descriptions specific and distinguish completed implementations from projects that are still in development. Compress large images and keep the site dependency-light so the portfolio remains fast and easy to review.

## Author

Built by **Sarowar Hossain Rony**.

- Portfolio: [ayanokoji-71.github.io](https://ayanokoji-71.github.io/)
- GitHub: [AYANOKOJI-71](https://github.com/AYANOKOJI-71)
- LinkedIn: [Sarowar Hossain Rony](https://www.linkedin.com/in/shrony/)
