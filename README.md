# Jingying Wang Hugo Site Starter

A simple, modern academic personal website built with Hugo.

## 1) Install Hugo

On macOS with Homebrew:

```bash
brew install hugo
hugo version
```

## 2) Preview locally

From this folder:

```bash
hugo server -D
```

Open the local address shown in Terminal, usually:

```text
http://localhost:1313/
```

## 3) Replace the CV placeholder

Put your own PDF here and keep the filename:

```text
static/files/Jingying_Wang_CV.pdf
```

## 4) Add your GitHub link later

Open `hugo.toml` and replace:

```toml
github = '# add-your-github-link-here'
```

## 5) Build the site

```bash
hugo
```

The built site will be in the `public/` folder.

## 6) Deploy

You can deploy the project with Netlify or GitHub Pages.

## Useful files to edit

- `hugo.toml` → site-wide settings
- `content/_index.md` → homepage intro
- `content/about.md` → About page
- `content/cv.md` → CV page
- `content/publications.md` → Publications page
- `content/posts/` → blog posts
- `static/css/style.css` → styling
