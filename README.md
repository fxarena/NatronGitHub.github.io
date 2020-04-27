# Open Source Compositing Software For VFX and Motion Graphics

## Proposed sitemap

This is my proposed new sitemap, it's a little different from Rodlie's but I think it's good.... feedback is appreciated! -Hank

* Home
  * `index.html`
    * Hero image
    * Key features of Natron (not Jekyllified, IMO there is no reason to make posts for each feature as these cards not going to be added onto in the same way that blog posts are)
    * Shows one  news image and description from all posts with the tag ``news``. Currently this is `_posts/*-news-*.md`
    * Section that directs to the downloads page, alternatively we can ditch the downloads page and just build it into a section, this might be nicer?

* News
  * `news.html`
    * A blog style page that lists whatever y'all want to put on there, major release updates, in depth talks about features and whatnot

* About
  * `about.html`
    * A more in-depth look at some of Natron's key features that has more text than the original cards on the home page can allow for
    * Sponsorship information
    * How to contribute to development

* Community
  * `community.html`
    * It would be _really_ cool to have some sort of Nukipedia-like website to replace the Natron community plugins but that's a really long-term stretch goal
    * This will likely be a link to the Pixls.us forums.

* Docs
  * This one is tricky.  IMO a proper docs website should probably be a different website entirely with the nav bar from this one tacked onto it.  This isn't otherworldly difficult to do and GitHub Pages makes it pretty easy to make multiple repos look like one website in the browser but that's just my opinion.

## Building for development

This website uses Jekyll, get that [here](https://jekyllrb.com/). You'll likely want to install [rbenv](https://github.com/rbenv/rbenv) as well to manage multiple installs of Ruby on your machine, sometimes the one you have installed by default is not the version that Jekyll likes.

`cd` to the git repo

`bundle install` to install all the dependencies used by GitHub Pages

`bundle exec jekyll serve --incremental` to start Jekyll @ localhost:4000

Navigate to localhost:4000 in the browser and get to writing code!  The server will check for updates and rebuild the website every time you save a file.