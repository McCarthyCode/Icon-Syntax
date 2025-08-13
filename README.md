# IconSyntax

[https://iconsyntax.org](https://iconsyntax.org)

## About

An educational tool for those with difficulty learning English by traditional means. Features a blog and a search engine that allows users to pick a category and/or type in a query to find icons.

## Current Features

* **Icon Dictionary** &ndash; A search tool and catalog for icons, each representing a word, phrase, conjunction, punctuation, etc.
* **Icon Literature** &ndash; Example library of literary works using icons with syntax
* **Blog** &ndash; Posts from the site owners

## Planned Features

* **Lesson Authoring** &ndash; A form for creating lessons to learn a foreign language (e.g., English)
* **Tutor Interface** &ndash; A tool, based on lessons created by authoring tool, for learning a foreign language with image, text, and audio examples

## Repository Usage

The repository includes two submodules: `front-end` and `back-end`. After cloning this parent repository by normal means (i.e. `git clone` or `gh repo clone`), these two directories will be left blank. To populate them, run the following:

```bash
$ git submodule update --init --recursive
```

For more information on submodules, visit [https://git-scm.com/book/en/v2/Git-Tools-Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) or run any of the following help commands:

```bash
$ git submodule help
$ man git-submodule
```

Additionally, at a later date, this repository will include a script and/or instructions for building Docker images from source.
