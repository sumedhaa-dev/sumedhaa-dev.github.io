# Portfolio improvement backlog

A practical backlog for improving the site one task at a time. Work from the top of a section, or pick any item that interests you. Keep this file as the source of truth: check off an item when it is live and its “Done when” condition is met.

## 1. Make the site ready to share

- [ ] **P1 · Verify the public profile copy.** Review the homepage, About page, résumé, and site description together for accuracy, consistent tone, and claims that are safe to share publicly. **Done when:** the same role, dates, location, and areas of focus appear consistently everywhere.
- [ ] **P1 · Verify current work details.** Check role titles, dates, company names, and project summaries in `data/home.yml` and `content/resume/_index.md`. **Done when:** every public statement is current and approved for disclosure.
- [ ] **P1 · Publish a stable résumé PDF.** Replace the Drive link with a versioned PDF in the repository or another stable public URL, and check it from a signed-out browser. **Done when:** the résumé link downloads or opens without requesting access.
- [ ] **P1 · Review résumé details.** Confirm certification names and dates, education, award wording, contact details, and PDF text match the page. **Done when:** page and PDF agree and the PDF is readable on mobile and when printed.
- [ ] **P1 · Replace travel placeholders.** Write the actual story for each trip in `content/travel/`; remove “I’ll add…” copy before publishing. **Done when:** every published card leads to a finished story, or the unfinished entry remains a draft.
- [ ] **P1 · Unpublish unfinished travel entries.** Set `draft: true` on posts that still contain placeholder copy until their stories are ready. **Done when:** the live journal no longer presents “I’ll add…” text as a finished post.
- [ ] **P1 · Add useful dates and context to travel entries.** Add trip dates (or year/season if exact dates are private), destinations, and a concise summary to each post’s front matter. **Done when:** a visitor can tell when and where each story happened.
- [ ] **P1 · Review blog posts.** Expand the Terraform and AWS certification notes into useful articles, or keep them as drafts until they are ready. **Done when:** each published post has a clear purpose, accurate guidance, and a final proofread.
- [ ] **P1 · Check every visible link.** Review navigation, résumé, social accounts, email, Substack, blog cards, travel cards, and footer attribution. **Done when:** each link reaches the intended destination and external links behave consistently.

## 2. Show the work clearly

- [ ] **P1 · Add a selected work section.** Create two or three concise engineering case studies that can be shared publicly. **Done when:** each case study explains the problem, your role, key design decisions, and outcome without exposing confidential information.
- [ ] **P1 · Add one case study at a time.** Start with a data pipeline, a cloud/platform improvement, or an AI/data discovery workflow. **Done when:** the write-up explains the tradeoffs and measurable impact in plain language.
- [ ] **P2 · Add simple architecture diagrams.** Draw only the components needed to explain a case study. **Done when:** each diagram has readable labels, a text description, and works on a phone-sized screen.
- [ ] **P2 · Add a “how I work” note.** Describe how you approach reliability, operability, and tradeoffs with one specific example. **Done when:** it adds a personal perspective instead of repeating the skills list.
- [ ] **P2 · Decide how to share dance writing.** Try a short dance-journey page or post before adding a new top-level section. **Done when:** the topic feels like a natural part of the site and has enough writing to support its own page.

## 3. Make the travel journal memorable

