# Portfolio site

A simple, no-build personal site (about, experience, projects, skills, contact) that runs free on GitHub Pages.

## Files

- `index.html` - all the content. Replace every `[bracketed placeholder]`.
- `style.css` - colors, fonts, layout. Change the colors at the top (`--accent` is the main one).
- `images/` - create this folder and add `headshot.jpg`, `project-1.jpg`, `project-2.jpg`, `project-3.jpg`.
- `resume.pdf` - add her resume here so the "Download resume" button works (or delete that button).

## Publish on GitHub Pages

1. Sign in to GitHub and create a **new public repository** named `USERNAME.github.io` (replace USERNAME with her exact GitHub username).
2. Upload everything in this folder to the repository (use "Add file" > "Upload files", or git).
3. Open the repo's **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, choose the `main` branch and `/ (root)`, then Save.
4. After a minute or two the site is live at `https://USERNAME.github.io`.

## Tips

- Search `index.html` for `[` to find every placeholder you still need to fill in.
- Don't need a section? Delete the whole `<section>` block and its link in the nav.
- Want more projects? Copy one `<article class="card">` block and paste it below.
- Preview locally by double-clicking `index.html`.
- Custom domain: Settings > Pages > Custom domain.
