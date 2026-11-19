# Dr. Hisham Sleem — personal website

This is a static, responsive website built from the supplied CV and portrait. It has no paid dependencies, advertising, tracking scripts, or animation libraries.

## Files
- `index.html` — website content and SEO metadata
- `styles.css` — responsive visual design
- `script.js` — small mobile navigation interaction
- `assets/hisham-sleem.jpg` — supplied portrait
- `Hisham-Sleem-CV.docx` — supplied CV download

## Before publishing
1. Open `index.html` in a text editor.
2. The LinkedIn section has been omitted because you do not have a LinkedIn account.
3. If you want the website to use a different public contact email, update the `mailto:` links and structured-data email consistently.
4. Review the public CV and contact details before publishing. The site intentionally does not publish the CV's reference contacts.

## Free publishing with GitHub Pages
1. Create a free account at https://github.com/ if you do not already have one.
2. Create a new **public** repository named exactly `Dr-Sleem.github.io` (replace the placeholder with your GitHub username).
3. Upload all files and folders in this package to the repository's root. Do not upload the ZIP file itself.
4. In the repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish. Your address will be `https://Dr-Sleem.github.io/`.

GitHub Pages is free for public repositories. GitHub controls its service terms and availability; no paid plan is required for this setup.

## Google search indexing
1. After the site is live, open Google Search Console: https://search.google.com/search-console/
2. Add the website as a URL-prefix property and verify ownership using one of the offered methods.
3. Submit `https://Dr-Sleem.github.io/sitemap.xml`.
4. Use URL Inspection to request indexing of the home page.

Indexing is controlled by Google and is not guaranteed or immediate. The SEO title, description, canonical URL, structured data, headings, semantic HTML and sitemap provide a sound starting point.

## Updating the site
Edit `index.html` to change professional information, publications, links or CV download. Replace `Hisham-Sleem-CV.docx` with the updated CV using the same filename. To change the portrait, replace `assets/hisham-sleem.jpg` with the new image using the same filename. Commit the changes to GitHub; Pages will publish the update automatically.

## Accuracy note
The page content is based on the uploaded six-page CV. Date overlaps and the source CV's stated details have not been independently reconciled or verified. Please review the website before making it public.
