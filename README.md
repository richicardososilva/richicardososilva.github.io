# Richard Cardoso da Silva — Academic website

A minimalist static academic website with six pages: Home, Research, Publications, Science communication, About and CV.

## Preview locally

Open `index.html` in a browser. For a more faithful preview from the website folder run `python3 -m http.server 8000`, then open `http://localhost:8000`.

## Publish

- **Cloudflare Pages (no GitHub needed):** create a Pages project and choose **Direct Upload**. Upload the contents of this directory (or a zip of its contents), with `index.html` at the root.
- **Netlify:** use its manual deploy / drag-and-drop site deployment and upload the directory.
- **GitHub Pages:** create a repository, upload the files to the repository root, and enable Pages from the main branch and root folder.

Deployment workflows may change over time; check your hosting provider’s current instructions.

## Edit

- Text lives directly in `index.html`, `research.html`, `publications.html`, `science-communication.html`, `about.html` and `cv.html`.
- Styling: `assets/style.css`. Mobile navigation and click-to-load YouTube players: `assets/main.js`.
- Images: `assets/images/` (user-provided photos). Downloadable CV: `assets/docs/Richard_Cardoso_da_Silva_CV.pdf`.
- The final YouTube video is intentionally labelled “Additional research video” because its exact title was not confirmed.
- The biography describes the proposed ChromBreak programme as prospective; do not label a laboratory or host appointment as established unless confirmed.

## Search visibility

After publishing, connect a personal domain if desired. Set the website’s full public URL in the `url` field of the Person JSON-LD in each page’s `<head>`. Consider adding absolute `og:image` and canonical URLs once the final domain is known. Verify the site in Google Search Console and request indexing. Add the public site URL to ORCID, Google Scholar, LinkedIn and your institutional/public researcher profiles.

**Privacy:** All images and the CV are publicly accessible after you publish. Check that the details you want public (including contact information in the PDF) are appropriate.

## Credit

Website assembled from materials supplied by Richard Cardoso da Silva, with external media links drawn from his memorial. Personal photographs are credited to their respective photographers where applicable; confirm photo reuse rights before publishing.

## Latest changes

- Smaller homepage greeting and a visible contact email (richicardoso.silva@gmail.com).
- Research page stays focused on published work and broad research interests, without describing a proposed or unapproved grant.
- Added a humorous annotated laboratory-bench photo to the Science Communication gallery.
