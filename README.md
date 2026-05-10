# TECH CRUSH

A polished single-page Learning Management System landing page for TECH CRUSH.

## What is included

- `index.html` — the main website with a professional blue aesthetic
- `styles.css` — responsive styling for desktop and mobile
- `README.md` — project overview and local preview instructions

## Trending course categories showcased

- Frontend Development
- Backend Engineering
- Cloud & DevOps
- Content Creator Growth

## Preview locally

1. Open `index.html` directly in your browser, or
2. Run a local server from the project folder:

```bash
cd /home/pc/CI_CD_test
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000` in your browser.

## Hosting on GitHub Pages

1. Create a new repository on GitHub (e.g., `CI_CD_test`)
2. Push your code:
   ```bash
   git remote add origin https://github.com/yourusername/CI_CD_test.git
   git push -u origin main
   ```
3. In your GitHub repo settings, go to Pages and select "GitHub Actions" as the source
4. On every push to `main`, the site will automatically deploy to `https://yourusername.github.io/CI_CD_test/`

## CI/CD

- Uses GitHub Actions for automatic deployment on pushes to `main`
- No build step needed since it's static HTML/CSS
- Supports pull request previews
