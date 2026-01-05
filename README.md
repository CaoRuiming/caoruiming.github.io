# Raymond Cao's Website

A modern, professional personal website built with [Hugo](https://gohugo.io/). This site is designed to showcase professional background, project posts, and blog posts with a focus on performance, accessibility, and maintainability.

## Features

- **Responsive Design**: Mobile-friendly layout using Vanilla CSS and BEM naming convention.
- **Theme Toggle**: Support for Light, Dark, and Auto (system preference) modes.
- **Configurable Social Links**: Easily manage social links via `content/_index.md`.
- **Font Awesome Support**: Scalable icons for social media and other elements.
- **Automatic Deployment**: Integrated with GitHub Actions for seamless deployment to GitHub Pages.
- **Semantic HTML**: Built with accessibility and SEO in mind.

## Development

### Prerequisites

- [Hugo](https://gohugo.io/)

### Running Locally

To start the development server with live reloading:

```bash
hugo server -D
```

The site will be available at `http://localhost:1313/`.

### Building the Site

To generate the static site files in the `public/` directory:

```bash
hugo
```

## Content Management

- **Homepage**: Edit `content/_index.md` to update your biography, interests, education, and social links.
- **Experience**: Add or edit markdown files in `content/experience/`.
- **Projects**: Add or edit markdown files in `content/projects/`.
- **Blog Posts**: Add or edit markdown files in `content/posts/`.

## Deployment

This project is configured to deploy automatically to GitHub Pages using GitHub Actions.

1. **GitHub Setup**:
   - Push your code to a GitHub repository.
   - Go to **Settings > Pages**.
   - Under **Build and deployment > Source**, select **GitHub Actions**.

2. **Wait for Workflow**:
   - The workflow defined in `.github/workflows/hugo.yml` will trigger on every push to the `main` branch.
   - It will build the site using Hugo and deploy the `public` folder to the `gh-pages` environment.

## License

This project is open-source and available under the MIT License.
