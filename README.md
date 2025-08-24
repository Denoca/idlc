IDLC Framework Website

This is a Jekyll-based static site for the IDLC (Infrastructure as Code Development Lifecycle) framework, hosted on GitHub Pages.

Maintenance





Update Content: Edit Markdown files in pages/ or pages/documentation/ for IDLC phase content. Use Markdown for simplicity.



Add Pages: Create new .md files in pages/ or pages/documentation/, with front matter like ---\ntitle: Page Title\nlayout: page\n---.



Assets: Place images in assets/images/, CSS/JS in respective folders.



Theme Customizations: Override Minima in assets/css/custom.css or _includes/.



SEO/Accessibility: Meta tags in _layouts/default.html; ARIA in includes.



Contributors: Update static list in pages/contributors.md. For dynamic, add JS to fetch GitHub API (not included).

Deployment





Push to main branch.



GitHub Pages builds automatically. Check settings > Pages.



Local test: bundle exec jekyll serve.

Prerequisites





Install Jekyll: gem install jekyll bundler



Run bundle install to install dependencies.



No external deps; all gems supported by GitHub Pages.