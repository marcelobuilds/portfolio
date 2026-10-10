# Marcelo B — Portfolio

Complete static website: six HTML pages, shared CSS, original whiteboard photographs, and the product-strategy infographic. No installation or build step is needed.

## Publish on GitHub Pages

1. Create a repository named `YOUR-USERNAME.github.io`, replacing YOUR-USERNAME with your exact GitHub username. Select Public if using GitHub Free.
2. Extract this ZIP. Open the extracted folder and upload its contents to the repository. `index.html` and `style.css` must be at the repository root, alongside the `about`, `projects`, `experience`, `contact`, and `assets` folders. Do not upload the ZIP itself or nest the whole folder in the repository.
3. Commit the files to the `main` branch.
4. Open Settings → Pages. Under Build and deployment, choose Deploy from a branch. Select `main` and `/ (root)`, then Save.
5. Wait for publication, then use the Visit site link on the Pages settings screen. It can take up to 10 minutes.

The site will be publicly visible once published. The included `.nojekyll` file tells GitHub to serve the static files directly. If your file picker hides it, create a new empty file named `.nojekyll` in the repository.

You can also use a repository named `portfolio`; its address will be `https://YOUR-USERNAME.github.io/portfolio/`. All page and image links in this export are relative and work in either location.

## Edit the portfolio

- `index.html`: homepage and featured project
- `about/index.html`: background, school, interests, and goals
- `experience/index.html`: activities and experience
- `contact/index.html`: email and LinkedIn placeholders
- `projects/index.html`: project gallery
- `projects/calendar-nobody-opens/index.html`: full calendar case study
- `style.css`: shared colors, typography, and layout
- `assets/`: original images

Edit the HTML directly in a text editor or GitHub's file editor. Your name is already Marcelo B. School, activities, goals, and contact information remain placeholders. Shared navigation and footers appear in each HTML page; update each page when changing those elements.

To add a project, copy the case-study folder under a new name, replace its contents and page title, and add a link in the gallery and, if desired, on the homepage.

Open `index.html` locally to preview. The image files are preserved; the whiteboard photos are rotated for readability by CSS.

This export is independent of the ChatGPT-hosted site. Changes made on GitHub do not automatically update that copy.

Official instructions:
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
