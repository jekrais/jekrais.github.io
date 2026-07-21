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
