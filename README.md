# riegan.dev content

Editable content repository for `riegan.dev`.

The website consumes this repository as a Git submodule at `content/`.

## Structure

```txt
site/
  en.json
  id.json
blog/
  en/
  id/
projects/
  projects.json
awards/
  awards.json
gallery/
  gallery.json
  images/
assets/
  profile/
  og/
```

Published blog posts use Markdown with frontmatter. Projects, awards, gallery entries, and localized site copy use JSON so the static site can validate them during build.
