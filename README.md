# Ana Brito — Portfolio

An English-language, responsive portfolio built with semantic HTML and custom CSS. No package installation, build step, tracking or API keys are required.

## Open locally

Open `index.html` in a browser, or use the Live Server extension in VS Code. Edit the content in `index.html` and the visual design in `style.css`.

## Content

- Introduction and current junior front-end career goal.
- Saldo project, links to its live Vercel demo and GitHub repository.
- Native expandable case study: problem, experience, implementation and limitations.
- Estúdio listed as in development, without invented live links.
- About section based on supplied work experience and training.
- GitHub profile used as the contact channel; add your email and LinkedIn when ready.

The finance illustration is HTML/CSS, not a screenshot. Its caption identifies the fictional preview. The project case study discloses AI assistance. Review and update all personal statements so they reflect your current experience before publishing.

## Design decisions

Warm paper background, dark ink and terracotta accents create an editorial identity separate from Saldo. Large typography establishes hierarchy; the illustrated project makes the work tangible. A one-page structure supports quick recruiter scanning. No animation or interaction is needed to access the content, and the case study uses native `details`/`summary`.

Navigation and actions are real links. Keyboard focus styles, a skip link, descriptive labels and reduced-motion support are included. Responsive layouts adapt at 900 px and 600 px. This is not a claim of audited WCAG compliance.

## GitHub

Create an empty repository named `ana-brito-portfolio`. In this folder:

```sh
git init
git add .
git commit -m "Add English portfolio"
git branch -M main
git remote add origin https://github.com/anabrito23/ana-brito-portfolio.git
git push -u origin main
```

The remote must exist before pushing. Git identity configuration from a different repository may not apply here; if requested, set `git config user.name` and `git config user.email` in this folder using your own details.

## Vercel

Import the new repository. Select **Other** as the application preset, root `./`, no build command and output directory `.` (or leave the static-site defaults). This portfolio uses plain HTML/CSS, unlike the Saldo React/Vite application. No environment variables are required.

## Before publishing

Check the live demo and code links, expand the case study, navigate with Tab and test at 375 px, 768 px, desktop and 200% zoom. The current delivery received static source checks, but no visual browser verification. Personal contact details can be added without a backend using a `mailto:` link.
