# GitHub Copilot Instructions for nimashoghi.github.io

This repository hosts a personal academic website built with **Jekyll**, based on the [academicpages](https://github.com/academicpages/academicpages.github.io) template (a fork of [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)).

## Architecture & Structure

- **Static Site Generator**: Jekyll (Ruby).
- **Templating**: Liquid.
- **Styling**: SCSS in `_sass/`, compiled to CSS.
- **Content**:
    - **Pages**: `_pages/` (Markdown/HTML).
    - **Publications**: `_publications/` (Markdown with specific front matter).
    - **Talks**: `_talks/` (Markdown).
    - **Posts**: `_posts/` (Blog posts, if any).
    - **Data**: `_data/` contains site-wide data like navigation (`navigation.yml`) and UI text.
- **Layouts**: `_layouts/` defines the HTML structure for different page types (e.g., `single.html`, `archive.html`, `talk.html`).
- **Includes**: `_includes/` contains reusable components (e.g., `sidebar.html`, `analytics.html`).

## Critical Workflows

### Local Development

To preview the site locally with auto-reload:

```bash
bundle exec jekyll serve
# OR
bundle exec jekyll liveserve
```

_Note: Ensure `Gemfile.lock` is consistent with your Ruby version. If errors occur, delete `Gemfile.lock` and run `bundle install`._

### Managing Content

- **New Publication**: Create a `.md` file in `_publications/`.
    - **Required Front Matter**: `title`, `collection: publications`, `permalink`, `date`, `venue`, `paperurl`, `citation`.
    - **Example**: See `_publications/2019-Slam-performance-on-embedded-robots.md`.
- **New Talk**: Create a `.md` file in `_talks/`.
    - **Required Front Matter**: `title`, `collection: talks`, `type`, `permalink`, `venue`, `date`, `location`.

### Asset Management

- **JavaScript**: Source files in `assets/js/`. Build/Minify using:
    ```bash
    npm run build:js
    ```
- **Talk Map**: `talkmap.py` generates a map of talk locations.
    - _Usage_: The script expects to find `.md` files in the current directory. It is currently located in the root but designed to process files in `_talks/`. You may need to adjust the script or run it from the correct context.

## Project Conventions

### Front Matter Patterns

- **Collections**: Explicitly set `collection: <name>` (e.g., `publications`, `talks`) in the front matter of content files to ensure they appear in the correct archives.
- **Permalinks**: Use explicit permalinks (e.g., `/publication/2019-Slam-performance-on-embedded-robots`) to maintain stable URLs.
- **Citations**: The `citation` field in front matter allows raw HTML (e.g., `<b>Author Name</b>`).

### Liquid & Jekyll

- **Site Variables**: Access global config via `site.config` (e.g., `site.title`).
- **Base URL**: Always prepend `{{ base_path }}` or `{{ site.url }}{{ site.baseurl }}` to internal links to ensure they work on both local and production environments.

### Styling

- **SCSS**: Modify `_sass/` files for style changes. The main entry point is likely `assets/css/main.scss` (or similar) which imports files from `_sass/`.
- **Customization**: Look for `_sass/_variables.scss` (if present) or specific component files to change colors/fonts.

## External Integrations

- **GitHub Pages**: The site is deployed via GitHub Pages. The `_config.yml` file controls settings like `url` and `baseurl`.
- **Analytics**: Configured in `_config.yml` under `analytics`.
- **Comments**: Configured in `_config.yml` (supports Disqus, etc.).
