# Legal Hub

Static GitHub Pages site hosting privacy policies for my mobile apps.

## Structure

```
index.html              Developer landing page (lists all apps)
_template/privacy.html  Reusable privacy-policy template
<app-slug>/privacy.html One folder per app
.nojekyll               Serve files as-is (no Jekyll processing)
```

## Add a new app

1. Copy `_template/privacy.html` to `<app-slug>/privacy.html`.
2. Replace `{{APP_NAME}}`, `{{EFFECTIVE_DATE}}`, `{{CONTACT_EMAIL}}`.
3. Add a link to the new page in `index.html`.
4. Commit & push. The URL is live within ~1 minute.

## Live URLs

Once published via GitHub Pages (repo `<USERNAME>.github.io`, branch `main`):

- Landing: `https://<USERNAME>.github.io/`
- PayoffPlan: `https://<USERNAME>.github.io/payoffplan/privacy.html`
