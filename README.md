My teaching materials for the Open R Sessions at Lund University (both autumn and spring version), organised as a quarto website. At the end of each semester (as of VT 2025), the site is archived via GitHub releases.

This quarto site uses [R for WebAssembly](https://github.com/r-wasm) to enable interactive teaching examples in a static website framework.

# Dependencies
- Requires [Quarto v1.6+](https://quarto.org/)
- Requires [R](https://www.r-project.org/)

# Usage

The repo is setup as a [Quarto Project](https://quarto.org/docs/projects/quarto-projects.html), using the [website template](https://quarto.org/docs/websites/).

Build the site, which is built in `/_site` folder:

```{bash}
quarto render
```

# Attributions

- [`slides/slides.scss`](slides/slides.scss) is forked from the revealjs theme: [`grantmcdermott/quarto-revealjs-clean`](https://github.com/grantmcdermott/quarto-revealjs-clean)

# To contribute

Create a pull request or issue.
