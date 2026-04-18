# ReminderText Website

Marketing site and legal documentation for ReminderText, built as a GitHub Pages Jekyll site.

## Local Development

### 1. Install dependencies

```bash
bundle install
```

### 2. Run the site locally

```bash
bundle exec jekyll serve
```

### 3. Open in browser

Because `_config.yml` sets `baseurl: /ReminderTextWebsite`, open:

- `http://127.0.0.1:4000/ReminderTextWebsite/`

## Build

```bash
bundle exec jekyll build
```

This writes the generated site to `_site/`.

## Content Structure

- Home page: `index.md`
- Blog index: `blog/index.md`
- Blog posts: `_posts/`
- Shared layouts: `_layouts/`
- Shared partials: `_includes/`
- Styles: `assets/css/main.css`
- Legal/support pages: root `*.md` documents (for stable URLs)
