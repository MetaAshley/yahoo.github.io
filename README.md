Yahoo Open Source
=====================

This is a GitHub Pages site build with [Jekyll](http://jekyllrb.com/) and hosted on [GitHub Pages](http://pages.github.com/).

To Run Locally
--
1. Clone this branch
2. Install Jekyll: `gem install jekyll`
3. Make sure everything is setup with `bundle install`
4. Run `jekyll serve --watch`
5. Access the docs at `http://localhost:4000`

### Dev Note
- `jekyll serve --watch` will compile the Jekyll and Sass files into static assets in the **_site** folder each time a file is saved. That folder is excluded from the repo.
- There is no easy way to use Jekyll plugins with GitHub pages, so none are used here.
- The repositories are injected via `site.github.public_repositories` object. In production, GitHub sends it real data. For local builds, static data is used

Dependencies (all included)
--
- **[jQuery 1.9](https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js)**
- **[Modernizr](http://modernizr.com/)**
- **[Handlebars.js](http://handlebarsjs.com/)**
- **[Isotope](http://isotope.metafizzy.co/)**
