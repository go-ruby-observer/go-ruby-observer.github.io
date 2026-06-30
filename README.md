<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-observer/brand/main/social/go-ruby-observer.png" alt="go-ruby-observer/go-ruby-observer.github.io" width="720"></p>

# go-ruby-observer.github.io

The organization's institutional landing page, served at
<https://go-ruby-observer.github.io> and built with [Hugo](https://gohugo.io). It
is a single page (custom `layouts/index.html`, capability cards driven by
`[[params.phases]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-ruby-observer/docs](https://github.com/go-ruby-observer/docs), served at
<https://go-ruby-observer.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
