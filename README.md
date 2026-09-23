# Anudeep Marapally — Portfolio Website Package

This ZIP is the checked GitHub Pages package. It includes the public portfolio, Owner Builder, project pages, CSS, resume, thumbnails, profile photo, and an embedded-image `portfolio-data.js`.

## Main files
- `index.html` — home page
- `projects.html` — project listing
- `builder.html` — Owner Builder
- `portfolio-data.js` — central portfolio data; current project thumbnails/profile photo are embedded in this file
- `style.css` — shared styling
- `resume.pdf` — public resume

## Project pages
- `olist.html`
- `food-delivery-customer-analytics.html`
- `retail-sales-performance-analysis.html`
- `zara-sales-revenue-analysis.html`
- `ipl-century-performance-dashboard.html`
- `hospital-management-system-sql.html`
- `global-freelancers-income-work-pattern-analysis.html`

## Image workflow
1. Open `builder.html`.
2. Change text or upload a new profile/project image.
3. Click **Save Changes** for local browser use.
4. Click **Export for GitHub**.
5. Replace the repository's `portfolio-data.js` with the exported file and push/commit it to GitHub.

You do **not** need to manually rename thumbnail files for future Builder uploads. The Builder converts uploaded images into embedded data URLs when exporting.

## Important
- Browser `localStorage` changes are local to that browser/device; they do not automatically update GitHub.
- The public GitHub Pages site uses the committed `portfolio-data.js`.
- The Builder password is a convenience gate for a static site, not server-grade authentication.
