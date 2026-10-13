# Personal Blog — GitHub Pages

A responsive, no-build personal website with a blog, About page, two example posts, and a light/dark theme toggle. Written in plain HTML, CSS, and JavaScript.

## Customize before publishing

1. Search all `.html` files for `Your Name` and replace it with your name or your blog's title.
2. Edit the introduction in `index.html` and your bio in `about.html`.
3. Replace `hello@example.com` in `about.html` with your contact address (or remove it if you don't want a public email).
4. Replace the sample posts with your own writing; sample dates and stories are fictional placeholders.
5. Change colors/fonts in `assets/style.css` if desired.

## Publish using GitHub Pages

1. Create a public GitHub repository named `YOUR_USERNAME.github.io` (replace the username).
2. Upload **the contents of this folder** into the repository root (not the containing `personal-blog` folder). `index.html` must be at the root.
3. Commit the files to the `main` branch.
4. Open Settings → Pages → Build and deployment.
5. Choose `Deploy from a branch`, select `main` and `/(root)`, then Save.
6. When deployment succeeds, browse to `https://YOUR_USERNAME.github.io/`.

## Add a new post

1. Copy a file in `posts/` to `posts/my-new-story.html`.
2. Edit its `<title>`, meta description, heading, date, and body text.
3. In `index.html`, copy an existing `<article class="card">...</article>` within `.cards`, and update the new card's title, date, summary, and links to `posts/my-new-story.html`.
4. Commit the changes to GitHub. The updated site will publish automatically.

## Preview locally

Open `index.html` in your browser, or serve this folder using a local development server (e.g. `python -m http.server 8000`) and visit http://localhost:8000.

## Notes

- Uses relative URLs so the site also works in a project repository at `https://YOUR_USERNAME.github.io/REPOSITORY/`.
- `.nojekyll` tells Pages to serve these static files without Jekyll processing.
- No login, database, comment system, or web server is included. Those require external services.
