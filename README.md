# Sumedhaa’s portfolio

This site is built with Hugo using a customized copy of the `charlolamode` theme. The pages and styles are in this repository; no separate frontend toolchain is required.

## Edit the site

- `data/profile.yml` — name, email address, and homepage social links.
- `data/home.yml` — homepage text, experience highlights, writing cards, and newsletter note.
- `data/navigation.yml` — visible navigation links.
- `data/travel.yml` — travel journal categories. Each travel post’s `travelCategory` must exactly match a category title here.
- `data/resume.yml` — résumé roles, skills, certifications, education, recognition, and volunteering.
- `content/resume/_index.md` — résumé page title, introduction, and PDF link.
- `content/about/_index.md` — About page text and search description.
- `content/blog/_index.md` — blog title and introduction.
- `content/blog/` and `content/travel/` — individual articles. Set `draft: false` when a post is ready to publish.
- `data/home.yml` → `newsletter.url` — add a Substack URL when subscriptions are ready; the placeholder automatically becomes a subscription link.
- `assets/css/extended/portfolio.css` — visual design, layout, responsive rules, and motion.
- `layouts/` — page structure and reusable visual components. Page copy should usually be changed in `data/` or `content/`, rather than in a template.
- `config.yml` — site URL, title, theme, and Hugo-wide options.

If you change the site’s name, update both `data/profile.yml` and `config.yml` (`title`).

## Add a post

Create a blog post:

```sh
hugo new content/blog/my-post.md
```

Create a travel post:

```sh
hugo new content/travel/my-trip.md
```

The travel archetype starts with `Within India`; change `travelCategory` to `International Trips` for an overseas trip. Posts are drafts by default. Add photos to `static/images/` and refer to them as `/images/your-photo.jpg` in Markdown.

## Preview locally

Install the Hugo version listed in `.github/workflows/hugo.yaml`, then run:

```sh
hugo server -D
```

Open the local address printed by Hugo. The `-D` flag includes drafts in the preview. GitHub Actions builds and deploys the `hugo` branch to GitHub Pages.

## Design notes

The custom styles extend the bundled theme. Botanical SVGs are hand-authored in `layouts/partials/`; their colors and motion live in `assets/css/extended/portfolio.css`. Motion has a reduced-motion override, and travel-card hydrangeas are decorative SVGs rendered by `layouts/partials/hydrangea-edge.html`.
