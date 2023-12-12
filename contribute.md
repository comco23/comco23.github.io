---
layout: default
---

## How to contribute to the wiki page

### Getting started

This tutoral assumes you have the following dependencies installed:

* [Github account](https://github.com/)
* [Git](https://git-scm.com/): a distributed version control system used for tracking changes in source code during software development
* [Ruby](https://www.ruby-lang.org/en/): a dynamic, open-source programming language. It's required for Jekyll, the static site generator used for the NBP Lab Wiki.
* [Ruby Gems](https://rubygems.org/): package manager for the Ruby programming language. It's used to manage Ruby libraries and dependencies.
* [Bundler](https://bundler.io/): static site generator. It transforms plain text into static websites and blogs, and it's used to build the NBP Lab Wiki.
* [Jekyll](https://jekyllrb.com/): a static site generator. It transforms plain text into static websites and blogs, and it's used to build the nbp lab wiki
* [Any code editor](https://code.visualstudio.com/): it is needed for viewing and editing the project files. for example, Visual Studio Code is a popular choice.

### 1. **Github collaboration:**
- get added as a collaborator to the [nbp lab wiki github repository](https://github.com/nbplabwiki/nbplabwiki.github.io).

### 2. **Set up your local computer environment:**

- open a terminal (MacOS users) or command prompt (Windows users) on your local machine.
- clone the repository to your local computer:
   ```
   git clone https://github.com/nbplabwiki/nbplabwiki.github.io.git
   ```
   - note: you may also download the repository as a zip file from [this link](https://github.com/nbplabwiki/nbplabwiki.github.io/) and extract the zip file to your deisred folder.

- navigate to the cloned project directory:
   ```
   cd nbp-lab-wiki
   ```
### 4.**Open repo on using any code editor (e.g. VS Code)** 

### 5.**Familarize yourself with the folder structures**

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

### 6. **Learn the Git basics:**
- to view the lab wiki page on your local computer environment
   ```
   bundle exec jekyll serve
   ```
- copy and paste the server address to your local browser to preview
- most relevant git commands (for publishing your changes):
   
   ```bash
   # Check the status of your changes
   git status

   # Add changes to the staging area
   git add .

   # Commit changes
   git commit -m "Your commit message"

   # Push changes to GitHub
   git push origin main
   ```
[back](/)