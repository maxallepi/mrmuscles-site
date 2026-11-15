# mrmuscles-site

Public developer website for **Mr.Muscles Inc.** — independent Android game studio.

Static HTML + one stylesheet. No build step, no JavaScript, no external requests.
Deploys straight to GitHub Pages (same setup as `chickenflap-site`).

## Structure

```
index.html          studio home: hero, what we make, games, next up, contact
about/index.html    studio story
support/index.html  support, data-deletion instructions, policy links
404.html
assets/             style.css, icons, store screenshots (webp)
```

## Editing

Copy lives inline in the HTML. All internal links are **relative** so the site works
both on `user.github.io/repo/` and on a custom domain at the root.

## TODO when a custom domain lands

1. Add `CNAME` with the domain.
2. Add a canonical `<link>` plus `og:image` / `og:url` absolute URLs to each page head.
3. Re-add `sitemap.xml` and the `Sitemap:` line in `robots.txt`.
4. Swap the contact address from `support@chickenflap.win` to the studio address.
