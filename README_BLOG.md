# AI & High-Performance Computing Blog

A Jekyll-powered blog focused on AI research, GPU architecture, and high-performance computing insights.

## 🚀 Quick Start

### Prerequisites
- Ruby 3.0+
- Bundler
- Git

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/waqarahmed89/waqarahmed.github.io.git
   cd waqarahmed.github.io
   ```

2. **Install dependencies:**
   ```bash
   bundle install
   ```

3. **Run the development server:**
   ```bash
   bundle exec jekyll serve
   ```

4. **View the site:**
   Open http://localhost:4000 in your browser

### Adding New Posts

Create a new file in `_posts/` with the format: `YYYY-MM-DD-title.md`

```markdown
---
layout: post
title: "Your Post Title"
date: 2025-10-30 10:00:00 -0000
categories: [Category1, Category2]
tags: [tag1, tag2, tag3]
author: "Your Name"
---

Your post content here...
```

## 📁 Project Structure

```
├── _config.yml          # Site configuration
├── _layouts/            # Page templates
├── _posts/              # Blog posts
├── _sass/               # Sass stylesheets
├── assets/              # CSS, images, etc.
├── index.html           # Homepage
├── about.md             # About page
├── archive.html         # Posts archive
└── 404.html             # 404 error page
```

## 🎨 Customization

### Site Information
Update `_config.yml` with your personal information:
- Site title and description
- Author details
- Social media links

### Styling
Modify `_sass/main.scss` to customize the appearance.

### Colors
The theme uses a professional color palette:
- Primary: `#3182ce`
- Text: `#1a1a1a`
- Secondary text: `#4a5568`
- Light gray: `#718096`

## 📝 Features

- ✅ Responsive design
- ✅ Syntax highlighting
- ✅ SEO optimized
- ✅ RSS feed
- ✅ Pagination
- ✅ Archive page
- ✅ Social media links
- ✅ Professional styling

## 🌐 Deployment

### GitHub Pages
1. Push your changes to the main branch
2. Enable GitHub Pages in repository settings
3. Site will be available at `https://yourusername.github.io`

### Custom Domain (Optional)
1. Add a `CNAME` file with your domain
2. Configure DNS settings with your domain provider

## 📊 Analytics

To add Google Analytics:
1. Get your tracking ID
2. Add it to `_config.yml`:
   ```yaml
   google_analytics: UA-XXXXXXXXX-X
   ```

## 🔧 Troubleshooting

### Common Issues

**Bundle install fails:**
```bash
gem install bundler
bundle install
```

**Port already in use:**
```bash
bundle exec jekyll serve --port 4001
```

**Permission errors:**
```bash
bundle install --path vendor/bundle
```

## 📚 Learn More

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Guide](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ❤️ for the AI and HPC community