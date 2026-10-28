# Jiarui Shi — Portfolio

Personal website: [verashi17.github.io](https://verashi17.github.io/)

This site presents my background, work experience, research, and software projects. The About page is the homepage, and the Projects page contains a text-first overview of selected work. A PDF resume is linked from the navigation.

## Edit the content

- About and contact details: [`_pages/about.md`](_pages/about.md)
- Work experience: [`_data/experiences.yml`](_data/experiences.yml)
- Research and software projects: [`_data/portfolio_projects.yml`](_data/portfolio_projects.yml)
- Social links: [`_data/socials.yml`](_data/socials.yml)
- Resume PDF: [`assets/pdf/Resume_Jiarui_Shi.pdf`](assets/pdf/Resume_Jiarui_Shi.pdf)
- Portfolio styling: [`_sass/_portfolio.scss`](_sass/_portfolio.scss)

## Run locally

With Docker installed, run:

```bash
docker compose up --build
```

Open [http://localhost:8080](http://localhost:8080/). Stop the server with `Ctrl+C`.

## Deployment

The site is configured as a GitHub Pages user site in [`_config.yml`](_config.yml). Pushing site changes to `main` runs the [deployment workflow](.github/workflows/deploy.yml), which builds the Jekyll site and writes the finished files to `gh-pages`. In the repository's **Settings → Pages**, set the publishing source to **Deploy from a branch**, with **gh-pages** and **/(root)** selected.

## Credits

Built with [Jekyll](https://jekyllrb.com/) and customized from the [al-folio](https://github.com/alshedivat/al-folio) theme. The original theme's MIT license is retained in [`LICENSE`](LICENSE).
