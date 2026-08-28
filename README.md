# Dan Case Portfolio — Static Site V1

A lightweight HTML/CSS/JS portfolio designed to position Dan as a senior creative executive, author and educator rather than a conventional production-focused portfolio designer.

## Files

- `index.html` — homepage
- `about.html` — editorial about page + photo gallery
- `kind-words.html` — full recommendations showcase linked from the homepage leadership section
- `work/` — five initial case-study pages
- `styles.css` — full responsive design system
- `script.js` — mobile menu, scroll reveals, dynamic copyright year
- `assets/images/about/` — photos extracted from the supplied Dan Photos document
- `assets/images/books/` — local book mockups for the Writing / Published Work sections
- `404.html` — optional Cloudflare Pages 404

## Current V1 project set

1. Signs of Hope — The Salvation Army
2. UCHealth — Live Extraordinary
3. GameStop — national TV
4. ESPN ESPYs
5. Restore — The Salvation Army

A recent executive/leadership case study should be added next as project 06.

## IMPORTANT: temporary image dependency

The five legacy work pages currently reference image URLs on the existing Squarespace CDN. This was intentional for V1 because high-resolution originals have not yet been supplied. The site itself is independent of Squarespace, but those work images are not yet local.

When high-resolution assets are available:

1. Put them in `assets/images/work/`.
2. Replace the Squarespace URLs in `index.html` and each `work/*.html` page with relative local paths.
3. For video projects, replace thumbnail-only presentation with the preferred video embeds or local hosted video.

The About-page photography is already local. The book images used in the Writing and About sections are also now local.

## Contact details used

- Email: `dancase@icloud.com`
- LinkedIn: current link from the legacy site / public profile reference

Update these directly in `index.html`, `about.html`, and the shared headers if desired.

## Local preview

From this folder:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub + Cloudflare Pages

1. Create a new GitHub repository, for example `dan-case-portfolio`.
2. Upload the contents of this folder to the repository root. Do **not** upload the containing folder as an extra nesting level; `index.html` should be at the repo root.
3. In Cloudflare: **Workers & Pages → Create → Pages → Connect to Git**.
4. Select the repository.
5. Framework preset: **None**.
6. Build command: leave blank.
7. Build output directory: `/` (repository root).
8. Deploy.
9. Add `danielrcase.com` as a custom domain in the Pages project.
10. Only after the Cloudflare preview is approved, update DNS / move the production domain away from Squarespace.

## Design intent

- Editorial / executive rather than “portfolio template”
- Quiet authority rather than self-promotional language
- Large typography and generous whitespace
- Work framed as evidence of judgment and leadership
- No software/tool proficiency section
- Leadership, writing and teaching are first-class proof points
- About photography shows a fuller creative life without becoming a personal social feed


## Image treatment

The About-page photography has been selectively stylized to better match the site's warm, editorial tone. The original extracted JPEGs are still included, and the live page now references the updated PNG versions for the main portrait and visible About-page gallery images.

## Testimonials

The homepage leadership section now links to a dedicated Kind Words page containing the full roster of recommendations from the legacy portfolio. The recommendations page uses concise adapted summaries for a cleaner executive presentation while preserving each recommender's name and professional context.

## Repository baseline

This reconciled V5 build is the first complete GitHub baseline. It includes the stylized About imagery, the two published-book images, and the Kind Words testimonials showcase in one tracked version. Future changes should build from this baseline.

## V6 note

The Kind Words page now uses all 18 testimonials in the original wording supplied by Dan rather than adapted summaries. The About-page closing line is now “Experience sharpens the eye. Curiosity keeps it open.”

## V7 note

Added a dedicated Photography / Personal Work section to the About page. The section is intentionally separated from client Work so it reads as a personal creative practice and evidence of visual judgment—not as a photography service offering. Twelve supplied photographs are stored locally in `assets/images/photography/`.


## V8 note

Selected Work has been reorganized around the five projects chosen for the next portfolio build. The Salvation Army Christmas Animations case study now embeds four Vimeo films: Gus, Battle, Emma and Chloe. The Salvation Army Christmas campaign page is staged for incoming artwork and project details.


## V9 note

Work imagery for the Salvation Army Christmas Animations, UCHealth, Signs of Hope and GameStop case studies is now stored locally in `assets/images/work/`. Role is standardized as **Concept & Art Direction**. UCHealth now includes Enemy Territory and Love Story Vimeo embeds; GameStop includes Bunny Wii, Wii Black, Transformers, Dead Space and Gamestock. The Christmas Animation page pairs the supplied stills with the four Vimeo films.


## V10 note

Homepage hero metadata now sits directly below the 24-year positioning statement and is left-aligned. The temporary Selected Work build-status note has been removed.


## V11 note

The Salvation Army Christmas case study is now complete with the supplied hero, Santa thumbnail, Overhead thumbnail and Vimeo embeds for both films. The homepage Christmas project card now uses final supplied imagery. The GameStop hero image has also been replaced with the latest supplied asset.


## V12 note

Homepage project cards now use hero artwork rather than video thumbnails for UCHealth, Salvation Army Christmas Animations and Salvation Army Christmas. Across every video-based case study, the presentation is now: case-study hero first, then the Vimeo player itself. Redundant still/thumbnail images above individual video embeds have been removed.


## V13 note

UCHealth now uses the newly supplied public Dropbox hero image on both the homepage project card and the case-study hero. Two additional Signs of Hope executions—anti-trafficking hotline and forced-labor awareness—have been added to the case-study gallery as local assets.


## V14 note

Added more breathing room between the small section label and the primary headline in Creative Leadership, Writing & Teaching, and the homepage About Dan section. The main homepage hero spacing was intentionally left unchanged.
