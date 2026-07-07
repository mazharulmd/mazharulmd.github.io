# Md Mazharul Islam — Academic Portfolio

![Jekyll](https://img.shields.io/badge/Jekyll-CC0000?logo=jekyll&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222?logo=github&logoColor=white)
![Made with Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

Personal academic portfolio, hosted at **[mazharulmd.github.io](https://mazharulmd.github.io)**.

The site presents my research and work in **cybersecurity, trustworthy AI, privacy-preserving systems, and cyber-physical systems security**, alongside my publications, experience, and credentials - built as a fast, static Jekyll site.

---

## About the Site

A Jekyll static site built on the [AcademicPages](https://github.com/academicpages/academicpages.github.io) theme (a fork of [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)), with custom styling applied per page for a consistent, modern look and full light/dark support.

**Sections (top navigation):**

- **Home** - research focus, highlights, and selected work
- **Publications** - journal articles, conference papers, thesis, and manuscripts under review
- **Education** - degrees and thesis
- **Experience** - research, teaching, and professional roles
- **Certifications** - verifiable industry credentials (AWS, EC-Council, Oracle, Azure)
- **Skills** - technical toolkit
- **Honors & Awards** - recognition and academic service
- **CV** - downloadable PDF
- **Blog** - self-hosted write-ups (also mirrored on Medium)

---

## Tech Stack

- **Jekyll** - static site generator
- **GitHub Pages** - hosting and CI
- **Markdown + Liquid** - content and templating
- **HTML / SCSS** - structure and styling
- **YAML** - configuration and data files

---

## Repository Structure

```text
.
├── _config.yml            # Site configuration
├── _pages/                # Page content (home, publications, education, blog, ...)
├── _publications/         # Publication entries (one Markdown file per paper)
├── _posts/                # Blog posts
├── _teaching/             # Teaching entries (collection)
├── _portfolio/            # Portfolio entries (from theme; optional)
├── _data/navigation.yml   # Top-nav menu structure
├── _includes/ & _layouts/ # Theme templates
├── _sass/                 # Stylesheets
├── assets/                # Compiled CSS, JS, icons
├── files/                 # Downloadable files (CV, paper PDFs)
├── images/                # Images and avatar
└── README.md              # You are here
```

---

## Run Locally

Requires Ruby, Bundler, and Jekyll.

```bash
# install dependencies
bundle install

# serve with live reload at http://localhost:4000
bundle exec jekyll serve --livereload
```

## Deploy

The site deploys automatically via **GitHub Pages** on every push to the `main` branch — no manual build step. Deployment status is visible under the repository's **Actions** tab.

---

## Editing Content

- **Add a publication:** create a Markdown file in `_publications/` with the appropriate front matter (`category`, `status`, `permalink`, `venue`, etc.). The Publications page groups and numbers entries automatically.
- **Add a blog post:** create a Markdown file in `_posts/` named `YYYY-MM-DD-title.md`.
- **Update the CV:** replace `files/mazharul_islam_cv.pdf` (keep the same filename so every link keeps working).

---

## Acknowledgments

Built on the [AcademicPages](https://github.com/academicpages/academicpages.github.io) template by Robert McDonnell and contributors, itself based on [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) by Michael Rose.

---

## Contact

- **Email:** mazharul.islam1@northsouth.edu
- **Website:** [mazharulmd.github.io](https://mazharulmd.github.io)
- **LinkedIn:** [linkedin.com/in/mazharul-i-tusar](https://www.linkedin.com/in/mazharul-i-tusar)
- **GitHub:** [github.com/mazharulmd](https://github.com/mazharulmd)
- **Google Scholar:** [profile](https://scholar.google.com/citations?user=LGE4nW4AAAAJ&hl=en)

---

## License

The site's code inherits the **MIT License** from the AcademicPages/Minimal Mistakes theme. Written content, publications, and personal materials are © Md. Mazharul Islam and are not covered by the MIT License.
