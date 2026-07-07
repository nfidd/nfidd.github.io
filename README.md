
# NFIDD landing page

Source for the NFIDD organisation landing page at
<https://nfidd.github.io/>. It links out to the individual NFIDD courses,
resources, and events, each of which lives in its own repository and is
published at `https://nfidd.github.io/<repo>/`.

The site is a single-page [Quarto](https://quarto.org) website. On every push
to `main`, the [`deploy`](.github/workflows/deploy.yaml) GitHub Actions workflow
renders the site and publishes it to the `gh-pages` branch, which GitHub Pages
serves at the organisation root.

To add or update a course, edit the card in [`index.qmd`](index.qmd).

## Local preview

Render the site locally with:

``` sh
quarto render
```

or preview with live reload:

``` sh
quarto preview
```

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<!-- prettier-ignore-start -->

<!-- markdownlint-disable -->

All contributions to this project are gratefully acknowledged using the
[`allcontributors` package](https://github.com/ropensci/allcontributors)
following the [all-contributors](https://allcontributors.org)
specification. Contributions of any kind are welcome!

### Code

<a href="https://github.com/nfidd/nfidd/commits?author=sbfnk">sbfnk</a>,
<a href="https://github.com/nfidd/nfidd/commits?author=seabbs">seabbs</a>,
<a href="https://github.com/nfidd/nfidd/commits?author=kathsherratt">kathsherratt</a>,
<a href="https://github.com/nfidd/nfidd/commits?author=dependabot[bot]">dependabot\[bot\]</a>,
<a href="https://github.com/nfidd/nfidd/commits?author=github-actions[bot]">github-actions\[bot\]</a>,
<a href="https://github.com/nfidd/nfidd/commits?author=jamesmbaazam">jamesmbaazam</a>,
<a href="https://github.com/nfidd/nfidd/commits?author=ManuelStapper">ManuelStapper</a>,
<a href="https://github.com/nfidd/nfidd/commits?author=zsusswein">zsusswein</a>

### Issues

<a href="https://github.com/nfidd/nfidd/issues?q=is%3Aissue+author%3Atoshiakiasakura">toshiakiasakura</a>,
<a href="https://github.com/nfidd/nfidd/issues?q=is%3Aissue+author%3Ajcken95">jcken95</a>,
<a href="https://github.com/nfidd/nfidd/issues?q=is%3Aissue+author%3ADegoot-AM">Degoot-AM</a>,
<a href="https://github.com/nfidd/nfidd/issues?q=is%3Aissue+author%3Aepiforecasts-workflows">epiforecasts-workflows</a>

<!-- markdownlint-enable -->

<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
