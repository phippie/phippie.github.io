This is the source of PHippie's public [Web site](http://phippie.github.io/).
=======

This Web site is rendered with GitHub pages.

To run this locally

* [Fork this](https://github.com/phippie/phippie.github.io/fork) repo and clone to your file system
* [Install Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
* Run `bundle install` if you are running it for the first time
* Run `bundle exec jekyll serve` in the cloned repo folder
* you will be able to access the site at http://localhost:4000

Or with Docker
* [Fork this](https://github.com/phippie/phippie.github.io/fork) repo and clone to your file system
* `docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 4000:4000 jekyll/jekyll:pages bundle exec jekyll serve`
* you will be able to access the site at http://localhost:4000