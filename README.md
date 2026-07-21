# Joe Kraisler academic website — revised version

This is a framework-free static website. It consists only of HTML, CSS, one image, and a PDF CV, so it can be hosted on GitHub Pages, Netlify, NearlyFreeSpeech, or almost any ordinary web server.

## Preview locally

Open `index.html` in a browser. For the most reliable local preview, run a small local web server from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files

- `index.html` — homepage, biography, photograph, and contact information
- `research.html` — short research overview followed by publications and preprints
- `teaching.html` — teaching history
- `students.html` — undergraduate research and recommendation-letter guidance
- `style.css` — all visual styling
- `assets/joe-kraisler.jpg` — profile photograph
- `files/Joseph_Kraisler_CV.pdf` — curriculum vitae

## Editing

Open the folder in Visual Studio Code. Text is edited directly in the corresponding `.html` file. Save the file and refresh the page in your browser. Visual changes such as type size, page width, and spacing are controlled by `style.css`.

The navigation menu is written separately in each HTML file, so a future page name or link change should be made in all four pages.

## Publishing with GitHub Pages

1. Create a new public GitHub repository, for example `academic-website`.
2. Upload the contents of this folder to the repository root.
3. Open **Settings → Pages** in GitHub.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/root`, and save.
5. After the temporary GitHub Pages address works, add `joekraisler.com` as the custom domain.

Keep the current Google Sites version live until the new host and domain are working correctly.
