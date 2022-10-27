
## Building the site

1. [Install Jekyll](http://jekyllrb.com), [NodeJS](https://nodejs.org/) and [Bundler](http://bundler.io/).
4. `bundle install`
5. `./serve.sh`
6. open in your browser: `http://localhost:4000`

## Editing the site

This site makes Jekyll's "layout", "include", and "configuration" features. Read about those under "site structure" on the [Jekyll docs](https://jekyllrb.com/docs/structure/).

Edit the global site sidebar at `_include/sidebar_top.html`, `_include/sidebar_bottom.html`, and the various `_include/nav_XX.html`. The persistent sidebar is only split into a top and bottom component because the navigation section in the center changes for each page (with an arrow that floats over the current page).

Edit/add pages in `content/whatever.html`, images and files in content/assets, then run `serve.sh` to test the site. This is run with `livereload = TRUE` in `_config.yml`, and will automatically update on file changes.
