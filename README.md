# Technical Blog - Jimmy Byrd

Personal technical blog covering Red Hat technologies, infrastructure automation, and system administration. **Styled with Red Hat's official design system.**

**Live site:** <https://blog.jbyrd.org>

## Red Hat Design System

This blog uses Red Hat's official design system with:

### Typography
- **Headings**: Red Hat Display (bold, sans-serif)
- **Body**: Red Hat Text (readable, professional)
- Fonts loaded from Google Fonts CDN

### Color Palette
- **Red Hat Red**: `#EE0000` (primary brand color)
- **Dark Red**: `#A30000` (hover states)
- **Black**: `#151515` (text)
- **Gray Scale**: `#3C3F42`, `#6A6E73`, `#D2D2D2`, `#F5F5F5`
- **White**: `#FFFFFF` (backgrounds)

### Design Principles
- **Sentence case** for all headings and text
- **Generous spacing** and white space for readability
- **Bold accents** using Red Hat red
- **Clean hierarchy** with clear visual structure
- **Accessibility-first** with proper contrast ratios

## Features

- ✅ **Red Hat branding** throughout the site
- ✅ **Custom Jekyll layouts** (default, home, post, page)
- ✅ **Responsive design** for mobile and desktop
- ✅ **SEO optimized** with proper meta tags
- ✅ **RSS feed** for subscribers
- ✅ **Social sharing** buttons on posts
- ✅ **Author bio** sections
- ✅ **Post navigation** (previous/next)
- ✅ **Categories and tags** support

## Topics

* Red Hat Enterprise Solutions (RHEL, Ansible, OpenShift)
* Infrastructure Automation
* System Administration
* Home Lab Projects (MiracleMax)
* Personal AI Infrastructure (PAI)

## Technology Stack

- **Static Site Generator**: Jekyll 3.10+
- **Hosting**: GitHub Pages
- **Domain**: blog.jbyrd.org (via CNAME)
- **Styling**: Custom Red Hat CSS
- **Fonts**: Red Hat Display + Red Hat Text

## Local Development

### Prerequisites

- Ruby 2.7+
- Bundler
- Jekyll

### Setup

```bash
# Clone the repository
git clone https://github.com/thebyrdman-git/blog-jbyrd-org.git
cd blog-jbyrd-org

# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# Visit http://localhost:4000
```

### Live Reload

```bash
bundle exec jekyll serve --livereload
```

## Writing a New Post

Create a new file in `_posts/` with the format: `YYYY-MM-DD-title.md`

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0400
categories: [category1, category2]
tags: [tag1, tag2]
author: "Jimmy Byrd"
---

Your content here...
```

## File Structure

```
blog-jbyrd-org/
├── _config.yml              # Site configuration
├── _layouts/                # Custom Red Hat layouts
│   ├── default.html         # Base layout with header/footer
│   ├── home.html            # Homepage layout
│   ├── post.html            # Blog post layout
│   └── page.html            # Static page layout
├── _posts/                  # Blog posts
│   └── 2025-10-19-welcome-to-my-technical-blog.md
├── assets/
│   └── css/
│       └── redhat-style.css # Red Hat design system CSS
├── about.md                 # About page
├── index.md                 # Homepage
├── CNAME                    # Custom domain config
└── Gemfile                  # Ruby dependencies
```

## Deployment

This site automatically deploys via GitHub Pages when you push to the `master` branch.

```bash
# Make changes
git add .
git commit -m "Your commit message"
git push origin master

# GitHub Pages will automatically build and deploy
# Site will be live at https://blog.jbyrd.org in ~1 minute
```

## Customization

### Update Site Info

Edit `_config.yml`:

```yaml
title: "Technical Blog"
description: "Red Hat TAM | Infrastructure Automation | System Administration"
author: "Jimmy Byrd"
email: "jbyrd@redhat.com"
```

### Modify Colors

Edit `assets/css/redhat-style.css` and update CSS variables:

```css
:root {
  --rh-red: #EE0000;
  --rh-black: #151515;
  /* ... */
}
```

### Add New Layouts

Create new files in `_layouts/` directory using existing layouts as templates.

## Red Hat Brand Compliance

This blog uses Red Hat's official:
- Color palette
- Typography (Red Hat Display + Red Hat Text)
- Design principles (open, clean, professional)
- Spacing and layout guidelines

**Note**: Red Hat and the Red Hat logo are trademarks of Red Hat, Inc. This is a personal blog and is not officially affiliated with or endorsed by Red Hat, Inc.

## About

Technical blog by **Jimmy Byrd** - Red Hat Technical Account Manager specializing in Ansible Automation Platform, RHEL, and enterprise infrastructure.

### Resources

- 📝 **Blog**: <https://blog.jbyrd.org>
- 🏠 **Website**: <https://jbyrd.org>
- 💻 **GitHub**: [thebyrdman-git](https://github.com/thebyrdman-git)
- 📧 **Email**: jbyrd@redhat.com

---

Built with ❤️ using Jekyll and Red Hat's design system.
