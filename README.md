# aymon.dev

Personal documentation and blog site for [aymon.dev](https://www.aymon.dev).

## Setup

This is a Jekyll site using the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme, hosted on GitHub Pages.

### Prerequisites

- Ruby (2.7 or higher)
- Bundler

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/aymond/aymond.github.io.git
   cd aymond.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Serve locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser.

## Project Structure

- `_config.yml` - Jekyll configuration
- `_pages/` - Static pages (About, Archives, etc.)
- `_posts/` - Blog posts
- `_data/` - Data files (navigation, etc.)
- `assets/` - Images and other assets
- `scripts/` - JavaScript files
- `styles/` - CSS stylesheets
- `index.html` - Custom landing page with gradient animation

## Customization

- Edit `_config.yml` to update site settings, author information, and social links
- Add posts in `_posts/` following the Jekyll naming convention: `YYYY-MM-DD-title.md`
- Customize navigation in `_data/navigation.yml`
- Modify `index.html` and `styles/style.css` for the landing page design

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the `master` branch.

## License

See [LICENSE](LICENSE) file for details.