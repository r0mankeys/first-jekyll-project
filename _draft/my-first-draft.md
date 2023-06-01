---
layout: post
title: My first draft
---

This is my first drafts folder, these are the steps to making it!

. First create a `_drafts` folder in the root of your project directory.

. Next `cd` into that sub_directory and create a draft in the format `<draft-name>.md` (Your draft dosen't have to be named with the standard naming convention for posts because it is not yet a post, it's date will just be the date it was last modified, however once you add it to your posts, the name will need to be modified)

Drafts are not visible by default, you can however see your drafts by restarting your server using the following code:

. First you have to quit the current server (if there is one) by typing `CTRL + c` in the terminal (this terminates any ongoing terminal commands by the way)

Then run the following in the terminal:

```
jekyll serve --draft
```

This will build all your posts and drafts as if all your drafts were posts.
