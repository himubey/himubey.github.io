<p align="center">
  <img src="favicon.svg" width="72" height="72" alt="HD">
</p>

<h1 align="center">Himanshu Dubey</h1>

<p align="center">
  Full-stack engineer, formerly fixing Macs.<br>
  Now building products people use every day.
</p>

<p align="center">
  <a href="https://himubey.is-a.dev">himubey.is-a.dev</a> ·
  <a href="https://www.himubey.in/blog">Blog</a> ·
  <a href="https://github.com/himubey">GitHub</a> ·
  <a href="https://www.linkedin.com/in/himubeydev/">LinkedIn</a>
</p>

---

## About

This is my personal portfolio. I once spent my days opening up Macs to find out what was wrong inside, and I built this site the same way: take out everything that isn't needed, and keep what is simple, fast and easy to fix.

## Principles

- **No frameworks.** Plain HTML and CSS, with no build step and no dependencies.
- **Almost no JavaScript.** A few lines handle the theme toggle, and that's all.
- **Light by default.** Two self-hosted variable fonts, one tiny SVG icon, and no trackers or third-party requests.
- **Easy on the eyes.** Warm cream in light mode, soft charcoal in dark mode. It follows your system setting and remembers your choice.
- **Content first.** Writing, projects and experience, with nothing in the way.

## Structure

```
.
├── index.html        Home: intro, writing, projects, experience
├── blog.html         All blog posts
├── css/style.css     Every style on the site, including both themes
├── fonts/            Outfit and Google Sans Code (variable, Latin subset)
├── images/           Profile photo
├── favicon.svg       Retro pixel "HD" mark
└── CNAME             Custom domain for GitHub Pages
```

## Run locally

There's nothing to install. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Customize

| What | Where |
|---|---|
| Colors (light and dark) | CSS variables at the top of `css/style.css` |
| Fonts | `@font-face` rules in `css/style.css` |
| New blog post | Add a `<li>` to the list in `blog.html` and `index.html` |

## Deploy

The site is served by **GitHub Pages** from the `main` branch. Anything merged into `main` goes live at [himubey.is-a.dev](https://himubey.is-a.dev).

## Credits

- [Outfit](https://fonts.google.com/specimen/Outfit) and [Google Sans Code](https://fonts.google.com/specimen/Google+Sans+Code), both under the SIL Open Font License
- Design inspired by the calm, content-first style of [Tania Rascia](https://www.taniarascia.com/)

---

<p align="center">
  Opened the DevTools console yet? There's a note in there for you.<br>
  <sub>© 2026 Himanshu Dubey</sub>
</p>
