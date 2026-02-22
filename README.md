# Michael Black - Personal Website

A minimal, fast-loading personal portfolio website built with vanilla HTML, Tailwind CSS, and minimal JavaScript.

## Tech Stack

- **HTML5**
- **Tailwind CSS v4**
- **Vanilla JavaScript**
- **GitHub Pages**

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

### Watch Mode

For active development with auto-rebuild:

```bash
./tailwindcss -i ./src/input.css -o ./css/output.css --watch
```

Keep this running in a terminal while editing. Changes to `src/input.css` or `index.html` will automatically rebuild the CSS.

### Local Server

```bash
python3 -m http.server 8080
```

