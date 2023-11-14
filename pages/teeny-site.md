---
template: default
title: Teeny-Site
author: noahreinalter
url: /teeny-site
description: Teeny-Site

---

# Teeny-Site

is a static site generator written initially by [Yakko Majuri](https://github.com/yakkomajuri) in JavaScript for his personal website.

The intention behind Teeny-Site is to be a simple, easy to use static site generator using Markdown for content and basic HTML templates for styling.

This fork adds a substitution feature to insert additional content into the generated HTML files using [front-matter](https://www.npmjs.com/package/front-matter) in the markdown.
Additionally, it optimizes the continuous build process by only rebuilding the files that have changed or depend on changed files.
