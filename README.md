# Imaduddin Sheikh portfolio

A responsive, buildless portfolio for GitHub Pages. It preserves the approved professional bio and personal value proposition and reserves five clearly labeled spaces for AIML-500 artifacts.

## Files

- `index.html`: homepage, approved content, contact links, and five upcoming artifact spaces.
- `assets/styles.css`: desktop, mobile, reduced-motion, and print styles.
- `assets/site.js`: accessible mobile navigation and the footer year.
- `artifact-template.html`: reusable course-artifact page; not linked from the public homepage until real work is added.
- `.nojekyll`: enables direct static publishing from the repository branch.

There are no package dependencies, external fonts, analytics, or build tools. Contact links use the professional email, GitHub profile, and LinkedIn profile in the supplied résumé. The résumé PDF itself is not included.

## Preview locally

Serve this folder with any static HTTP server. For example, run `python -m http.server 4173` in this folder and open `http://localhost:4173`.

## GitHub Pages deployment

Repository: https://github.com/isheikh8492/isheikh8492.github.io

Site address: https://isheikh8492.github.io/

The site publishes directly from **main → /(root)**. GitHub handles the Pages build and deployment; no custom workflow or build dependencies are needed.

To update the site:

1. Edit the site files in the repository’s `main` branch. Keep `index.html` at the repository root.
2. Commit the changes. GitHub Pages publishes them automatically.
3. Check **Settings → Pages** and the repository’s deployment status, then verify the live page and links.

To configure a fresh copy, select **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root)**. The site’s relative paths also work on a project site such as `/portfolio/`.

## Add a completed AIML-500 artifact

1. Confirm that the assignment designates the work as a course artifact. Outside projects do not count toward the required course collection.
2. Copy `artifact-template.html` to a descriptive filename at the same folder level, such as `ai-timeline.html`.
3. Replace the template title, description, notice, and instructional text with accurate information about your completed work. Remove the `noindex` meta tag when the page is ready.
4. Include the finished deliverable, an embed, or a working direct link. For downloadable files, use a relative location such as `assets/artifacts/filename.pdf` and commit the file.
5. Complete the title, introduction, description, objective, process, tools and technologies, artifact-specific value proposition (unique value and relevance), and applicable references.
6. Update one reserved card in `index.html`: replace its title, summary, and status, remove the decorative placeholder mark if you add a preview, and replace its footer with a real link. For example: `<a class="text-link" href="ai-timeline.html">View artifact →</a>`.
7. If you add more than five assigned artifacts, duplicate an article using the same structure.
8. Test the artifact link without relying on a signed-in account. Do not link to a generic “Shared with me” page.

Submit the required reflections in Brightspace’s designated text area. Keep those submission reflections off the public portfolio.

## Content boundaries

All five initial cards are reserved spaces, not completed artifacts. The site does not claim that five artifacts have been completed or that course submission requirements have been met. Add only actual experience and supported results when revising the bio or artifact descriptions.
