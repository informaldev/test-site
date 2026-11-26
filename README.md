# Informal Capital

A starter site in plain HTML and CSS, hosted on GitHub Pages.

| File | What it does |
|---|---|
| `index.html` | The page content (text, headings, links) |
| `style.css` | The look (colours, fonts, layout) |
| `README.md` | This note. GitHub shows it on the repo page |

To edit: change the text in `index.html`, or the colours at the top of `style.css`, then push. GitHub Pages redeploys in about a minute.

## Adding a portfolio company

Open `portfolio.json` and add a line in the same format (mind the commas):

```json
{ "name": "Company Name", "url": "https://company.com/" }
```

Add it anywhere in the list: the site sorts companies A to Z automatically. Commit the change and the site updates in about a minute.
