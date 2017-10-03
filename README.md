# WattCharger

WattCharger is a platform that unifies multiple charging cards, allowing you to travel longer distances easily, i.e., less time spent creating accounts(other charging cards) for each country you visit. Also simplifies the process of finding new charging posts that are compatible with your EV specifications.


## Setup

1. Add your site and author details in `_config.yml`.
2. Add your Google Analytics, Google Maps API and Disqus keys to `_config.yml`.
3. Get a workflow going to see your site's output (with https://www.zecarlos94.github.io/WattCharger/) or Jekyll locally).

## Develop

WattCharger was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

### Contact Form

* Configured to work with FormSpree(https://formspree.io/)).

### Staff

* Reused around the site to save multiple editing locations(about us section).

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Navigation* section.

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Footer* section.
