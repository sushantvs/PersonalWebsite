# Personal Website

![Jekyll](https://img.shields.io/badge/Jekyll-4.2.2-yellow)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-brightgreen)

A modern personal website built using Jekyll 4+ and deployed to GitHub Pages.

## Features
- Responsive design
- Blog functionality
- Custom 404 page
- GitHub Actions CI/CD pipeline
- Easy content management through Markdown

## Project Structure
```
PersonalWebsite/
├── _config.yml       # Main configuration
├── _data/            # Data files
├── _posts/           # Blog posts
├── 404.html          # Custom 404 page
├── index.markdown    # Main page content
├── Gemfile           # Ruby dependencies
└── README.md         # Project documentation
```

## Getting Started

### Prerequisites
- Ruby 3.3+
- Bundler

### Installation
1. Clone the repository
2. Install dependencies:
   ```bash
   apt install build-essential ruby ruby-dev
   gem install bundler
   bundle install
   ```
3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```
   
## Deployment
The site is automatically deployed to GitHub Pages through GitHub Actions. See the workflow in `.github/workflows/`.

## Acknowledgments
- Inspired by [Hacked-Jekyll](https://github.com/piazzai/hacked-jekyll) And also [j47.in](https://github.com/jatinkrmalik/j47.in)
- Deployment guide from [Moncef Belyamani](https://www.moncefbelyamani.com/making-github-pages-work-with-latest-jekyll)

