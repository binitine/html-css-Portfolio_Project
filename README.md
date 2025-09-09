# Portfolio

Purpose: A single-page, semantic, accessible portfolio using only HTML and one CSS file.

Structure:
- `index.html`: One-page site linking to `css/styles.css` and `assets/profile.jpg`.
- `css/styles.css`: Single consolidated stylesheet (variables, layout, components).
- `assets/`: Images (add `profile.jpg` here).

How to open:
1. Add your photo to `assets/` as `profile.jpg` (optional).
2. Open `index.html` in a browser (double-click), or serve locally.
   - PowerShell: `cd portfolio` then `python -m http.server 5500` → open `http://localhost:5500`

Accessibility notes:
- Semantic landmarks: `header`, `nav`, `main`, `section`, `footer`.
- Headings: `h1` (site), `h2` (sections), `h3` (project titles).
- Skip link to main content is provided and focusable.
- Links have visible focus styles; colors chosen for contrast.
- Images include `alt` text (edit as needed).

Validation:
- Meets constraint: no JS, no frameworks/libraries, one CSS file.
- Validate with W3C validators for HTML and CSS. 