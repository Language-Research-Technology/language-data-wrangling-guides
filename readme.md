# Language Data Wrangling Guides

NOTE: at present (5 June 2026) this material is such a rough sketch it doesn't even count as a first draft. Significant change is expected, all feedback and suggestions are welcome.

This is the source for a website for technical and dataset design guidance for researchers and research software developers working with language data.

## Editing

This website is written in [Quarto](https://quarto.org/). It is currently in the very early draft stages. Contributions from within LDACA are welcome at this stage, but while the overall structure and plan is still in flux things will probably be easiest if you coordinate your changes with Betsy (e.alpert@uq.edu.au), Sam, or Simon.

To preview your changes on your local machine, use `quarto preview` for a live site that will update as you make changes (when you save the files), or `quarto render` to fully build the output static pages in the same way as the publishing does.

Note: do not commit any rendered output files to git, they will not be used in the actual site and will just make for merge conflicts in future.


## Publishing

Automatic rendering and publishing of the website is set up using [quarto publish](https://quarto.org/docs/publishing/github-pages.html#publish-command) and GitHub actions. When you push or merge a commit onto the `main` branch of the GitHub repository, a GitHub action will immediately render the site and save it to the `gh-pages` branch of the repository, which is what is used for the GitHub Pages-hosted website. Do not directly edit files in the `gh-pages` branch, those changes will be lost when the site is next updated.

## Citation, Licensing, Copyright

TBA

All material (so far at least) is by the [Language Data Commons of Australia](https://www.ldaca.edu.au).

