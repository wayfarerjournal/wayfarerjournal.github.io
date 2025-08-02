# Wayfarer Journal

A personal travel blog built with Jekyll and designed for GitHub Pages.

## Getting Started

### Prerequisites

- Ruby (version 2.6 or higher)
- RubyGems
- GCC and Make

### Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/wayfarerjournal/wayfarerjournal.github.io.git
   cd wayfarerjournal.github.io
   ```

2. **Install Jekyll and dependencies**
   ```bash
   bundle install
   ```

3. **Run the site locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **View your site**
   Open your browser and go to `http://localhost:4000`

## Site Structure

```
wayfarerjournal.github.io/
├── _posts/          # Blog posts
├── _config.yml      # Site configuration
├── Gemfile          # Ruby dependencies
├── index.md         # Homepage
├── about.md         # About page
└── README.md        # This file
```

## Adding New Posts

Create new posts in the `_posts` directory with the following naming convention:
`YYYY-MM-DD-title.md`

Example:
```markdown
---
layout: post
title: "My Amazing Trip to Paris"
date: 2024-01-20 12:00:00 +0000
categories: travel europe
author: Wayfarer
---

Your post content here...
```

## Customisation

- Edit `_config.yml` to change site settings
- Modify the theme in `_config.yml` (currently using "minima")
- Add new pages by creating `.md` files in the root directory
- Customise styling by creating `assets/css/` directory

## Deployment

This site is configured for GitHub Pages. Simply push your changes to the main branch and GitHub Pages will automatically build and deploy your site.

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the [MIT License](LICENSE). 