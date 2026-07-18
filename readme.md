<!-- PORTFOLIO-BANNER:START -->
> **🗂️ Portfolio archive — static website / blog (Hugo).** The Codifice.uk personal site and blog. Part of a consolidated set of my personal repositories and **not actively maintained** (dormant since 2020).

<details>
<summary><b>📋 Self-review — 5 good practices &amp; 5 things I'd improve</b></summary>

**✅ Good practices demonstrated**
1. A proper static-site-generator structure — content, layouts, archetypes and data directories.
2. Netlify CI/CD with a deploy-status badge.
3. Theme managed as a git submodule (reuse rather than a vendored copy).
4. A clear purpose statement for the personal brand.
5. Devcontainer and VS Code config for reproducible authoring.

**⚠️ Weaknesses / what I'd do differently today**
1. Dormant since 2020 — a stale personal site.
2. Large repository (100 MB+) from committed build assets (`resources` / `static`).
3. The submodule theme dependency can break clones if the upstream moves.
4. The Netlify deployment/badge is likely dead now.
5. Relatively thin published content compared with the surrounding scaffolding.

</details>

---
<!-- PORTFOLIO-BANNER:END -->


# Codifice Blog

[![Netlify Status](https://api.netlify.com/api/v1/badges/3fc53a50-e7b6-4516-ba10-f70a868790bb/deploy-status)](https://app.netlify.com/sites/codifice/deploys)

The initial Codifice.uk blog site, a new Hugo powered static site intended to promote myself as a flexible Full Stack Developer and to host my blog posts.

This will replace [MartinOnDotNet](http://martinondotnet.blogspot.com/) and will act as the public face of the Codifice Organisation which brings together most of my side projects under a single GitHub Organisation from a disperate of legacy GitHub accounts.

## The Blog
The blog itself is [Hugo](https://gohugo.io/) powered and hosted by [Netlify](https://www.netlify.com/) with blog post comments being provided by [utteranc.es](https://utteranc.es).  I've customised the [Minimo](https://themes.gohugo.io/minimo/) to suite my tastes and leveraged royalty free images from [Pexels](https://www.pexels.com/) and [pixabay](https://pixabay.com/) for post thumbnails and cover images.