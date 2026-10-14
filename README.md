---
version: 0.1
---

# dusanjovanovic.org

Online CV of Dusan B. Jovanovic, published at https://dusanjovanovic.org

## Hosting

- **Source**: https://github.com/DBJDBJ/dusanjovanovic_org (branch `master`)
- **Build and hosting**: GitHub Pages. Every push to `master` runs [.github/workflows/hugo.yml](.github/workflows/hugo.yml), which builds the [Hugo](#vocabulary) site and publishes it
- **Custom domain**: set by [static/CNAME](static/CNAME) and in the repo's Settings → Pages
- **Domain registrar and DNS**: [name.com](https://www.name.com) — the domain is paid for there and its DNS records live there:
  - `A` records for `dusanjovanovic.org` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153` (GitHub Pages)
  - `CNAME` for `www` → `dbjdbj.github.io`
  - Renewal due every year by 18 October

## History

- 2019–2026: hosted on Netlify (project `dbjdeprecated`, formerly `dbj`), source on GitLab `dbjdbj/online`
- 2026-10-14: moved to GitHub Pages; DNS moved from Netlify to name.com

## Vocabulary

- **Hugo**: static site generator; theme is Academic, kept in `themes/academic`. https://gohugo.io
- **GitHub Pages**: GitHub's static hosting. https://docs.github.com/pages

---

Released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.

### &copy; 1999-present [![dbj();](http://dbj.org/wp-content/uploads/2015/12/cropped-dbj-icon-e1486129719897.jpg)](http://www.dbj.org "dbj") [Dusan B. Jovanovic](https://dbj.org)
