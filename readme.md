# Nbp lab wiki

This site is built using [jekyll](https://jekyllrb.com).

## Getting Started

### Prerequisites

1. Make sure `ruby` and `gem` is installed. \
   `ruby -v` \
   `gem -v` \
   If not, make sure to install it.
2. Install `bundle`, `bundler` and `jekyll`. \
   `sudo gem install bundle jekyll bundler`

### Runing The Site Locally

1. Clone the site first. \
   `git clone https://github.com/nbplabwiki/nbplabwiki.github.io.git`
2. Change to the project root. \
   `cd [your folder name]`
3. Install the necessary gems required by the site. \
   `bundle install`
4. Run the local development server. \
   `bundle exec jekyll serve`
5. Visit the development server address in your favourite browser. By default it is `localhost:4000`.

## Project Structure

The site follows the normal site structure as mentioned in the jekyll documentation [here](https://jekyllrb.com/docs/structure/).

### File and Folder Descriptions

* The project root or the folder where you find the `Gemfile` is called as `Project Root` or `/`.
* `/_includes/`: the common portions of the site that are used in multiple html pages.
* `/_layouts/`: the layouts for the site, that are used in the html pages.
* `/_posts/`:
* `/_sass/`:
* `/assets/`: contains css, js and other assets for the site.
* `/script/`:
* `/slides/`:
* `/tags/`:
* `/_config.yml`: site global data and config for jekyll.
* `/.editorconfig`: contains config for `Editorconfig` text editor configurations.
* `/.gitignore`: contains files to be ignored by `git`.
* `/Gemfile`: contains the project dependencies.
* `/index.md`: this website's homepage
* `/jekyll-theme-minimal.gemspec`:
* `/readme.md`: contains the project documentation.

## View Website

<a href = "https://nbplabwiki.github.io/" > View website using this link </a>