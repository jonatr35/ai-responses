# AI Responses

A searchable collection of AI responses and conversations, published as a GitHub Pages site.

## 🚀 Quick Start

1. **Enable GitHub Pages**: Go to your repository settings → Pages → Source: Deploy from a branch → Branch: main
2. **Access your site**: Visit `https://yourusername.github.io/ai-responses`

## 💻 Local Development

To run the site locally:

1. **Install dependencies** (first time only):
   ```bash
   bundle install
   ```

2. **Run the development server**:
   ```bash
   bundle exec jekyll serve
   ```

3. **Access the site**: Open your browser to `http://127.0.0.1:4000/ai-responses/`

The site will auto-reload when you make changes to files.

### Additional Commands

**Build without serving** (just generate the static files):
```bash
bundle exec jekyll build
```

**Serve with live reload and drafts**:
```bash
bundle exec jekyll serve --livereload --drafts
```

**Serve on a different port**:
```bash
bundle exec jekyll serve --port 4001
```

### Prerequisites

You'll need Ruby installed on your system:
- **macOS**: Ruby comes pre-installed, or use `brew install ruby`
- **Linux**: `sudo apt-get install ruby-full` (Ubuntu/Debian)
- **Windows**: Use [RubyInstaller](https://rubyinstaller.org/)

## 📁 Adding New Responses

Create new files in the `_responses/` directory with this format:

```markdown
---
title: "Your Response Title"
date: YYYY-MM-DD
tags: ["tag1", "tag2", "tag3"]
excerpt: "Brief description of the response content"
---

# Your AI Response Content

Write your response content here in Markdown format...
```

## 🏗 Site Structure

- `_config.yml` - Jekyll configuration
- `_layouts/` - Page templates
- `_responses/` - Collection of AI responses
- `assets/css/` - Styling
- `index.html` - Homepage with search functionality

## 🔍 Features

- **Live Search**: Type to search through all responses
- **Responsive Design**: Works on desktop and mobile
- **Tagging System**: Organize responses with tags
- **Jekyll Collections**: Automatic page generation
- **Clean URLs**: SEO-friendly response URLs

## 📝 File Naming

Use descriptive, kebab-case filenames:
- `python-debugging-tips.md`
- `react-best-practices.md`
- `fitness-training-plan.md`

## 🎨 Customization

Edit these files to customize your site:
- `_config.yml` - Site title, description, and settings
- `assets/css/style.css` - Styling and colors
- `_layouts/default.html` - Overall page structure

## 🏷 Recommended Tags

**Technical**: `programming`, `python`, `javascript`, `web-development`, `debugging`, `api`, `database`

**Content Types**: `tutorial`, `explanation`, `troubleshooting`, `code-review`, `best-practices`

**Domains**: `fitness`, `cooking`, `travel`, `business`, `productivity`, `design`

### Prompts

You are looking for a new SUV for your family of 6. You want an SUV that can tow at least 5,000lbs and you are prioritizing cargo space behind the 3rd row seats and reliability. Your max budget is $20,000. Cargo space would ideally be min 18 max 35. Create a list of top 5 options and pros and cons of each.