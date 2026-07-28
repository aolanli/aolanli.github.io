# AGENTS.md

## Scope

This directory is the local working copy of
`https://github.com/aolanli/aolanli.github.io`. Website code and assets belong
here.

## Repository profile

- Remote: `https://github.com/aolanli/aolanli.github.io.git`
- Default branch: `main`
- Hosting: GitHub Pages
- Generator/theme: Jekyll with the `minima` theme
- Configuration: `_config.yml`
- Main content: `index.md`, `research.md`, `publications.md`, and `contact.md`
- CV viewer: `cv.html`
- Website CV source: `Aolan_Li_CV.tex`
- Embedded website CV: `Aolan_Li_CV.pdf`

Use the pinned dependencies in `Gemfile` and `Gemfile.lock` for local builds.
Do not treat rendering as validated until `bundle exec jekyll build` succeeds.

## Facts and content

- Use `../profile/` as the canonical shared professional record.
- Treat the live website as an output that may be stale.
- Do not promote publication status without the evidence required by the root
  `AGENTS.md`.
- Never publish a phone number anywhere on the website, including HTML,
  Markdown, metadata, structured data, embedded documents, and downloadable
  CV PDFs.
- Never publish manuscripts in preparation on the Publications page or in an
  embedded or downloadable website CV. This rule does not automatically
  exclude verified preprints, submitted or under-review manuscripts, accepted
  articles, or articles in press.
- Keep private application logistics and immigration details off the website.

## Repository and deployment

- Preserve the existing Git history, branches, framework, and deployment
  configuration when the repository is connected.
- Discover the actual install, build, test, preview, and deployment commands
  from repository files before running them.
- Keep generated dependencies and build output uncommitted unless the existing
  repository intentionally tracks them.
- Do not commit, push, open a pull request, change repository settings, or
  deploy without an explicit user request.
- Never store credentials or tokens in repository files.

## Quality checks

For website changes, validate:

- local build success;
- desktop and mobile rendering;
- navigation and external links;
- accessibility basics and meaningful link text;
- publication status against `../profile/publications.yaml`; and
- downloadable CV links and file freshness.
