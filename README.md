# Imaduddin Sheikh portfolio

A responsive software engineering portfolio featuring a professional bio, practical value statement, and a growing collection of projects.

## Files

- `index.html`: homepage, bio, value statement, project spaces, and professional contact links.
- `assets/styles.css`: desktop, mobile, reduced-motion, and print styles.
- `assets/site.js`: the automatically updated footer year.
- `assets/imaduddin-sheikh-resume.pdf`: supplied résumé, linked from Experience.
- `artifact-template.html`: reusable project case-study template, kept at its existing URL and marked `noindex` until filled with real work.
- `.nojekyll`: supports direct static publishing from the repository branch.

The site has no package dependencies, external fonts, analytics, or build tools. Newsreader is self-hosted in `assets/fonts/`, with its open-font license included. It uses relative asset paths and preserves the existing `#work`, `#about`, and `#contact` anchors. The navigation and main collection heading both use Projects.

## Preview locally

Serve this folder with a static HTTP server. For example, run `python -m http.server 4173` in this folder and open `http://localhost:4173`.

## Deployment

Repository: https://github.com/isheikh8492/isheikh8492.github.io

Website: https://isheikh8492.github.io/

GitHub Pages publishes directly from **main → /(root)**. Commit updates to `main`, wait for the deployment to succeed, and check the live pages and assets. No custom build workflow is needed.

## Add a project

1. Copy `artifact-template.html` to a descriptive filename at the same folder level, such as `project-name.html`.
2. Replace the page title, metadata, template notice, and instructional copy with accurate details about completed work. Remove `noindex` when the finished page is ready to be indexed.
3. Include the actual deliverable through a public link, accessible embed, or downloadable file. Use relative asset paths for files stored with the site.
4. Complete the title, introduction, description, objective, process, tools and technologies, value proposition covering unique value and relevance, and applicable references. Identify personal contributions accurately for collaborative work.
5. Update one project card in `index.html`: use the real title, update its status, add a concise summary, and link to the completed page. For example: `<a class="text-link" href="project-name.html">View project →</a>`.
6. Use an actual deliverable preview if appropriate. Duplicate the card structure to add more projects.
7. Test every deliverable link without relying on a signed-in account.

## Content maintenance

The five initial cards are clearly labeled spaces for future projects. They do not represent completed work. Publish only actual experience and supported results. Experience uses one-sentence summaries supported by the supplied résumé; Education retains its degree details. Keep dates, titles, institutions, and results supported by the source résumé. The introduction is a consolidated value statement.

## Visual system

Newsreader throughout on one warm off-white surface. Centered navigation stays visible while scrolling, without repeating the name above the introduction. Employer groups show role progression; all approved role summaries remain unchanged. Projects use open rows, education uses two columns on desktop, and Contact uses large icons above smaller labels. The layout adapts to phone and tablet widths.

Homepage order: Introduction → Areas of Focus → Experience → Projects → Education → Contact.
