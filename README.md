# Meridian Urban Mobility Lab — publication site

A small Jekyll site that lists the lab's publications. The live site is built from
this repository, so everything here is public.

## Layout

- `_papers/` — one Markdown entry per publication. The file name (without `.md`) is
  the site key used in links and in analytics.
- `_includes/paper-card.html` — shared card template. It renders a "Code" button
  when an entry's front matter contains `projecturl`.
- `index.md`, `_config.yml` — landing page and site configuration.

## Editing conventions

Paper entries are edited by hand; generated files are not. A content sync touches
only the files under `_papers/`. Front matter fields used by the template are
`layout`, `title`, `venue`, `status`, `year`, `authors`, `paperurl`, `citation`
and, when the code is public, `projecturl`.
