# Nerea Montes-Pérez — personal website

A [Quarto](https://quarto.org/) website for research, publications, CV and creative work. Edit the `.qmd` pages and `styles.css`; GitHub Pages serves the rendered files in `docs/`.

## Preview on your computer

Install [Quarto](https://quarto.org/docs/get-started/), then open a terminal:

```bash
git clone https://github.com/NerMonPer/nermonper.github.io.git
cd nermonper.github.io
quarto preview
```

Quarto opens a local browser preview and refreshes it when you save changes. If the repository is already on your computer, run `git pull` inside it instead of cloning again. Press Ctrl+C in the terminal to stop previewing.

## Publish changes

Run `quarto render` from the repository directory. This creates the site in `docs/` as configured in `_quarto.yml`. Commit both the edited source files and updated `docs/` files, then push to `main`. GitHub Pages serves the site at [nermonper.github.io](https://nermonper.github.io/).

The artwork in `assets/` is decorative. The former photography URL redirects to the creative work page, so old links still work.
