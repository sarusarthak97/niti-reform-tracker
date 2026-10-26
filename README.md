# NITI Reform Tracker (prototype)

Prototype website prepared by FED for NITI Aayog: a single record of the Government of India's regulatory reforms for business.

Not an official Government of India website. Search engines are asked not to index it (robots.txt and a noindex tag).

## Files
- `index.html`: the whole site in one file (styles, scripts, data and images inline)
- `robots.txt`: blocks search engine indexing while this is a preview
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Publish on GitHub Pages
1. Create a public repository, for example `niti-reform-tracker`.
2. Upload these files to the main branch.
3. Settings > Pages > Build and deployment: Source "Deploy from a branch", Branch "main", folder "/ (root)". Save.
4. The site goes live at `https://<account>.github.io/niti-reform-tracker/` within a few minutes.

To update, upload a new `index.html` over the old one.
