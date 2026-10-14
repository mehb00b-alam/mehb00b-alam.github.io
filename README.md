# Mehboob Alam — multi-page personal website

This is a static, responsive portfolio for https://mehb00b-alam.github.io/.
No framework, npm install, build step, or server-side software is needed.

## Site architecture
- `index.html`: homepage overview
- `about.html`, `projects.html`, `research.html`, `publications.html`, `experience.html`: major pages
- `education.html`, `skills.html`, `community.html`, `contact.html`: additional pages
- `projects/*.html`: individual detailed project pages
- `research/*.html`: two thesis overview pages
- `publications/*.html`: bibliographic publication records for all 18 articles
- `styles.css`: shared design and responsive layout
- `script.js`: dark mode, mobile navigation, filterable publications, copy email
- `assets/`: professional portrait, favicon
- `docs/`: academic CV and industry résumé; contact phone removed for public sharing

## Publishing and updating on GitHub Pages
The repository must be named `mehb00b-alam.github.io` and be public.
Upload the **contents** of this folder to the `main` branch root (the `index.html` should be alongside `styles.css`).
Go to Settings > Pages > Deploy from a branch > `main` > `/(root)`.
**Important:** Delete old files only when you want to remove them; replacing existing names should update them.

To update an individual project, edit its file inside `projects/`.
To add a publication, add a record to the `publications` array in `script.js`, create a matching detail page, and link it from the list.
DOI and publication data originally came from the author's CV and earlier website; verify links after publishing.

## Limitations / review items
- Some ML project pages summarize coursework; actual result figures and code repository links can be added later.
- Classification is marked in progress based on the supplied source résumé; update as needed.
- Publication records provide citations and DOI links, not full copyrighted journal articles.
- The email link opens visitors’ mail apps; the website does not host a contact-form backend.
- Review dates, GPAs, publication status, and URLs before treating the portfolio as finalized.
