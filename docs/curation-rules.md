# Curation rules

Rules for anyone (human or agent) adding links to a topic `README.md`.

## Sourcing

- Every URL must come from a source you actually saw (search result, page, repo). Never construct or guess a URL.
- Prefer, in order: official Microsoft Learn docs, official Microsoft GitHub repos (`microsoft/*`, `Azure/*`, `Azure-Samples/*`), Microsoft blogs (devblogs.microsoft.com/foundry, techcommunity.microsoft.com), Microsoft Learn Training and Microsoft videos, then community content.
- Community content must be useful and specific. Skip paywalled posts, thin summaries and SEO pages.
- If you cannot find a good source for a section, leave it empty. An empty section is better than a weak link.

## URL hygiene

- Remove locale segments (`/en-us/`, `/en-gb/`, `/ar-sa/`) from learn.microsoft.com URLs.
- Remove tracking parameters (`WT.mc_id`, `utm_*`, `pivots=` unless the page needs it).
- Do not link mirrors or scrapers (for example copies of Learn pages on other domains).
- Link the canonical page, not a redirect.

## Entry format

`- [Title](url) - One-line description.`

- The title is the page title, not marketing copy.
- The description says what the reader gets, in one sentence, starting with a capital and ending with a period.
- Add `(preview)` or `(deprecated)` after the title only when the source says so. Foundry features change status often, so do not assume.
- Entries are alphabetical by title within a section.

## Placement

- Each link has one primary topic. Put it where a reader looking for that subject would look first.
- If a link also matters to another topic, add it there only when it is directly about that topic, and keep the description specific to that topic.
- Use `docs/topic-map.md` to resolve overlaps.
- Remove the `<!-- Add links ... -->` comment and the "Status: structure only" note from a topic once it has links.
