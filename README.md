# hugo-mock-landing-page

This repo uses a GitHub Actions workflow that automatically builds and deploys the Hugo website to GitHub Pages whenever changes are pushed to the main branch. The workflow:
- Fetches submodules for themes
- Publishes to the gh-pages branch using GitHub's authentication
- Supports custom domain configuration (commented out by default)
