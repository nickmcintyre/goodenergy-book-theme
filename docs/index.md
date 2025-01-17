# The Quantecon Book Theme


**An interactive book theme for Sphinx**.

This is a lightweight Sphinx theme designed to mimic the look-and-feel of an
interactive book. It has the following primary features:

* **[Bootstrap 4](https://getbootstrap.com/docs/4.0/getting-started/introduction/)**
  for visual elements and functionality.
* **[Flexible content layout](layout)** that is inspired by beautiful online books,
  such as [the Edward Tufte CSS guide](https://edwardtufte.github.io/tufte-css/)
* **[Visual classes designed for Jupyter Notebooks](notebooks)**. Cell inputs, outputs,
  and interactive functionality are all supported.
* **[Launch buttons for online interactivity](launch)**. For pages that are built with
  computational material, connect your site to an online BinderHub for interactive content.

## Get started

To get started with `goodenergy-book-theme`, first install it with `pip`:

```
pip install goodenergy-book-theme
```

then, activate the theme in your Sphinx configuration (`conf.py`):

```
...
html_theme = "goodenergy_book_theme"
...
```

This will activate the Sphinx Book Theme for your documentation. Note that you may
need to change your `html_theme_options` configuration depending on your previous
theme. See the pages to the left for information about what you can configure with
`goodenergy-book-theme`.

## Site contents

```{toctree}
:maxdepth: 1
:caption: Main docs

configure
Controlling page elements <layout>
notebooks
launch
contributing
GitHub repository <https://github.com/nickmcintyre/goodenergy-book-theme>
```

## Reference pages

```{toctree}
:caption: Reference items
:maxdepth: 2

reference/index
api/index
```

## Acknowledgements

This theme is heavily inspired by (and dependent on)
[PyData Sphinx Theme](https://pydata-sphinx-theme.readthedocs.io/) for its base
structure and configuration.
