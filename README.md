# Nyota Nne Interventions Website

## Structure

- `index.html` — Homepage
- `about.html` — About page
- `services.html` — Services page
- `support.html` — Who We Support page
- `resources.html` — Resources & Insights page
- `partnerships.html` — Partnerships page
- `team.html` — Team page
- `contact.html` — Contact page
- `css/styles.css` — Shared styles
- `js/main.js` — Shared navigation and partial loading
- `partials/header.html` — Shared header
- `partials/footer.html` — Shared footer
- `assets/` — Images and other assets

## Important

1. Replace `assets/logo-new.jpeg` with the actual logo file.
2. Add real team photos as `team-member-1.jpg` and `team-member-2.jpg`.
3. Replace the placeholder Formspree endpoint in `contact.html`.
4. Replace placeholder team names, roles, qualifications and biographies with verified information.
5. Add only verified social media links.
6. The shared header/footer use `fetch()`, so test using a local development server rather than opening the HTML file directly with `file://`.

## Running locally

If using VS Code, use Live Server. Alternatively:

```bash
python -m http.server 8000
```

Then open:

`http://localhost:8000`
