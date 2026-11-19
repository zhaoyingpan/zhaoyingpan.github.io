# zhaoyingpan.github.io

Personal academic website for Zhaoying Pan, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and hosted on GitHub Pages.

## Local preview

```bash
bundle install
npm install
npm run build:js
bundle exec jekyll serve --host 0.0.0.0 --config _config.yml,_config_docker.yml
```

Then open <http://localhost:4000>.

The Jekyll command stays running while the preview is available. Stop it with
`Ctrl+C`. When working on a remote machine, forward port `4000` to your local
computer or use your editor's **Ports** panel to open the forwarded URL.

## Content

- Site and profile settings: `_config.yml`
- Homepage: `_pages/about.md`
- Publications: `_publications/`
- Teaching: `_teaching/`
- Navigation: `_data/navigation.yml`
