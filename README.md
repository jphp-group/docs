Documentation
=============

JPHP's documentation is based on [sphinx-doc](http://sphinx-doc.org/). You can always find the last
version of the documentation on http://jphp-docs.readthedocs.org/.

### How to generate docs?

You need to install the sphinx-doc system with Python 2.7 or 3+.
After this, install the `sphinxcontrib-phpdomain` and `sphinx_rtd_theme` extensions
via the `pip` or `easy_install` commands.

At the end, cd to the root of the docs and:

```
sphinx-build -b html . _build
```

Or you can download the last html portable version here:
https://media.readthedocs.org/htmlzip/jphp-docs/latest/jphp-docs.zip
