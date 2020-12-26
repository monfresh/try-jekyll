---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
Welcome to My Home Page

{% assign date = '2020-04-13T10:20:00Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}

This is a new change to the index page.

Let's see if this shows up after building on main, then adding contents of _site to gh-pages branch and pushing, without using GitHub Actions.

Does this work without JEKYLL_TOKEN secret?
