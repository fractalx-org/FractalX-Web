# FractalX Web

Marketing and documentation site for [FractalX](https://github.com/Project-FractalX/FractalX) - the open-source static decomposition framework for Spring Boot.

## Structure

```
FractalX-Web/
├── index.html          # Homepage
├── docs/               # Documentation
├── blog/               # Blog listing and posts
├── privacy/            # Privacy policy
├── terms/              # Terms and conditions
├── resources/          # PDFs (developer guide, evaluation report)
└── assets/             # Images and favicons
```

## Adding a blog post

1. Create a folder under `blog/` named after the post slug, e.g. `blog/my-post-title/`
2. Copy an existing post page as a starting point: `blog/the-core-science-behind-fractalx/index.html`
3. Update the title, tags, date, read time, and article content
4. Add a new `<a class="post-card">` entry to `blog/index.html`

## Development

No build step. Open any `index.html` directly in a browser, or serve locally:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## License

Apache 2.0 - same as the FractalX framework itself.
