# Contributing to the NFIDD landing page

Thanks for helping improve the NFIDD landing page. This repository holds only the
organisation homepage at <https://nfidd.github.io/>. The courses themselves live
in their own repositories under the [`nfidd` organisation](https://github.com/nfidd)
— contribute to course content there.

## Adding or updating a course, resource, or event

The homepage is a single [Quarto](https://quarto.org) page,
[`index.qmd`](index.qmd). Each course is a card in one of the grouped grids
(*Courses & resources*, *Taught courses*, *Events*). To add one, copy an existing
card block and update the heading, link, and description:

```markdown
::: {.g-col-12 .g-col-md-6}
### [Course title](https://nfidd.github.io/<repo>/){target="_self"}
One or two sentences describing the course.
:::
```

Keep links pointing at the published site (`https://nfidd.github.io/<repo>/`), not
the source repository.

## Previewing locally

```sh
quarto preview
```

This renders the site with live reload so you can check your change before opening
a pull request.

## Reporting problems

Open an [issue](https://github.com/nfidd/nfidd.github.io/issues) for broken links,
missing courses, or suggestions.
