# Contributing

## Adding a link

1. Find the topic folder under `topics/<category>/<topic>/`.
2. Add the link to the matching section of that topic's `README.md`:
   `- [Title](https://example.com) - One-line description.`
3. Prefer official and primary sources.
4. Tag the status of a feature in the title or description when it is not generally available: `(preview)` or `(deprecated)`.
5. Keep entries alphabetical within a section, and avoid duplicates.
6. Descriptions start with a capital letter and end with a period.

## Checks

Pull requests run two checks:

- **Lint**: markdownlint on all Markdown files (`.markdownlint-cli2.jsonc`).
- **Links**: lychee checks every URL (`lychee.toml`). It also runs weekly and opens an issue when links break.

Run them locally with `npx markdownlint-cli2 "**/*.md"` and `lychee --config lychee.toml './**/*.md'`.

## Adding a topic

Create `topics/<category>/<topic>/README.md` using an existing topic as the template, then list it in the root `README.md`.

## Adding a guide

Put it at `topics/<category>/<topic>/guide.md` and link it from the topic's `Guide` section.
