# alirezahashemi.com

Personal site, built with Jekyll and served by GitHub Pages.

## Editing

- **Experience, publications, background, projects:** `_data/*.yml`
- **CV PDF:** replace `files/Alireza_Hashemi_CV.pdf`
- **Header links:** `links` in `_config.yml`

## Writing and projects

- **Blog post:** add `_posts/YYYY-MM-DD-slug.md` with `title` and optional `description` in the front matter. Drafts go in `_drafts/`. The "writing" nav link appears once there is a post.
- **Project:** add an entry to `_data/projects.yml`. Each one shows up in the "projects" menu in the top bar.

## Running locally

```bash
bundle install
bundle exec jekyll serve --livereload
```
