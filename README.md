# Yanbin Gong — Resume Website

A responsive, static HTML/CSS resume site ready for Cloudflare Pages.

## Files
- `index.html` — website content
- `style.css` — design and responsive layout
- `resume.pdf` — **not included**. Add your own PDF resume before publishing if you want the download buttons to work.

## Before publishing
1. Review all descriptions for accuracy; the text is a draft, not a verified complete resume.
2. Add your PDF as `resume.pdf` in the same folder as `index.html`.
3. Add your professional email and LinkedIn URL to the contact section.
4. Avoid publishing private contact information you do not want indexed.

## iPhone → GitHub
1. Save the ZIP to Files and tap to extract it.
2. In Safari, create a GitHub repository at https://github.com/new.
3. Open the repository, choose **Add file → Upload files**.
4. Upload the *contents* of the extracted `my-resume` folder (`index.html`, `style.css`, and optionally `resume.pdf` and `README.md`), not the ZIP itself.
5. Commit the files. If the upload UI is difficult, try Safari's **Request Desktop Website**.

## Cloudflare Pages
1. Open https://dash.cloudflare.com and navigate to Workers & Pages.
2. Create a **Pages** project connected to the GitHub repository.
3. Set framework preset to **None**; no build is required. Set output directory to the repository root (`.`), and leave the build command empty if allowed.
4. Deploy. Cloudflare provides a `*.pages.dev` URL.

The project needs no npm packages, build step, or backend.
