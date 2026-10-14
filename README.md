# Cody Ayers: Portfolio

My personal portfolio site: an introduction, featured projects, a resume page and
a contact form.

**Live site:** https://cody-ayers.github.io/PortfolioWebsite/

## Pages

- **Home:** intro, tech stack and featured projects
- **About:** background and technical skills
- **Work:** every project with screenshots, live demos and GitHub links
- **Resume:** a print-friendly resume (print or save as PDF from the page)
- **Contact:** a contact form powered by Formspree

## Built with

- Semantic HTML5 and hand-written CSS (custom properties, Flexbox and Grid, BEM-style class names)
- No framework or build step
- Responsive layout and a print stylesheet for the resume
- Formspree for the contact form
- Stylelint for CSS linting
- GitHub Pages for hosting

## Running locally

No build step is needed. Serve the folder and open it in a browser:

```bash
git clone https://github.com/Cody-Ayers/PortfolioWebsite.git
cd PortfolioWebsite
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploying

GitHub Pages publishes the `gh-pages` branch, so push both branches:

```bash
git push origin main && git push origin main:gh-pages
```
