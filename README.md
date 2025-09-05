
# Professional Jekyll GitHub.io Site

This is a professional, minimalist Jekyll site with classic styling, dark/light theme support, and responsive design for desktop, laptop, and mobile devices. It includes Blogs, CV, and Projects tabs, with the CV page configured for easy updates and PDF export to assets/files/cv-*.pdf.

## Setup Instructions

1.  Create a new GitHub repository named username.github.io.
    
2.  Clone the repository locally: git clone https://github.com/username/username.github.io.git.
    
3.  Install Ruby and Jekyll: sudo apt-get install ruby ruby-dev build-essential (Linux) or brew install ruby (macOS).
    
4.  Install Jekyll and Bundler: gem install jekyll bundler.
    
5.  Create the following file structure in the repository.
    
6.  Run bundle install in the project directory.
    
7.  Start the local server: bundle exec jekyll serve.
    
8.  Deploy to GitHub Pages by pushing to the main branch: git push origin main.
    

## File Structure and Content

### _config.yml

Configuration file for Jekyll site settings.

title: Your Name - Professional Portfolio description: A professional portfolio showcasing my blog, CV, and projects. baseurl: "" url: "https://username.github.io" theme: minima markdown: kramdown permalink: /blog/:title collections: projects: output: true permalink: /projects/:title plugins: - jekyll-feed - jekyll-seo-tag exclude: - Gemfile - Gemfile.lock