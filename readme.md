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

* Project Root (`/`): The main directory where you find the `Gemfile` and essential project files.
* `/_includes/`: Contains common portions of the site used in multiple HTML pages.
* `/_layouts/`: Holds layouts for the site, which are used in HTML pages.
* **`/_posts/`: Stores individual blog posts written in Markdown.**
* `/_sass/`: Includes Sass stylesheets, providing a modular and organized way to manage styles.
* `/assets/`: Contains CSS, JS, and other assets for the site, such as images or fonts.
* `/script/`: Holds scripts or executable files associated with the project.
* **`/slides/`: A folder that stores presentation slides or related materials.**
* `/tags/`: Contains files or data related to categorizing content based on tags.
* `/_config.yml`: Stores site global data and configuration for Jekyll.
* `/.editorconfig`: Contains configurations for text editors using Editorconfig.
* `/.gitignore`: Lists files to be ignored by Git during version control.
* `/Gemfile`: Specifies project dependencies using Bundler.
* **`/index.md`: The homepage of this website, written in Markdown.**
* `/jekyll-theme-minimal.gemspec`: A Gemspec file specifying information about the Jekyll theme as a Ruby gem.
* `/readme.md`: Contains project documentation, providing an overview of the project and its structure.

## View Website

<a href = "https://nbplabwiki.github.io/" > View website using this link </a>