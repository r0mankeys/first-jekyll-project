---
layout: page
title: Permalinks
permalink: /permalinks/
---

This is a guide on permalinks with jekyll.

Think of permalinks as url's for your pages or posts that use relative paths for names.

A permalink will change the url of the current page or posts that the browser is showing, you can name it anything but it would make more snese to make it a relative path for conciseness.

e.g.1. if you have a an `about.md || about.markdown` file (same thing, `.md` is just a shorthand) located in your root directory then the permalink to use would be `/about/`.

e.g.2. if you had a `<YEAR-MONTH-DAY-post-name>.md` file located in your `_posts` folder, the permalink would be `/posts/<whatever-you-want-the-post-link-name-to-be>`

> **_Note:_** You can assign variables in a permalink with the syntax `/:<variable-name>/` for a dynamic experience
