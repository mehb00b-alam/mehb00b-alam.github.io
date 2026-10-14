# Mehboob Alam — Personal Portfolio Website

A responsive, static personal website built with plain HTML, CSS, and JavaScript. It includes:

- About Me, Education, Teaching and Professional Experience
- Machine Learning / Optimization / Scientific Computing Projects
- Research Interests, Thesis Projects, All 18 Listed Journal Publications with DOI links
- Technical Skills, Awards, Scholarships, Service, Conferences, Contact Links
- Downloadable academic CV and industry résumé PDFs
- Responsive layout, dark/light theme switch, mobile menu, publication search and filters

## Preview

Double-click `index.html` in your browser (or run `python -m http.server 8000` in this folder and open `http://localhost:8000`). The website works offline without a build step or external dependencies.

## Publish for free with GitHub Pages

1. Create a repository at github.com named `mehb00b-alam.github.io` (or any name, such as `personal-website`).
2. Upload the **contents** of this folder to the root of the repository.
3. In **Settings → Pages**, under **Build and deployment**, select **Deploy from a branch**, `main`, `/(root)`, and Save.
4. Your site will be available at `https://mehb00b-alam.github.io/` for the profile-named repository, or at `https://mehb00b-alam.github.io/personal-website/` for the example repository. Deployment may take a few minutes.

Netlify Drop is another simple option: drag the website folder onto Netlify's deploy page.

## Editing

- Update biography, project and experience copy in `index.html`.
- Update or add publications in the `publications` array at the top of `script.js` (all entries have `title`, `authors`, `journal`, `year`, `doi`, `first`).
- Change theme, color palette, layout, or spacing in `styles.css`.
- Replace `docs/Mehboob_Alam_Academic_CV.pdf` and `docs/Mehboob_Alam_Industry_Resume.pdf` as your CV evolves.
- Replace LinkedIn/GitHub/Scholar/ResearchGate links if they change.

## Review before publishing

The bundled PDF documents were copied from your existing CV and résumé, with the phone number redacted for public sharing. The website displays your professional email and social links, but not your phone number. Check publication details, date ranges, GPA, and submitted-manuscript status for any updates since your documents were last edited.

This is a static site: the Email button opens the visitor's email app; it does not run a backend contact form or collect visitor information.

## Profile photograph (October 2026)

The portrait on the homepage is stored in `assets/mehboob-alam-portrait.webp`. Replace that image with a similar square photo to update it. The HTML and CSS control its size and crop.
