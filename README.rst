sphinxcontrib-githubribbon
==========================

`sphinxcontrib-githubribbon` is a Sphinx extension to put a `GitHub Ribbon` to each HTML pages.

.. _GitHub Ribbon: https://github.com/blog/273-github-ribbons

Usage
-----

Append this extension in conf.py::

    extensions = ['sphinxcontrib.github_ribbon']


And update settings:

``github_ribbon_repo``
    The location of your repository.  By default, `"sphinx-doc/sphinx"`.

``github_ribbon_position`` = ("left" | "right")
    The position of ribbon.  By default, `"right"`.

``github_ribbon_color`` = ("red" | "green" | "darkblue" | "orange" | "gray" | "white")
    The color of ribbont.  By default, `"red"`.

Special Thanks
--------------

Members of Sphinx-users.jp!