- [ ] **P1 · Finish the solo US trip story.** Include the AWS All Builders Welcome Grant and re:Invent experience in your own voice. **Done when:** the story gives readers a sense of the journey, not only the itinerary.
- [ ] **P1 · Finish the Tromsø story.** Add the northern-lights experience, what the trip felt like, and any practical details you want to share. **Done when:** the post has a clear beginning, a few specific moments, and an ending.
- [ ] **P2 · Finish the Singapore and Malaysia stories.** Give each trip its own perspective and avoid making them generic destination summaries. **Done when:** a reader can tell what was distinctive about each visit.
- [ ] **P2 · Finish the India stories.** Add the Jaisalmer, Goa birthday, and Ujjain Diwali stories. **Done when:** each entry reflects the experience you actually want to remember.
- [ ] **P2 · Add a small set of travel photos.** Choose a few strong photos per post instead of adding every photo. **Done when:** images support the story, have useful alt text, and load quickly.
- [ ] **P2 · Create a consistent photo treatment.** Decide on image ratios, captions, spacing, and how photos appear on dark mode. **Done when:** travel stories feel cohesive without forcing different photos into awkward crops.
- [ ] **P3 · Add travel details as structured metadata.** Consider year, country/state, trip length, and travel type in front matter. **Done when:** these details can be reused for cards and filters without hand-editing templates.
- [ ] **P3 · Add destination filters or search.** Build this only after enough finished posts exist to make it useful. **Done when:** visitors can find a place or trip type quickly, including by keyboard.
- [ ] **P3 · Consider a travel map.** Add a light, accessible map only if it helps visitors explore the journal. **Done when:** every location has a text equivalent and the map works without a third-party tracking service.

## 4. Polish the visual experience

- [ ] **P1 · Review the homepage at common viewport sizes.** Check a narrow phone, a large phone, a laptop, and a wide desktop. **Done when:** the first screen introduces you clearly and the next section begins naturally on scroll.
- [ ] **P1 · Refine homepage spacing page by page.** Check the hero, story, work timeline, writing cards, newsletter, and footer for balanced line lengths and breathing room. **Done when:** spacing feels intentional on both short and tall screens, without large accidental gaps.
- [ ] **P1 · Review line wrapping.** Check paragraphs, headings, social links, buttons, and long job titles on narrow screens. **Done when:** ordinary words stay intact and no text clips or forces horizontal scrolling.
- [ ] **P2 · Set a consistent type scale.** Define a small set of heading, body, caption, and eyebrow sizes and use them consistently. **Done when:** page hierarchy is clear without relying on many one-off font sizes.
- [ ] **P2 · Review botanical artwork at real page sizes.** Check dividers, home side blooms, newsletter branches, and travel hydrangeas against the actual text and cards. **Done when:** each illustration is decorative, balanced, and never competes with content.
- [ ] **P2 · Tune both color themes.** Review text, links, cards, borders, floral details, and the newsletter section in light and dark mode. **Done when:** text remains readable and accent colors feel related in both themes.
- [ ] **P2 · Make animation restrained and consistent.** Keep the branch and divider movement subtle and respect reduced-motion preferences. **Done when:** motion does not distract, shift layout, or make the page uncomfortable.
- [ ] **P2 · Add a clear active navigation state.** Show which main section the visitor is viewing. **Done when:** the active page is identifiable visually and to assistive technology.
- [ ] **P3 · Refine the wordmark and favicon.** Decide whether the initial-letter mark is the desired identity and provide matching light/dark browser-tab artwork if useful. **Done when:** the mark is legible at small sizes and matches the site’s tone.

## 5. Help visitors find and follow content

- [ ] **P2 · Verify RSS feeds.** Confirm Hugo emits feeds for the blog and travel journal and add visible feed links if useful. **Done when:** a feed reader can subscribe and new posts appear in the expected feed.
- [ ] **P2 · Add article dates and reading time.** Show metadata consistently on blog and travel posts. **Done when:** dates are accurate, optional dates do not render blank, and reading time is a useful estimate.
- [ ] **P2 · Add a contents list for long articles.** Only show it when an article has enough headings to benefit. **Done when:** contents links work, are keyboard-accessible, and do not crowd short posts.
- [ ] **P3 · Add related posts.** Suggest a small number of relevant articles at the end of a post. **Done when:** suggestions are genuinely related and never link to drafts.
- [ ] **P3 · Add search.** Start with the blog and travel journal, then extend it if visitors need it. **Done when:** search results show readable titles and summaries and no draft or private content.
- [ ] **P3 · Add social preview images.** Set a site-wide Open Graph image and allow important posts to specify their own. **Done when:** shared links have a clear image, title, and description.
- [ ] **P3 · Add a custom not-found page.** Provide a useful way back to Home, Blog, and Travel. **Done when:** a made-up URL produces a branded 404 page with working links.

