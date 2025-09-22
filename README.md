# Personal Website (Hugo + blogdown) Repo README

This repository contains the source code for my personal website and blog.
It’s built with **[Hugo (extended)](https://gohugo.io/)**, authored primarily with **R Markdown (blogdown)**, and themed with a customized fork of **gurusabarish/hugo-profile**. I’ve added several sections and quality-of-life features (courses, enroll form with payments, publications, achievements, etc.).

**Website:** <https://mdahsanulhimel.github.io>

---

## Quick start

### Prerequisites

* **Hugo extended** (v0.115+ recommended)
* Optional (for Rmd authoring): **R** + **blogdown** package
* Node is **not** required

## Project structure

```
.
├─ content/                # pages, posts (Rmd/markdown)
│  ├─ post/                # blog posts (leaf bundles recommended)
│  │   └─ my-post/
│  │      ├─ index.Rmd
│  │      └─ images/...
│  ├─ courses/             # course pages (optional)
│  └─ enroll/              # enroll pages using `layout: "enroll"`
├─ layouts/                # custom templates & partials
│  ├─ _default/
│  │   ├─ list.html        # posts list (custom card layout + reading time)
│  │   └─ single.html      # article page (featured image, top-TOC on mobile)
│  ├─ partials/
│  │   ├─ sections/
│  │   │   ├─ hero/
│  │   │   │   ├─ index.html
│  │   │   │   └─ social.html
│  │   │   ├─ courses.html
│  │   │   ├─ achievements.html
│  │   │   ├─ publications.html
│  │   │   └─ ...
│  └─ _default/enroll.html # form page with payments (Formspree-ready)
├─ assets/ | static/       # css, images, pdf, QR codes, etc.
├─ config/_default/        # hugo config files (params live here)
└─ themes/hugo-profile/    # theme (tracked or referenced as submodule)
```

---

## Credits & License

* Theme base: **gurusabarish/hugo-profile**
* Icons: **Font Awesome**
* Built with **Hugo** and **blogdown**
* Content © Me. Theme and code customizations are MIT unless noted otherwise. See `LICENSE`.

