# Pavle Orlović - personal web presentation (Homework 1)

A small static web site about me, made with **HTML, CSS and Bootstrap 4.5.2**, published with **GitHub Pages**.

| File | Content |
|---|---|
| `index.html` | About me: the welcome area with the photo, a short biography, cards with facts and strengths |
| `education.html` | Education as a timeline, and a table of certificates |
| `experience.html` | Work experience as a timeline, and skills in a grid of three cards |
| `contact.html` | E-mail, and a form that opens the e-mail program of the visitor |
| `css/style.css` | my own styles: colours, the welcome area, the round photo, the timeline |
| `images/pavle.png` | the photo |

What is used from the lectures of module 01:

- **HTML**: headings, paragraphs, lists, links between pages, an image, a table, a form;
- **CSS**: an external style sheet, classes, a CSS variable (`--accent`), the pseudo-element `::before` (the dots of the timeline);
- **Bootstrap**: a navbar that folds into a button on a phone, a container and the grid (`row`, `col-md-*`),
  cards, badges, progress bars, list groups, buttons, a striped table, form controls, spacing utilities (`mt-5`, `mb-4` ...).

## Viewing it on the computer

```text
python -m http.server 8000
```

in this folder, then open <http://localhost:8000>. (Or simply double-click `index.html`.)

## Publishing with GitHub Pages

1. On GitHub, create a repository named exactly **`PavleOrl.github.io`** (my GitHub username is PavleOrl), public, without a README.
2. In this folder:

   ```text
   git init
   git add .
   git commit -m "Homework 1: personal web presentation"
   git branch -M main
   git remote add origin https://github.com/PavleOrl/PavleOrl.github.io.git
   git push -u origin main
   ```

3. On GitHub: **Settings > Pages**, *Source*: **Deploy from a branch**, branch **main**, folder **/ (root)**, Save.
4. After a minute the site is at **https://PavleOrl.github.io**.
