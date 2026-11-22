# binodil.github.io

Source of the deployment for my personal website: **https://binodil.github.io**

The site is written with [Pelican](https://getpelican.com/) and built from a
separate repository by GitHub Actions:

- `.github/workflows/deploy.yml` runs on every push, daily at 00:00 UTC, or
  manually ("Run workflow" in the Actions tab), and publishes to GitHub Pages.
- `.github/workflows/build.yml` checks out the site sources with a read-only
  deploy key, builds them with Pelican, and uploads the result.

To get in touch, see https://binodil.github.io/work-with-me/
