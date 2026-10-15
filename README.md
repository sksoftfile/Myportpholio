# Shashank Singh — IT Leadership Portfolio

## IMPORTANT: Keep these three files together
The website uses a relative stylesheet and script path. Your folder must look exactly like this:

```text
shashank-portfolio/
├── index.html
├── style.css
├── script.js
└── README.md
```

Do not open `index.html` from inside the ZIP preview. Extract the ZIP first, then open `index.html` from the extracted folder.

## Run locally
1. Extract `shashank-portfolio.zip`.
2. Confirm `index.html`, `style.css`, and `script.js` are in the same folder.
3. Double-click `index.html` to open it in a browser.

If CSS still does not load:
- Check that the stylesheet is named exactly `style.css` (not `style.css.txt` or `Style.css`).
- In `index.html`, the stylesheet line should be: `<link rel="stylesheet" href="./style.css">`.
- Refresh with **Ctrl + F5**.
- If using GitHub Pages, upload all files into the same repository folder and keep filename capitalization exactly the same.
- If you uploaded only `index.html`, upload `style.css` and `script.js` too.

Optional local server:
```bash
python -m http.server 8000
```
Run the command from inside the extracted folder, then visit `http://localhost:8000`.

## Deploy on GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, `script.js`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
5. Wait for GitHub Pages to show the published URL.

## Deploy on Netlify
Deploy the extracted folder containing `index.html`, `style.css`, and `script.js` using Netlify's manual deployment or CLI.

## Customization
- Edit website content in `index.html`.
- Edit colors/layout in `style.css`.
- Edit navigation and animation behavior in `script.js`.
- Google Fonts load from the internet; if offline, the page falls back to system fonts.

## Publishing note
This is a personal portfolio, not an official CERSAI website. Review employment details and contact information before publishing publicly.
