# Soumyadip Ghosh | Portfolio

Single-page portfolio (plain HTML, CSS and JavaScript, no build step).

## Put it online with GitHub Pages

1. Create a new repository on GitHub, for example `portfolio`.
2. Upload `index.html`, `.nojekyll` and `README.md` to the repository root.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
5. Wait a minute. Your site appears at `https://<your-username>.github.io/portfolio/`.

Tip: name the repository `<your-username>.github.io` to get the shorter address `https://<your-username>.github.io/`.

## Add your photo permanently

1. Put your photo in the repository as `photo.jpg`.
2. In `index.html`, find `<img id="photo" alt="Portrait of Soumyadip Ghosh" hidden>` and change it to `<img id="photo" src="photo.jpg" alt="Portrait of Soumyadip Ghosh">`.
3. Find `<span class="initials" id="initials" aria-hidden="true">SG</span>` and delete that line.

## Add your LinkedIn and GitHub

In the contact section of `index.html`, copy one of the `.row` blocks and set the link to your profile URL.
