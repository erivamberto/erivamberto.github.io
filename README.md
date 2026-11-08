# erivamberto.github.io

Personal academic website of **José Erivamberto Lima Oliveira**, Associate Professor at the Universidade Estadual do Ceará (UECE/FAFIDAM) and PhD in Mathematics (UFC).

🌐 **Live site:** <https://erivamberto.github.io/>

## About the site

The site presents my research in Analysis, focused on quasilinear and fully nonlinear elliptic PDEs and free boundary problems, together with my teaching and outreach activities.

- **about** – short biography and research interests
- **publications** – research articles, submitted preprints, and theses and dissertations (generated from [`_bibliography/papers.bib`](_bibliography/papers.bib))
- **blog** – Mathematics Club activities, participation in events, and opinion pieces
- **links** – academic profiles (MathSciNet, ORCID, Lattes, ResearchGate), social media, and contact

## Built with al-folio

This website is built with [**al-folio**](https://github.com/alshedivat/al-folio), a simple, clean, and responsive [Jekyll](https://jekyllrb.com/) starter for academic websites created by [Maruan Al-Shedivat](https://github.com/alshedivat) and contributors. This repository started as a copy of the al-folio template and was customized with my own content. Many thanks to the al-folio maintainers and community.

al-folio is distributed under the [MIT License](LICENSE), which is kept in this repository.

## Running locally

```bash
bundle install
npm ci
bundle exec jekyll serve
```

Then open <http://localhost:4000/>. For more details, see the [al-folio documentation](docs/README.md).

## Deployment

The site is hosted on [GitHub Pages](https://pages.github.com/). Pushes to the `main` branch trigger the [deploy workflow](.github/workflows/deploy.yml), which builds the site and publishes it.
