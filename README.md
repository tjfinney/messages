---
title: "README"
author: "TJF"
date: "2018"
output: html_document
---

This is a collection of messages I've written. The messages are written in Markdown using RStudio, archived on GitHub, and hosted on Netlify.

## Typical workflow

1. Create a new MarkDown doc in `/home/tim/Keep/www/etij.net/tim/Messages/content/posts` (can duplicate an existing one)
2. Issue command `hugo server -F` from `/home/tim/Keep/www/etij.net/tim/Messages` (as it contains `config.toml`; "F" flag builds future-dated posts)
3. Navigate to [http://localhost:1313/](http://localhost:1313/) with a browser
4. Edit the doc and see what it looks like in the browser.

To publish the result, commit, push to GitHub, then browse to Netlify:

1. `git add *`
2. `git commit -m "..."`
3. `git push`
4. Browse to [https://tjfinney-messages.netlify.com/](https://tjfinney-messages.netlify.com/).

## Images

Use the full path to an image if using *Preview*. E.g. `![An old synagogue in Capernaum](/home/tjf2n/Keep/www/etij.net/Tim/Messages/static/images/Capernaum.jpg)`. A short path is used in production. E.g. `![An old synagogue in Capernaum](/images/Capernaum.jpg)`.

## References

To get references to work, click "Preview" in RStudio then push to Github.
