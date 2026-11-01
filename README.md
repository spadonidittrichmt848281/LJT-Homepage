# Junteng Liu — Homepage

Personal academic homepage of **Junteng Liu**, first-year PhD candidate at the **HKUST NLP Group**, Hong Kong University of Science and Technology.

The site is built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and published with GitHub Pages.

## Pages

- **About** (`/`): biography, research interests, education, research experience, publications, skills and contact information.
- **Publications** (`/publications/`): publication list.

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)

## Repository layout

- `_config.yml` — site and author configuration
- `_data/navigation.yml` — header navigation
- `_pages/about.md` — the About page
- `_pages/publications.html` — the Publications page
- `_publications/` — individual publication records

## Publishing

The `/.github/workflows/jekyll.yml` workflow builds the site with Jekyll and deploys it to GitHub Pages on pushes to `master`.

GitHub Pages must be enabled for the repository with **GitHub Actions** as the build source: **Settings → Pages → Build and deployment → Source: GitHub Actions**. Enabling Pages is a one-time repository-admin action; the `GITHUB_TOKEN` used by Actions cannot create the Pages site itself.
