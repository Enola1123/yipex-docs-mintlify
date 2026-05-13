# Editing Guide

## Recommended editor for non-technical edits

Use Pages CMS:

https://app.pagescms.org/

Sign in with GitHub, select `voidtechai/yipex-docs-mintlify`, then edit pages from the CMS.

Pages CMS writes changes back to GitHub. Mintlify then deploys the latest `main` branch automatically.

## Daily editing rules

- Edit `总页面` for the sidebar home page.
- Keep `index.mdx`; it is used for the direct `/docs` address.
- Edit existing pages under `PC端页面` or `APP端页面`.
- Upload new screenshots into `images/`.
- Keep image links as `/images/...`.
- Do not rename, delete, or create pages in Pages CMS.
- Do not edit `docs.json` unless you are changing the sidebar.

## When GitHub editing is still needed

Use GitHub directly only for structural changes:

- adding a new page
- deleting a page
- changing the sidebar order
- changing `docs.json`
- changing Mintlify config
