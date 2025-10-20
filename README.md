# Joshuah Elmore — Portfolio

A minimal, single-page portfolio with:
- Header (name + navigation)
- Hero section (welcome + contact links + resume button)
- Summary, Education, Work Experience, Projects
- Skills and Volunteer sections

## Quick start

- Open `index.html` in your browser. On Windows, you can double-click it in File Explorer.

Optional: run a tiny local server (useful if you later add images or scripts):

```powershell
# From the my_portfolio folder
python -m http.server 8000
# Then visit http://localhost:8000/
```

## Customize

- Update text in sections: `#summary`, `#education`, `#experience`, `#projects`, `#skills`, `#volunteer`.
- Add or change contact links in the hero (email, LinkedIn, GitHub).
- Add a PDF resume named `resume.pdf` in this folder to enable the "Download Resume (PDF)" button in the hero.
- Tweak colors and spacing in `styles.css`.

## Structure

- `index.html` — The page markup
- `styles.css` — Styles and layout
- `resume.pdf` — Optional; if present, the hero shows a Download Resume button
- `README.md` — This guide
