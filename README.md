# Benjamin Serfhos - Jekyll Website

This is a Jekyll-based version of my personal portfolio website. It's been converted from a static HTML site to use Jekyll's templating system for better maintainability and content management.

## Features

- **Responsive Design**: Built with Bootstrap 5 for mobile-first responsive design
- **Jekyll Templating**: Uses Jekyll layouts and includes for consistent structure
- **Data-Driven Content**: Experience, skills, and other content stored in YAML data files
- **Blog Functionality**: Built-in blog with markdown support
- **SEO Optimized**: Includes meta tags and Open Graph data
- **Contact Form**: Ready-to-use contact form (requires Formspree setup)

## Structure

```
├── _config.yml          # Jekyll configuration
├── _data/               # Data files (YAML)
│   ├── about.yml        # About section content
│   ├── certifications.yml # Certifications data
│   ├── education.yml    # Education data
│   ├── experience.yml   # Work experience data
│   └── skills.yml       # Skills and technology stack
├── _layouts/            # Jekyll layouts
│   ├── default.html     # Main layout template
│   └── home.html        # Homepage layout
├── _posts/              # Blog posts (markdown)
├── assets/              # Static assets (CSS, JS, images)
├── blog/                # Blog index page
├── contact/             # Contact page
└── index.html           # Homepage
```

## Setup

1. **Install Ruby and Jekyll**:
   ```bash
   # Install Ruby (if not already installed)
   # On macOS with Homebrew:
   brew install ruby
   
   # Install Jekyll and Bundler
   gem install jekyll bundler
   ```

2. **Install Dependencies**:
   ```bash
   bundle install
   ```

3. **Run the Site Locally**:
   ```bash
   bundle exec jekyll serve
   ```

4. **View the Site**:
   Open your browser and go to `http://localhost:4000`

## Customization

### Site Configuration
Edit `_config.yml` to update:
- Site title and description
- Author information
- Company details
- Social media links

### Content Updates
- **Experience**: Edit `_data/experience.yml`
- **Skills**: Edit `_data/skills.yml`
- **Education**: Edit `_data/education.yml`
- **Certifications**: Edit `_data/certifications.yml`
- **About**: Edit `_data/about.yml`

### Adding Blog Posts
Create new markdown files in `_posts/` with the format:
```markdown
---
layout: default
title: "Your Post Title"
date: YYYY-MM-DD
excerpt: "Brief description of the post"
---

Your content here...
```

### Styling
- Main styles are in `assets/css/style.css`
- Highly inspired on Freelancer Theme for Bootstrap: https://startbootstrap.com/theme/freelancer
- Based on Bootstrap 5 with custom modifications
- Uses Font Awesome for icons

This project is open source and available under the [MIT License](LICENSE).

## Credits

- **Bootstrap**: [Bootstrap 5](https://getbootstrap.com/)
- **Font Awesome**: [Font Awesome](https://fontawesome.com/)
- **Jekyll**: [Jekyll](https://jekyllrb.com/)
- **Theme**: Based on Start Bootstrap Freelancer theme 
