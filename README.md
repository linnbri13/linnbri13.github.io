# Personal site — linnbri13.github.io

A single-page personal site hosted free on GitHub Pages. Plain HTML/CSS — no build step, no dependencies.

## Live URL

`https://linnbri13.github.io`

## Structure

```
index.html        # Home page
style.css         # Shared styles
blog/             # Posts (one HTML file each)
```

## Adding a new post

1. Copy `blog/first-post.html` to `blog/your-post.html`
2. Edit the title, date, and content
3. Add a link in the Writing section of `index.html`
4. Commit and push

## Custom domain (optional)

Create a `CNAME` file at the repo root with your domain, e.g. `linnbri13.dev`,
then add a DNS record pointing it at `linnbri13.github.io`.

## Publishing

Push to `main` — GitHub Pages publishes automatically within ~1 minute.
