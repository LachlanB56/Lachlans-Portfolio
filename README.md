# Your Portfolio Site

A single-page portfolio (About / Experience / Projects / Education), styled to match
https://emajkic.github.io/ — same layout, spacing, hover animations, section structure,
and light-blue accent color. No build tools required; it's one static `index.html`.

## 1. Edit the content

Everything is in `index.html`. Search for these placeholders and replace them:

- **Hero**: your name, tagline, `mailto:` address, LinkedIn/GitHub URLs
- **About**: the two bio paragraphs, and the skill pills in `#skills-list`
  (copy/paste a `<span>...</span>` to add more, delete extras)
- **Experience**: duplicate the `<div class="group relative block">...</div>` block
  to add more roles
- **Projects**: duplicate a project card to add more; the small number (`01`, `02`, …)
  is just text, update it manually
- **Education**: school, degree, achievements, courses
- **Footer**: name, tagline, social links (mirrors the hero — keep them in sync)

## 2. Add your photos

Drop your images into the `images/` folder and update the matching `<img src="images/...">`
paths in `index.html`. Until you do, every image slot shows a light-grey
"Add your photo" placeholder so the page never looks broken.

Recommended: square-ish photos, at least 600x600px, .jpg or .png.

## 3. Add your resume

Put your resume PDF in this folder as `resume.pdf` (or update the `href` on the
"Resume" button in the hero section to point wherever you put it).

## 4. Preview locally

Just double-click `index.html` to open it in a browser — no server needed.

## 5. Deploy on GitHub Pages (free, and works well on a resume/LinkedIn)

1. Create a new GitHub repo named exactly `your-username.github.io`
2. Push this folder's contents to that repo's `main` branch
3. In the repo Settings → Pages, confirm the source is the `main` branch / root
4. Your site goes live at `https://your-username.github.io/`

That URL is what you put on your resume and LinkedIn "Featured" section.

## Notes on fonts

The reference site uses the LaTeX "Computer Modern" + "Latin Modern Sans" font
files, which aren't freely redistributable as webfonts. This version uses
Google Fonts **Source Serif 4** (headings) and **Inter** (body) as close,
professional-looking, license-free substitutes — everything else (layout, spacing,
colors, card styles, scroll/fade animations) matches.
