# foggy-labs.github.io

Foggy Labs app landing pages, privacy policies, and terms of service. Hosted via GitHub Pages.

## Live URLs

- **Homepage:** https://foggy-labs.github.io
- **StudioNow Privacy:** https://foggy-labs.github.io/privacy/studionow/
- **StudioNow Terms:** https://foggy-labs.github.io/terms/studionow/
- **StudioNow Support:** https://foggy-labs.github.io/support/studionow/

## Adding a New App

For each new app, create three directories and copy from templates:

```bash
APP_SLUG=myapp

mkdir -p privacy/$APP_SLUG terms/$APP_SLUG support/$APP_SLUG

cp _templates/privacy-template.md privacy/$APP_SLUG/index.md
cp _templates/terms-template.md terms/$APP_SLUG/index.md

# Edit the files — replace APP_NAME, APP_DATE, APP_DESCRIPTION, etc.
# Then commit and push:
git add .
git commit -m "Add legal pages for $APP_SLUG"
git push
```

GitHub Pages auto-deploys within ~60 seconds.

## URL Pattern

| Page | URL |
|------|-----|
| Privacy Policy | `https://foggy-labs.github.io/privacy/[app-slug]/` |
| Terms of Service | `https://foggy-labs.github.io/terms/[app-slug]/` |
| Support | `https://foggy-labs.github.io/support/[app-slug]/` |

## For Paperclip Agents

The Senior iOS Developer agent should create legal pages for each new app as part of the build process. Use the templates in `_templates/` and push to this repo.
