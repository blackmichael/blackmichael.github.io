# Michael Black - Personal Website

A minimal, fast-loading personal portfolio website built with vanilla HTML, Tailwind CSS, and minimal JavaScript.

## Tech Stack

- **HTML5** - Semantic, accessible markup
- **Tailwind CSS v4** - Utility-first styling via Standalone CLI
- **Vanilla JavaScript** - Minimal (~50 lines) for smooth scrolling and animations
- **GitHub Pages** - Free, reliable hosting

## Development

Install the [tailwindcss CLI](https://tailwindcss.com/docs/installation/tailwind-cli).

### Style Changes (Requires CSS Rebuild)

1. Edit `src/input.css` or `tailwind.config.js`
2. Rebuild CSS:
   ```bash
   ./tailwindcss -i ./src/input.css -o ./css/output.css --minify
   ```
3. Commit both source and output:
   ```bash
   git add src/input.css css/output.css
   git commit -m "Update styles"
   git push
   ```

### Watch Mode (Development)

For active development with auto-rebuild:

```bash
./tailwindcss -i ./src/input.css -o ./css/output.css --watch
```

Keep this running in a terminal while editing. Changes to `src/input.css` or `index.html` will automatically rebuild the CSS.

### Local Server
For a more production-like environment:

```bash
python3 -m http.server 8080
```

