# blog

A personal blog built with Jekyll and hosted on GitHub Pages.

## About

This repository contains the source code for my personal blog. The blog is automatically built and deployed to GitHub Pages using GitHub Actions.

## Local Development

To run the blog locally:

1. Install Ruby (version 3.0 or higher recommended)
2. Install bundler: `gem install bundler`
3. Install dependencies: `bundle install`
4. Build the site: `bundle exec jekyll build`
5. Serve the site: `bundle exec jekyll serve`
6. Open your browser to `http://localhost:4000`

## Technology Stack

- **Jekyll**: Static site generator
- **GitHub Pages**: Hosting platform
- **Minima**: Default Jekyll theme
- **GitHub Actions**: Automated deployment

## Adding Posts

To add a new post:

1. Create a new file in the `_posts` directory
2. Name it following the convention: `YYYY-MM-DD-title.md`
3. Add front matter at the top:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS +0000
   categories: category1 category2
   ---
   ```
4. Write your content in Markdown
5. Commit and push to trigger automatic deployment

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.