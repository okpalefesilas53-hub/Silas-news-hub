# Silas News & Updates

A static, API-free news website designed for GitHub Pages.

## How to add a story
Open `script.js` and find `const stories = [`. Add another object using this format:

```js
{cat:'Nigeria',icon:'🇳🇬',title:'Your headline',text:'A short summary of the story.',source:'Official source name'}
```

Supported categories can be any category you want, for example Nigeria, Education, Technology, World, Sports, or Entertainment.

## Publish on GitHub Pages
Replace the old `index.html`, `style.css`, `script.js`, and `README.md` with these files. Keep `index.html` in the repository's main/root folder.

## Important
This version does **not** use an API, database, or external AI service. News is manually added to `script.js`, making it suitable for a simple GitHub Pages deployment.
