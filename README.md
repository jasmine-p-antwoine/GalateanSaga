# Jasmine Author Website

Personal author website for The Galatean Saga, built with Hugo and the Nomad-Tech theme.

## Tech Stack

- **Static Site Generator**: Hugo v0.153.3
- **Theme**: [nomad-tech](https://github.com/helioLJ/nomad-tech-hugo-theme) @ 3b8b1fe
- **Hosting**: Netlify
- **Repository**: GitHub

## Local Development

### Prerequisites
- Hugo Extended v0.153.3 or higher
- Git

### Running Locally
```bash
cd D:\websites\jasmine-author-site
hugo server
```
Visit `http://localhost:1313` to preview.

## Deployment

Site automatically deploys to Netlify when changes are pushed to the `main` branch.

### Update Workflow
```bash
git add .
git commit -m "Description of changes"
git push origin main
```

## Project Structure

- `content/` - Site content (posts, pages)
- `static/` - Static assets (images, files)
- `themes/nomad-tech/` - Theme files
- `hugo.toml` - Hugo configuration
- `netlify.toml` - Netlify build settings

## License

Content © [Year] Jasmine [Your Last Name]. All rights reserved.
