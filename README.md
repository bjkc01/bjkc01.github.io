# Bijay Kumar Khatri Portfolio

[![Live Site](https://img.shields.io/badge/Live%20Site-bjkc01.github.io-0a0f1c?style=for-the-badge)](https://bjkc01.github.io/)
![HTML](https://img.shields.io/badge/HTML-Single%20File-e34f26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-Embedded-1572b6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-f7df1e?style=for-the-badge&logo=javascript&logoColor=111111)

A single-page cybersecurity portfolio website for Bijay Kumar Khatri. The site highlights experience, projects, skills, and contact information in a static GitHub Pages-friendly format.

## Live Demo

Visit the portfolio here: [https://bjkc01.github.io/](https://bjkc01.github.io/)

## Screenshot

A preview image has not been committed yet. If you want, I can still set this up later once a screenshot file is added to the repository.

## Project Overview

- `index.html` contains the full page markup, embedded CSS, and embedded JavaScript.
- `Resume_Khatri_Bijay_CIS_Cybersecurity.pdf` is the resume file linked directly from the site.
- `sections/` stores planning notes and future content ideas for each major section of the portfolio.

## Current Sections

- Hero / intro
- Experience
- Projects
- Skills / tech stack
- Contact

## Folder Structure

```text
.
|-- index.html
|-- README.md
|-- Resume_Khatri_Bijay_CIS_Cybersecurity.pdf
`-- sections/
    |-- contact-form/
    |   `-- README.md
    |-- experience/
    |   `-- README.md
    |-- hero-intro/
    |   `-- README.md
    |-- projects-work/
    |   `-- README.md
    `-- skills-tech-stack/
        `-- README.md
```

## Editing Guide

- Update text, layout, styles, and interactions directly in `index.html`.
- Replace the root resume PDF if the linked resume changes.
- Use the section folders to keep future copy, assets, notes, and content ideas organized without changing the single-file deployment approach.

## Local Preview

You can open `index.html` directly in a browser for a quick preview.

If you want to run a small local static server instead:

```powershell
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Notes

- The contact form is currently front-end only and does not submit anywhere yet.
- Project links, GitHub links, and contact details are defined directly inside `index.html`.
- The site does not currently use a framework, package manager, or build step.
