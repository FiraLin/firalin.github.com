# Lin's Site

firalin.github.com
==================

I made this site for my fira.

## About the theme

This blog started with the beautiful theme [MrZhang.me](https://github.com/jsw0528/octopress), created by [张](http://mrzhang.me/) (?).

More details about the theme can be found in the article, [Blog = GitHub + Octopress - MrZhang.me](http://mrzhang.me/blog/blog-equals-github-plus-octopress.html).

## Problems

When `rake install['blog']` (`rake install\['blog'\]` for `zsh`), one has to manually remove `.git` and `.gitignore` files from the folder `sass/_base`. This will avoid the following error,

	fatal: Not a git repository: sass/_base/../../../../.git/modules/.themes/blog/sass/_base

