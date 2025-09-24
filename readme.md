## Mohamed's Portfolio

A simple, single‑page personal portfolio built with plain HTML. It showcases a brief intro, about section with an audio clip, a projects list, a resume table, and a contact form UI.

### Features

- **Single HTML file**: Easy to read and modify (`myportfolio.html`).
- **Navigation**: Jump links to Home, About, Work, Resume, and Contact.
- **Audio intro**: Plays `intro.mp3` in the About section.
- **Projects list**: Quick snapshot of work items.
- **Resume table**: Compact timeline of roles and companies.
- **Contact form UI**: Inputs for name, email, and message (no backend).

### File structure

```
myportfolio/
  ├─ myportfolio.html   # main page
  ├─ intro.mp3          # audio used in About section
  └─ readme.md          # this file
```

### Getting started (local)

- Double‑click `myportfolio.html` to open it in your browser, or
- Serve it with a lightweight dev server (optional):
  - VS Code: install Live Server → right‑click `myportfolio.html` → "Open with Live Server".

### Deploying (GitHub Pages)

1. Create a new repo and push this folder.
2. In GitHub → Settings → Pages → set **Branch** to `main` (or `master`) and **Folder** to `/root`.
3. Save. Your site will be available at a URL like `https://<username>.github.io/<repo>/myportfolio.html`.
   - To make it the default page, rename `myportfolio.html` to `index.html` at the repo root.

### Customization

- **Title & header**: Update the `<title>` and the `<h1>` in the header.
- **Welcome blurb**: Edit the text in the `#home` section.
- **About & audio**: Replace `intro.mp3` (keep the same filename or update the `<source>` path).
- **Projects**: Modify the list under `#work`.
- **Resume**: Add rows to the table in `#resume` (Year, Position, Company).
- **Contact form**: The form is static. To make it functional, connect it to a backend or a service (e.g., Formspree, Netlify Forms) and update the `action`/`method` accordingly.

### Notes

- No external CSS or JS included; styles rely on browser defaults. Add your own CSS/JS as needed.
- The form currently posts to `#` and will not send messages without a backend/service.
- Footer credits: `© 2025 Mohamed Hussein` (update as needed).

### License

Personal project; no explicit license provided. Add a license if you plan to open‑source.
