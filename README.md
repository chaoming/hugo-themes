# Hugo Themes Development Repository

This repository serves as the root development environment for my Hugo themes. It's structured to manage multiple Hugo themes and their corresponding demo sites using Git submodules.

## Current Themes

### Hugo Saasify Theme
A modern Hugo theme designed for SaaS websites, built with TailwindCSS. The theme development is organized into two repositories:

- `hugo-saasify-theme`: The main theme repository containing all theme-specific code and assets
- `hugo-saasify-demo`: A demo site repository that showcases the theme's features and serves as a testing ground

## Repository Structure

```
.
├── hugo-saasify-demo/          # Demo site for the Saasify theme
│   └── themes/
│       └── hugo-saasify-theme/ # The Saasify theme (submodule)
└── README.md
```

## License

MIT
