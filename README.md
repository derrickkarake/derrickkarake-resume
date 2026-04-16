# derrickkarake-resume

One-page resume site for Derrick Karake — full-stack engineer focused on Azure cloud architecture.

Live site: https://derrickkarake.github.io/derrickkarake-resume/

## Files

- `index.html` — landing page
- `styles.css` — site styles
- `resume.html` — print-styled source for the PDF
- `Derrick_Karake_Resume.pdf` — one-page resume (generated from `resume.html`)

## Regenerate the PDF

```
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" \
  --headless --disable-gpu --no-pdf-header-footer \
  --print-to-pdf="Derrick_Karake_Resume.pdf" \
  "file://$PWD/resume.html"
```
