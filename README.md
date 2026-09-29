# BFF11 conference website

Website for **BFF11: the Eleventh Bayesian, Fiducial & Frequentist Conference**, May 24–26, 2027, University of Minnesota Twin Cities campus, Minneapolis. Hosted by the Institute for Research in Statistics and its Applications (IRSA).

Plain static HTML served by GitHub Pages (no build step; `.nojekyll` disables Jekyll).

- Pages: `index.html`, `committees.html`, `404.html`
- Shared styles: `assets/css/style.css`; menu script: `assets/js/site.js`; logos and icons: `assets/img/`
- The header/footer are repeated in each page; change them in every file.
- Before launch: remove the `<meta name="robots" content="noindex">` line and the draft notice bar from every page.