## 6. Accessibility, speed, and trust

- [ ] **P1 · Keyboard-test the whole site.** Use Tab, Shift+Tab, Enter, and Escape where relevant. **Done when:** every link and control has a visible focus state and a sensible order.
- [ ] **P1 · Check screen-reader structure.** Review heading order, landmarks, button names, decorative SVG labels, and link purpose. **Done when:** important content is understandable without visual styling.
- [ ] **P2 · Check color contrast.** Verify body text, muted metadata, links, focus rings, and botanical details in both themes. **Done when:** essential text and controls remain distinguishable.
- [ ] **P2 · Add meaningful image descriptions.** Use descriptive alt text for story photos and empty alt text for purely decorative images. **Done when:** no meaningful image relies on its filename or surrounding text to make sense.
- [ ] **P2 · Optimize travel photos.** Resize large originals, use modern formats where practical, and lazy-load below-the-fold images. **Done when:** image quality remains good and pages load smoothly on mobile connections.
- [ ] **P2 · Check responsive zoom and reflow.** Test at 200% zoom and at a narrow viewport. **Done when:** content remains usable without sideways scrolling, except where a genuinely wide diagram needs it.
- [ ] **P2 · Keep external services intentional.** Review Google Fonts, Substack, and any future maps, analytics, or forms. **Done when:** each service has a clear purpose and the site still works if it is unavailable.
- [ ] **P3 · Add privacy-friendly analytics only if needed.** Decide what question analytics should answer before installing anything. **Done when:** tracking is documented, minimal, and disclosed appropriately.

## 7. Keep the Hugo project easy to maintain

- [ ] **P1 · Keep Hugo versions aligned.** Match the version used locally to `.github/workflows/hugo.yaml`. **Done when:** a local production build and the GitHub Actions build use the same Hugo release.
- [ ] **P1 · Add a local build check to the editing routine.** Build to a temporary destination before publishing significant layout or content changes. **Done when:** broken templates, missing assets, and bad links are caught before deployment.
- [ ] **P1 · Confirm deployment branch and Pages settings.** The current workflow publishes pushes to `hugo`. **Done when:** GitHub Pages is configured to use the workflow artifact and the expected repository/branch.
- [ ] **P2 · Add automated checks to GitHub Actions.** Check Hugo build output and optionally verify internal links. **Done when:** a failed build or broken internal route prevents an unnoticed deployment.
- [ ] **P2 · Review and consolidate CSS.** Remove obsolete selectors and repeated overrides, then group styles by component. **Done when:** each component has one clear source of truth and existing page layouts still match.
- [ ] **P2 · Extract repeated template markup.** Use partials for repeated post cards, metadata, and shared decorative components where that improves readability. **Done when:** a visual change can be made once without duplicating markup.
- [ ] **P2 · Make content front matter consistent.** Document fields for blog and travel posts in the archetypes. **Done when:** a new post starts with the right title, date, summary, category, image fields, and draft state.
- [ ] **P2 · Keep the README current.** Update it when paths, commands, deployment, or content workflows change. **Done when:** you can add a post and preview the site using only the README.
- [ ] **P2 · Remove stale starter content and assets.** Check whether `data/quote.json`, `layouts/shortcodes/quotes.html`, and theme demo images are used before removing or replacing them. **Done when:** every retained file has a clear purpose and no old sample quote or theme image appears on the site.
- [ ] **P3 · Add a short publishing checklist.** Include spelling, links, images/alt text, front matter, preview, and deployment status. **Done when:** publishing a post is repeatable and takes only a few minutes to review.

## Suggested first five

1. Verify current profile and experience details.
2. Publish a stable résumé PDF and confirm access.
3. Replace placeholder copy in one travel post you most want to share.
4. Expand one technical blog post into a useful, finished article.
5. Add one privacy-safe engineering case study.

## Working rule

Choose one unchecked task, finish it, preview the result, then mark it complete. Avoid adding a new feature until the existing pages and content that support it are ready.
